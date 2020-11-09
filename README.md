# Evergreen

Getting up to speed with [Cypress](http://cypress.io)

A cypress is an ___evergreen___. If your tests stay ever green, you're golden.

## Motivation

As a Functional Testing tool, Cypress is relatively new but shows promise.

Now that web applications are increasingly reactive, front-end tests are important.

This has always been an area where good tools are lacking, so I was interested in
Cypress. Specifically, it should help make Front-end Developers more Agile.

And of course the best way to learn something is to play with it.

## Javascript-based

Cypress is JavaScript-based which makes navigating a DOM straightforward. This may
well obviate the need for HTML Parsing libraries such as [Cheerio](http://cheerio.js.org).

Cypress plays well with [Mocha](http://mochajs.org) and [Chai](http://chaijs.com).

## Browsers Supported

As contrasted with [Selenium](http://selenium.dev), browser support is more limited - as of November, 2020:

1. Chrome
2. Firefox
3. Edge
4. Electron
5. Brave

[These are probably sufficient for most purposes.]

## Browser-based

Cypress operates directly in the browser, however the browser may be invoked headlessly.

## CORS

Being browser-based, it looks like Cypress can bypass some CORS limitations.

## Fast, with no network lag

Unlike other tools, Cypress does not use a [Selenium WebDriver](http://www.selenium.dev/projects/#selenium-webdriver).
This should mean that Cypress testing is faster (no WebDriver ramp-up time needed),
also no network lag.

## Screen captures

Cypress records screen captures of failing tests.

## Video record

Cypress records video of the tests (this video needs to be slowed-down quite a lot).

[In practice, this option seems like overkill and should be disabled.]

## Electron

Cypress can interact with Electron applications (such as [Postman](http://www.postman.com)
and Cypress Test Runner).

## Examples

For an example of running a Dockerized version of Cypress with Travis CI:

    http://github.com/mramshaw/hello-world-cypress

For an example of integrating CI (GitHub Actions) with a Vue app using Cypress:

    http://github.com/mramshaw/VueRender

## To Do

- [ ] Investigate adding Cypress test to a React app
- [x] Investigate adding Cypress test to a Vue app

## Credits

Easy End-to-End Testing with Cypress:

    http://mtlynch.io/painless-web-app-testing

Running a Docker version of Cypress on mac:

    http://github.com/bahmutov/cypress-open-from-docker-compose

    https://www.cypress.io/blog/2019/05/02/run-cypress-with-a-single-docker-command/

Running a Docker version of Cypress on linux:

    https://stackoverflow.com/questions/59514234/viewing-the-interactive-cypress-test-runner-in-docker-on-linux
