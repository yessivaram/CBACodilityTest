CBACodilityTest (API Framework) - Instructions to run the project

Pre-requisite:
-----------------
Java 8+ and Maven 

Steps to run from local machine:
-------------------------------------------
1. clone the repository from GitHub into your local directory
2. open command prompt and go to your local repository location using cd command
3. run the mvn command "mvn clean test" in the command prompt

Cucumber HTML Report -> target/cucumber-html-reports/overview-features.html

Steps to run from CI (GitHub Actions)
--------------------------------------------------
1. Click on "Actions" tab
2. Click on "Run PetStore API Automation Suite in GitHub Actions" on the left panel.
3. Click on Run workflow button on the right side
4. Select the branch "feature/Sivaram-CBATest"
5. Click on "Run workflow" button
6. The workflow should be triggered now and click on the workflow followed by build
7. Click on Build and test Maven Project step.
8. Test execution results can be found at the bottom of the execution log.


Test Coverage:
--------------------
EverythingAboutPet feature contains all the positive and negative test cases with data driven testing for Pet endpoints from PetStore Swagger.
Few negative test cases are not automated due to the mismatches between the expected and actual test results.
Those are clearly updated in the feature file comments section.
