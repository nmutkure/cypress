# cypress
Cypress demo repository

Here are some Multiple Choice Questions (MCQs) for Cypress certification preparation:

1. What is Cypress primarily used for?
a) API Testing
b) UI Automation Testing
c) Performance Testing
d) Security Testing

Answer: ✅ b) UI Automation Testing

2. Which command is used to visit a URL in Cypress?
a) cy.go()
b) cy.open()
c) cy.visit()
d) cy.load()

Answer: ✅ c) cy.visit()`

3. Cypress runs on which type of architecture?
a) Client-Server
b) Node.js Runtime + Browser
c) Multi-threaded Java Engine
d) WebSocket-based Execution

Answer: ✅ b) Node.js Runtime + Browser

4. How do you select an element with an id="username" in Cypress?
a) cy.get('username')
b) cy.find('#username')
c) cy.get('#username')
d) cy.query('#username')

Answer: ✅ c) cy.get('#username')

5. Which Cypress command is used to interact with an input field?
a) cy.enter()
b) cy.type()
c) cy.fill()
d) cy.sendKeys()

Answer: ✅ b) cy.type()`

6. How do you handle an iframe in Cypress?
a) Cypress has built-in iframe support
b) Use cy.getIframe().find()
c) Use cy.get('iframe').its('0.contentDocument.body').then(cy.wrap)
d) Use cy.frame()

Answer: ✅ c) Use cy.get('iframe').its('0.contentDocument.body').then(cy.wrap)

7. How do you retry an assertion in Cypress?
a) Cypress automatically retries assertions
b) Use cy.retry()
c) Use cy.assert()
d) Cypress does not support retrying assertions

Answer: ✅ a) Cypress automatically retries assertions

8. Which Cypress command is used to handle API requests?
a) cy.fetch()
b) cy.api()
c) cy.request()
d) cy.http()

Answer: ✅ c) cy.request()`

9. What is the correct way to intercept network requests in Cypress 10+?
a) cy.route()
b) cy.spy()
c) cy.intercept()
d) cy.stub()

Answer: ✅ c) cy.intercept()`

10. Cypress uses which type of assertions by default?
a) Chai
b) Jest
c) Mocha
d) Selenium Assertions

Answer: ✅ a) Chai

11. What is the command to wait for an API response in Cypress?
a) cy.waitForAPI()
b) cy.wait('@alias')
c) cy.apiWait()
d) cy.listen('@alias')

Answer: ✅ b) cy.wait('@alias')`

12. What is the recommended way to handle flaky tests in Cypress?
a) Increase timeout values
b) Use cy.wait() for long delays
c) Remove all assertions
d) Improve test reliability by using better selectors and retry logic

Answer: ✅ d) Improve test reliability by using better selectors and retry logic

13. How do you disable an assertion timeout in Cypress?
a) cy.disableTimeout()
b) cy.wait(0)
c) cy.get(selector, { timeout: 0 })
d) cy.noTimeout()

Answer: ✅ c) cy.get(selector, { timeout: 0 })`

14. Which Cypress feature allows running tests in parallel?
a) Cypress Dashboard
b) Cypress Executor
c) Cypress Multi-Run
d) Cypress Cluster

Answer: ✅ a) Cypress Dashboard

15. Cypress does not support which type of browser?
a) Chrome
b) Firefox
c) Safari
d) Internet Explorer

Answer: ✅ d) Internet Explorer

16. What is the best practice for selecting elements in Cypress?
a) Use XPath selectors
b) Use hardcoded timeouts
c) Use data-test attributes
d) Use randomly generated IDs

Answer: ✅ c) Use data-test attributes

17. How can you pause the test execution in Cypress?
a) cy.pause()
b) cy.stop()
c) cy.break()
d) cy.debug()

Answer: ✅ a) cy.pause()`

18. How do you perform drag-and-drop in Cypress?
a) Cypress does not support drag-and-drop
b) cy.dragAndDrop()
c) cy.get().trigger('dragstart') followed by cy.get().trigger('drop')
d) cy.get().simulate('drag')

Answer: ✅ c) cy.get().trigger('dragstart') followed by cy.get().trigger('drop')

19. Which Cypress configuration file is used in Cypress 10+?
a) cypress.json
b) cypress.config.js
c) cypress-settings.json
d) cypress.config.ts

Answer: ✅ b) cypress.config.js

20. What is the command to take a screenshot in Cypress?
a) cy.screenshot()
b) cy.takeScreenshot()
c) cy.snap()
d) cy.capture()

Answer: ✅ a) cy.screenshot()`


//---------------------------Lambad Certification Notes

Key Topics to Prepare:
Running Cypress Automation Tests

Understand cy.get(), cy.visit(), cy.click(), cy.type(), etc.
Handling assertions (should(), expect(), assert()).
Using beforeEach() and afterEach().
Running Cypress tests in headless mode (cypress run --headless).
Cross-Browser Testing with Cypress on Cloud Grid (LambdaTest)

LambdaTest integration with Cypress using the LambdaTest Tunnel.
Running tests on Chrome, Firefox, Edge, Safari using the LambdaTest platform.
Executing Cypress tests in parallel on LambdaTest Cloud Grid.
Using lambdatest-config.json to set up cloud test runs.
Cypress Features (Screenshots, Videos, Headless Testing, Env Variables)

Screenshots & Videos:
cy.screenshot() (for capturing failures or steps).
Automatic video recording (video: true in cypress.config.js).
Environment Variables:
Setting up CYPRESS_ENV variables using cypress.config.js.
Using Cypress.env('VAR_NAME') for different environments.
Headless Testing:
Running tests without UI using cypress run --headless.
LambdaTest Cypress Certification - Likely MCQs
How do you integrate Cypress with LambdaTest?
a) Use cy.visit('lambdatest.com')
b) Configure lambdatest-config.json and run tests via CLI
c) Use cy.runOnCloud()
d) Install Cypress Lambda Plugin

Answer: ✅ b) Configure lambdatest-config.json and run tests via CLI

Which command runs Cypress tests in headless mode?
a) cypress run --headless
b) cypress headless
c) cypress run --silent
d) cypress execute

Answer: ✅ a) cypress run --headless

Which file is used to configure parallel testing in LambdaTest for Cypress?
a) cypress.json
b) lambdatest-config.json
c) parallel-config.js
d) lambda-parallel.json

Answer: ✅ b) lambdatest-config.json

How to Practice?
Sign up for LambdaTest and run Cypress tests in the cloud.
Use LambdaTest's parallel testing feature to speed up test execution.
Run tests across different browsers and versions on the LambdaTest grid.
Enable Cypress screenshots and video recording in cypress.config.js.

