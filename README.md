# backend-challenge

Todoist API Tests with Postman and Newman.

Download the zip, unzipped the content, open your favorite IDE and open the project folder. Once inside, open a new terminal and type:

```
npm i newman -g
```

Also, install the reporter:

```
npm i newman-reporter-htmlextra
```


Now, you are setup to run all the tests. Run in the terminal:
```
npm run testAPI
```
This command will initialize the test, and will create a report.html in the reports folder of the project. A report is also included if you don't want to run all the tests.

Finally, to run the test that creates several tasks from a csv file, just run in the terminal:
```
npm run test-several-tasks 
```
An html report named SeveralTasksReport.html will be created in the reports folder.

