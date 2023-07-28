# api-automation-project

Small project to automate api testing scenarios on https://www.automationexercise.com/ practice website.

Check out [test scenarios](https://www.automationexercise.com/api_list) :point_left:

## Getting started

If you don't have Newman:

```
npm install -g newman
npm install -g newman-reporter-htmlextra
```

Clone repository and run tests in CLI:

```
git clone git@github.com:micsiw/api-automation-project.git
cd api-automation-project
npm test
```

or generate report with [htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra) reporter:

```
npm run test-report
```

## Built with

- [Postman](https://www.postman.com/)
