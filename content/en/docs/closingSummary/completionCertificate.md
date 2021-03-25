---
title: "Course Completion Certificate"
date: 2020-10-09T03:15:26-07:00
weight: 6015
---

If you have completed all tests in the course and recieved over 70% correct responses, you can make an automated request to recieve a certificate of completion for this course. 

{{< youtube ywLPw0QdU08 >}}

To request your certificate of completion:
1. In a seperate browser tab navigate to: https://github.com/ModernAppsNinja/vSphereTanzu301_vt4163/tree/main/static/admin/userdata/certs_awarded
2. Click on the `Add file` button to add a new file
3. Name the file using your own github username in the format `yourgithubusername.yml`
4. In the body of the file type: `Status: Completed`
5. Click on `Propose new file` and then `Create pull request` to submit your new file. 

When you submit your new file as described in the steps above (also called making a pull request) it will trigger an automated github action workflow that will:
- Compare the total quantity of tests in the course with the quantity of tests you have completed to ensure you have completed all required tests for the course
- Tabulate the total quantity of all test questions from all tests
- Compare the quantity of questions you have answered correctly against the total quantity of questions for all tests to ensure you have attained a minimum of 70% correct answers
- Post grade report and updated course record card to your member repository
- Append a message to the pull request to notify the requesting user the course grading is complete, the result, and links to the updated grade report and course record card. 
  - The requesting members github account will be mentioned in the posted message, which will trigger a github notification to the requestors github account and associated email address. 

In the event that a user requests a certificate and does not have the minimum required grade to pass, a grade report will be provided that will include details on the percent of correct answers for each test in the course, highlighting which test(s) may need to be retaken to achieve a passing grade. Members can then retake any tests necesarry to increase their grade, and then repeat the above process again to request that the certificate service run again. 

If you encounter any problems with testing or with the certificate process, please open an issue ticket on this course.


