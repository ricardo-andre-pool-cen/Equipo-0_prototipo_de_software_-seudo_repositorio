# NEW REQUIREMENTS

- ## USER STORIE_01

>*As a beginner user learning git, i want to see all the information about git in different style formats so i can comprehend it better*
>
>**Acceptance criteria:**
>
>- There are graphs and images as visual help.
>- The information is presented as audio playables.
>- Formats (graphs, diagrams) that describe a process are animated
>- There is not other information or advertisings that could distract me while learning.

- ## USER STORIE_02

>*As a beginner user learning git, i want to easily find the contents of git inside the environment so i don't waste time looking for those.*
>
>**Acceptance criteria:**
>
>- The information is divided, from big containers to smaller:
>Big container contains:
> Description, Medium container contains:
> Little amount of information, Smaller container contains:
> Big amount of information.
>- There is a tool that could take me to direct content (ex. search bar), it's not hard to find and use.
>- Inside the medium and small content: The information is presented inside dropdown menus, with icons and names.

- ## USER STORIE_03

>*As a beginner user learning git, i want to have knowledge tests in the environment so i can evaluate myself the contents i just read*
>
>**Acceptance criteria:**
>
>- There is a can be found at the end of every article.
>- The user can change the test format once he finishes one.
>- The user can finish the test anytime he wants, with any amount of responses.

## USE CASES

- ## FOR USER STORIE_01: USE CASE 01

Use case | See all the information about git in different style formats
--------- | ------------------------------------------------------------
Objective | The user can verify that all the information about git is displayed in different style formats
Pre-conditions | The user has already access the system
Successful end | It's verifiable that all the information about git is displayed in different style formats
Fail end | It's not verifiable that all the information about git is displayed in different style formats (doesn´t exists)
Principal actors | Beginner user learning git
Happy path | Step 1: enters to an article<br>Step 2: opens the interactive content (audios, menus, graphs, images)
Exceptions | The user can't find where the articles are (Return to step 1)

- ## FOR USER STORIE_03: USE CASE 03

Use case | Perform knowledge tests in the environment
--------- | ------------------------------------------------------------
Objective | The user can perform knowledge tests in the environment
Pre-conditions | The user has already explore all parts of an article
Successful end | The user can evaluate himself the contents he just read in the article.
Fail end | The user can´t evaluate himself the contents he just read in the article.
Principal actors | Beginner user learning git
Happy path | Step 1: finish an article<br>Step 2: starts a test<br>Step 3: answers the test<br>Step 4: finish the test
Exceptions | The user goes out of the test without finishing (Return to step 2)
