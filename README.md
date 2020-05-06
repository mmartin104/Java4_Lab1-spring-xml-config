# Lab 1: Configuring Spring with XML

In this lab you will get hands on practice configuring the Spring IOC container using XML (eXtensible Markup Language). In the beginning, this was the only way to configure dependencies so you will often see it in legacy projects. 

## Getting Started

1. Create a private repository for this assignment by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#create-a-private-repository-for-completing-this-assignment) making the following substitutions:
    * For step 2, use this URL: [https://github.com/jeff-anderson-cscc/lab1-spring-xml-config/generate](https://github.com/jeff-anderson-cscc/lab1-spring-xml-config/generate) to create your private repository from my template
    * For step 3, name your repository: ``lab1-spring-xml-config``
1. Add me as a collaborator so I can view and grade your work by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#add-me-as-a-collaborator-so-i-can-view-and-grade-your-work)
1. Create and checkout a new project for this lab in IntelliJ by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#create-and-checkout-a-new-project-for-this-lab-in-intellij)
1. **IMPORTANT:** Before you start coding, create a new branch for your work as [described here](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#important-before-you-start-coding)

## Completing the Assignment

**Important: You may not change the code in any test cases.** _For a passing grade, the only permissible difference between the base version of each JUnit test class and yours is yours will have no tests commented out and the file is otherwise identical._

Instructions for completing the assignment:

1. The Community edition may not automatically configure all Spring artifacts so, if necessary, create a "resources" directory under ``src/main``
1. Open ``XmlConfigTests`` in the editor:
    1. Move the /* -- top block comment line to below the first Test
    1. Right click in the editor window and choose "Run XmlConfigTests"
    1. Change just enough code / configuration to make that test pass
    1. Repeat the last 3 steps until every test method runs without error
1. Once you are done, commit your changes using "VCS" -> "Commit":
    * Make sure the commit includes any new files you created
    * Enter a proper comment
    * Uncheck "Perform code analysis"

## Hints from the Documentation

1. The IoC Container
    * [1.2.1. Configuration Metadata](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/core.html#beans-factory-metadata)
    * [1.3.2. Instantiating Beans](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/core.html#beans-factory-class)
    * [1.4.1. Dependency Injection](https://docs.spring.io/spring-framework/docs/current/spring-framework-reference/core.html#beans-factory-collaborators)


## Submitting your work


1. Push your changes to GitHub, create a pull request, and ask for my review by following [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#push-your-changes-and-create-a-pull-request-for-grading)
1. Once I have reviewed and approved your pull request, follow [these procedures](https://github.com/jeff-anderson-cscc/lab0-completing-and-submitting-assignments#once-your-pull-request-is-reviewed-and-approved) to submit your assignment in Blackboard


