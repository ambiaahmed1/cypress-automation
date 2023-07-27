# cypress-automation

### How to run :

Commands | Defination | 
--- | --- | 
npx cypress open  |  opens cypress app > select E2E > Spec file to run |
npx cypress run  |  without opening cypress app (runs all spec files default: headless)  | 
npx cypress run --headed   |  without opening cypress app (runs all spec files headed mode)  | 
npx cypress run --spec cypress\e2e\myFirstTest.cy.js --headed |  runing specific spec file in headed mode | 
npx cypress run --browser chrome  |  headless chrome browser | 
npx cypress run --browser chrome --headed |  headed chrome browser | 
