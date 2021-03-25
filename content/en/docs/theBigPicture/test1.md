---
title: "Test1"
date: 2020-10-09T03:15:26-07:00
weight: 2150
---
# Section Test

All Modernapps Ninja learning content is publicly accessible and available openly, however a free membership is required to take tests and recieve a certificate of completion for the course. You must first [join the community](https://modernapps.ninja/about/membership/) and [register for this course]() before attempting to submit a test.

Ninja tests use devops tools and processes so the testing system itself is educational and provides both experience and validation of foundational devops skills. 

{{< youtube J_nV5YPypqs >}}

## Instructions

This test uses automated grading, you must follow the instructions exactly to ensure the automated grading will complete successfully. 

To complete the test you must review the questions on this page, and fill in your answers on a seperate answer sheet provided below. We recommend opening the answer sheet for the test in a seperate browser tab so you can fill in the answers as you proceed through the questions. 

Every question in this test is titled "Question" followed by its order, for example Question1, Question2 etc...

All questions will provide a list of possible answers. Each possible answer is represented by a lowercase letter, the first response is option "a", the second is option "b" and so on, as shown in the example questions below. 

The Answer sheet will open in Github's web-based editor, similar to the image shown below:

![Example Test Response Sheet](/vSphereTanzu101_VT7933/admin/assets/images/blank_test_screen_example.png)

### Example Questions

Tests may contain two types of questions, multiple choice single answer, and multiple choice multiple answer, as shown in the examples below.

#### Example Multiple Choice Single Answer Question

```
Question1: What value will the bash shell return when you enter the command `echo hello`?

Answers:
  a: banana
  b: hello
  c: apple
  d: shutdown commencing
```

The correct answer to Question1 is `b` as the command will return the value hello. 

On your answer sheet, you would fill in the value `b` for Question1, as shown in the following example:

```
Question1: b
Question2:
Question3:
```

#### Example Multiple Choice Multiple Answer Question

```
Question2: Which of the following are fruits? (Select 3)

Answers:
  a: banana
  b: hello
  c: apple
  d: shutdown commencing
  e: orange
```

**IMPORTANT**: When providing answers to multiple choice multiple answer questions, it is important your responses are in alphabetical order. For example, the correct answer for Question2 above is `a,c,e`, in alphabetical order, with a comma between each answer. If you provided the answer as `a,e,c`, the grading service would mark your answer incorrect as the response values were not provided in alphabetical order.

Partially correct answers will be counted as incorrect, no partial credit is given.

You do not need to put spaces between each value in your response, but the grading service will ignore spaces if present. 

On your answer sheet, you would fill in the value `a,c,e` for Question2, as shown in the following example:

```
Question1: b
Question2: a,c,e
Question3:
```

### Submitting your test response

After you fill in responses to all questions, scroll to the bottom of the screen and click the propose changes button as shown below:

![propose_new_file](/vSphereTanzu101_VT7933/admin/assets/images/propose_changes.png)

After you click propose changes:
- GitHub will automatically create a copy of the course repository on a new special copy of the repository called a **fork** in your github account.
- Your proposed changes will be saved to a [branch](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-branches) on your fork of the repository.
- Your browser will be directed to a screen where you can submit the updated document from your fork to the course repository

Your browser should now show the `Comparing Changes` screen, as shown in the image below:

![comparing_changes](/vSphereTanzu101_VT7933/admin/assets/images/comparing_changes.png)

Observe that in the top part of the Comparing Changes screen:
- The `base repository` is the repository you are proposing changes to
- The `head repository` is your fork of the repository, where the updates you have made are saved
- A directional arrow points from the head repository toward the base repository, indicating that you want the proposed update to be merged from the head, into the base repository

The bottom part of the Comparing Changes Screen shows the names of any files that are proposed to be updated, and displays and highlights the lines of files proposed to be changed. 

Review the proposed file changes to ensure your responses look correct, and then click the `Create pull request` button.

### Reviewing your test response

After you click the `Create pull request` button, you will be directed to a new page where you can review the status of your pull request. 

At the same time, an automated github actions workflow will evaluate your test responses, and post a response sheet to your member repo where you can review results at the link https://github.com/modernappsninjas/YOUR-MEMBER-REPO-Name/admin/userdata/COURSE_REPO_NAME/testresults directory. If you passed the test, it will also be indicated on the course card



submit the updates as a git [pull request](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to the course respository, where an administrator can choose to approve, modify, or reject your proposed changes to the file. 









In this case, a Github Actions based automated workflow will capture and grade your responses, post a message on your member repo with your test results, and close the pullrequest ticket.




#### [Please Click Here to Proceed with the Introduction Section](../tanzukubernetesgridoverview/)