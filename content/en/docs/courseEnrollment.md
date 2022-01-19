---
title: "Course Enrollment"
date: 2020-10-12T18:34:25-07:00
weight: 1020
draft: false
---

- [Video Overview](#video-overview)
- [Enroll for this course](#enroll-for-this-course)
  - [Step 1 - Open the new course enrollment document link](#step-1---open-the-new-course-enrollment-document-link)
  - [Step 2 - Name your file](#step-2---name-your-file)
  - [Step 3 - Add a line to your file](#step-3---add-a-line-to-your-file)
  - [Step 4 - Submit your enrollment document](#step-4---submit-your-enrollment-document)

## Important Notice: 

**The Enrollment, testing and digital badge features will be removed on Friday February 18th, 2022. Please ensure you have completed any test and digital badge requests prior to this date. The course materials will still be available.**

### Video Overview

{{< youtube ZwomDsloyHg >}}

### Enroll for this course

You must first be a member of the community before you can enroll for this course. Ensure that you have fully completed the community member enrollment process before proceeding.

To enroll for this course, follow the detailed instructions below to post a simple file with your github username to this repository. This process, while simple to follow, helps participants to gain experience and comfort, and validate their knowledge with foundational devops tools and process.

Posting a file to enroll uses the git pull request process, which is one of the most important and common foundational skills for participating in devops, cloud native, and infrastructure modernization initiatives. 

This process will also show on your public github profile that you have made a commit, the course also provides several additional exercises throughout where you will make commits to gain additional git experience while enhancing your github and professional profiles. 


#### Step 1 - Open the new course enrollment document link

**The Course Enrollment Process Requires that you have a github account, and that you are signed in using the github account you want to be enrolled for the course. If you attempt to enroll a different account than the account you are signed in as, the process will fail.**

Please right click the following link and select the option to open it in a new browser tab, so you can keep this instruction page open in the current tab to guide you through the process. 

[Right Click Here and select the option to open link in new tab](https://github.com/ModernAppsNinja/modernappsskills101_ms4043/tree/main/static/admin/userdata/registered_members) and click on `Add File > Create new file`

#### Step 2 - Name your file

Note the page displays a message that `You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork YOUR_GITHUB_USERNAME/COURSE_REPOSITORY_NAME, so you can send a pull request.`

The pull request process works by submitting a copy of your new or updated file to the repository, which will only be applied to the course repository if a course administrator approves the request. Because you do not have write access to the repository, github will create a special copy called a `fork` of the course repository within your github account with your new or updated files, and use your copy to save the updates you're submitting to the official course repository as shown in the following steps.

In your browser tab to the new enrollment document, above the document editor in the file name field, type in the name of the file in the format `your_github_username.yml`, replacing the value **your_github_username** with the username for your github account. 

The following screenshot shows an example of this step using the github username `Oni-no-Hanzo`

**Note:** If needed, you can verify your github username by clicking on your github profile menu, which can be found on the upper right hand corner on any github page if you are signed in.

![Screenshot of File Naming](https://modernapps.ninja/course_repo_template_ct8279/admin/assets/images/course_registration_file_naming.png)

#### Step 3 - Add a line to your file

On line 1 in the document editor, type `status: in-progress` as shown in the following screenshot:

![Screenshot of File Editing](https://modernapps.ninja/course_repo_template_ct8279/admin/assets/images/course_registration_file_editing.png)

#### Step 4 - Submit your enrollment document

Scroll to the bottom of the enrollment document page and click `Propose New File` as shown in the following image:

![Propose New File Screenshot](https://github.com/ModernAppsNinja/course_repo_template_ct8279/blob/main/static/admin/assets/images/propose_changes.png)

After you click `Propose New File`, your browser will be redirected to the `Comparing Changes` page with all the configuration all setup so all you sould need to do is click `Create Pull Request` --- but before you click, please review the other details shown on the comparing changes and observe that the file you created and the lines added are shown, so you can easily review and verify your proposed changes before submitting.

After you click `Create pull request`, an automated GitHub Action worklow will initiate that will do the following actions:
- verify that your github account is a member of the modernappsninja organization
- verify the filename of the submitted document matches the github username of the logged-in user that submitted the pull request
- if the above items are successfully validated:
  - add the course record page to the members profile repository to display course progress and completion records
  - add a message to the pull request ticket with the URL for the members course record page
  - trigger github to send an email from github to the email address for the github user account that submitted the pull request including the message from the previous step
  - approve and merge the new document you submitted into the registered members directory for this course

This completes the course enrollment process, once you have completed the above steps, you can proceed through the course and participate in any steps such as tests and completion certificates that require course enrollment. 

Thank you!
