## Cypress

### Click and type events in after or afterEach hook don't work if one test fails
Any click event in the after block fails if one of the tests in an it block fails. Known Cypress issue.

#### Workaround

use force type and force click in after or ```afterEach``` Hooks

or

use ```scrollIntoView``` function before ```click()```

or

wrap click:

```
Cypress.Commands.add('forceClick', { prevSubject: 'element' }, (subject, options) => {
    cy.wrap(subject).click({ force: true });
});
```
