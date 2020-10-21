# Team Profile Generator

A Node CLI that takes in information about employees and generates an HTML webpage that displays summaries for each person.

![Screen Shot 2020-10-20 at 10 24 28 PM](https://user-images.githubusercontent.com/63524583/96665568-2d510680-1323-11eb-88b6-ca030258e9df.png)

## Instructions

The application will prompt the user for information about the team manager and then information about the team members. The user can input any number of team members, and they may be a mix of engineers and interns. 

This app must also pass all unit tests. When the user has completed building the team, the application will create an HTML file that displays a nicely formatted team roster based on the information provided by the user. 

* Your app will run as a Node CLI to gather information about each employee.
  
It is recommended that you start with a directory structure that looks like this:

```
lib/           // classes and helper code
output/        // rendered output
templates/     // HTML template(s)
test/          // jest tests
  Employee.test.js
  Engineer.test.js
  Intern.test.js
  Manager.test.js
app.js         // Runs the application
```

### User input

The project prompts the user to build an engineering team. An engineering
team consists of a manager, and any number of engineers and interns.

![Screen Shot 2020-10-20 at 10 26 16 PM](https://user-images.githubusercontent.com/63524583/96665658-67baa380-1323-11eb-851b-48cf14daa427.png)

### Roster output

The project generates a `team.html` page in the `output` directory, that displays a nicely formatted team roster. Each team member displays the following in no particular order:

  * Name

  * Role

  * ID

  * Role-specific property (School, link to GitHub profile, or office number)