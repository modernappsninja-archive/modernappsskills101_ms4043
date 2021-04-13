---
title: "Community Membership and Course Registration"
date: 2020-10-12T18:34:25-07:00
weight: 1013

---

- [Requirements for tests and course completion certificates](#requirements-for-tests-and-course-completion-certificates)
  - [Join the ModernApps Ninja Community!](#join-the-modernapps-ninja-community)
  - [Register for this course](#register-for-this-course)
    - [Step 1 - Open the new course registration document link](#step-1---open-the-new-course-registration-document-link)
    - [Step 2 - Name your .yml file](#step-2---name-your-file)
    - [Step 3 - Add a line to your .yml file](#step-3---add-a-line-to-your-file)
    - [Step 4 - Submit your .yml registration document](#step-4---submit-your-registration-document)


{{< youtube Ad4ObhsOaJk >}}

## Requirements for tests and course completion certificates

ModernApps Ninja learning content is free and open to anyone to view, however to take tests and receive certificates of completion for courses, you must sign up for a free community membership, **and** register for this course, per the instructions below. 

### Join the ModernApps Ninja Community!

In addition to unlocking the ability to take tests and recieve course completion certificates, joining the ModernApps Ninja Community has a number of other benefits, and is a completely free program. 

[Please click here to learn more about member benefits and to join the community!](https://modernapps.ninja/about/membership)

### Register for this course

You must first be a member of the community before you can register for this course. Ensure that you have fully completed the community member registration process before proceeding.

To register for this course, follow the detailed instructions below to post a simple file with your github username to this repository. This process, while simple to follow, helps participants to gain experience and comfort, and validate their knowledge with foundational devops tools and process.

Posting a file to register uses the git pull request process, which is one of the most important and common foundational skills for participating in devops, cloud native, and infrastructure modernization initiatives. 

This process will also show on your public github profile that you have made a commit, the course also provides several additional exercises throughout where you will make commits to gain additional git experience while enhancing your github and professional profiles. 

#### Step 1 - Open the new course registration document link

**The Course Registration Process Requires that you have a github account, and that you are signed in using the github account you want to be registered for the course. If you attempt to register a different account than the account you are signed in as, the process will fail.**

The following link will direct your browser to a github web-based document editor that is used to submit new files or updates to this github repository. You will need to type in a few values and then submit the document as detailed in the following steps.

Please right click the following link and select the option to open it in a new browser tab, so you can keep this instruction page open in the current tab to guide you through the process. 

[Right Click Here and select the option to open link in new tab](https://github.com/ModernAppsNinja/vSphereTanzu301_vt4163/tree/main/static/admin/userdata/registered_members) and click on `Add File > Create new file`

#### Step 2 - Name your .yml file

Note the page displays a message that `You’re making changes in a project you don’t have write access to. Submitting a change will write it to a new branch in your fork YOUR_GITHUB_USERNAME/COURSE_REPOSITORY_NAME, so you can send a pull request.`

The pull request process works by submitting a copy of your new or updated file to the repository, which will only be applied to the course repository if a course administrator approves the request. Because you do not have write access to the repository, github will create a special copy called a `fork` of the course repository within your github account with your new or updated files, and use your copy to save the updates you're submitting to the official course repository as shown in the following steps.

In your browser tab to the new registration document, above the document editor in the file name field, type in the name of the file in the format `your_github_username.yml`, replacing the value **your_github_username** with the username for your github account. And don't forget the **.yml** extension.

The following screenshot shows an example of this step using the github username `Oni-no-Hanzo`

**Note:** If needed, you can verify your github username by clicking on your github profile menu, which can be found on the upper right hand corner on any github page if you are signed in.

![Screenshot of File Naming](https://modernapps.ninja/course_repo_template_ct8279/admin/assets/images/course_registration_file_naming.png)

#### Step 3 - Add a line to your .yml file

On line 1 in the document editor, type `status: in-progress` as shown in the following screenshot:

![Screenshot of File Editing](https://modernapps.ninja/course_repo_template_ct8279/admin/assets/images/course_registration_file_editing.png)

#### Step 4 - Submit your .yml registration document

Scroll to the bottom of the registration document page and click `Propose New File` as shown in the following image:

![Propose New File Screenshot](https://github.com/ModernAppsNinja/course_repo_template_ct8279/new/main/static/admin/userdata/registered_members)

After you click `Propose New File`, your browser will be redirected to the `Comparing Changes` page with all the configuration all setup so all you sould need to do is click `Create Pull Request` --- but before you click, please review the other details shown on the comparing changes and observe that the file you created and the lines added are shown, so you can easily review and verify your proposed changes before submitting.

After you click `Create pull request`, an automated GitHub Action worklow will initiate that will do the following actions:
- verify that your github account is a member of the modernappsninja organization
- verify the filename of the submitted document matches the github username of the logged-in user that submitted the pull request
- if the above items are successfully validated:
  - add the course record page to the members profile repository to display course progress and completion records
  - add a message to the pull request ticket with the URL for the members course record page
  - trigger github to send an email from github to the email address for the github user account that submitted the pull request including the message from the previous step
  - approve and merge the new document you submitted into the registered members directory for this course

This completes the course registration process, once you have completed the above steps, you can proceed through the course and participate in any steps such as tests and completion certificates that require course registration. 

Thank you!
