---
title: "Community Membership"
date: 2020-10-12T18:34:25-07:00
weight: 1015
draft: false
---

- [Video Overview](#video-overview)
- [About Community Membership](#about-community-membership)
- [How to Register](#how-to-register)
- [Link to Membership Registration Form](#link-to-membership-registration-form)

### Video Overview

{{< youtube CIRecX6M9Go >}}

### About Community Membership

The Free ModernApps Learning Community Membership unlocks access to many key community assets including:

- Membership in the ModernAppsNinja Github Organization and Members Github Team
- ModernApps Learning Mailer list emails about community events and key content updates
- Ability to take course tests and request certificates of completion
- Member Repository and Github Pages site to display Member Course Records, Completion Certificates and Achievements
- Access to member discussion boards
- Access to submit blogs, courses and course contents, access course template and other community resources for contributors
- Course Enrollment and particpation reflects github commits on Members github profile and listed as contributor on ModernAppsNinja Github Org
- Access to participatory gitops/devops learning events, hackathons and exercises where members can gain organizational permissions including collaborator and maintainer achievements

Please Note: We are currently making some changes to our backend course hosting, and some courses may require additional registration steps until we complete this transition. If a course requires any additional registration steps, instructions will be provided in the course materials. 

### How to Register

Note: You must have a Github account and be logged in to github to register. Regardless of what values you type into the form, the github account you are logged in as at the time you submit the registration form will be used, so please be sure you are logged in to github with the account you want to register with.  

We use gitops/devops tools for participatory actions in the program to help ensure participants are comfortable with these important new skills.  

To register you will fill out a simple form in a github issue ticket. Its important that you fill out the form as instructed, and not modify the form spacing or punctuation as that could interfere with the automated workflows that process your registration.  

Here is an example registration form:

```bash
preferredEmailAddress: ""  
firstName: ""  
lastName: ""  
twitterUsername: ""  
linkedinUsername: ""  
isVmwareEmployee: false  
vmwareEmailAddress: ""
```

As you can see in the form above, each field has an empty pair of quotation marks where you can fill in your registration data. For example if your first name is John, you would enter `firstName: "John"` only adding your name between the quotation marks, without changing the line in any other way.  

Please note that First and Last Name fields do not infer which is the family name, it infers the display order. For example if you enter first name as `Juan` and your last name as `Dew`, your member repository homepage would say `Welcome to the ModernApps Learning Member Page for Juan Dew`.  

You may notice the `isVmwareEmployee: false` line does not have quotation marks around the value `false` - because it is a boolean value, it does not require quotations. If you are a vmware employee, please change this value to `isVmwareEmployee: true`; otherwise leave the value as false and do not change this line.  

**Required Values:** `preferredEmailAddress`, `firstName`, `lastName`  

**Optional Values:** `twitterUsername`, `linkedinUsername`, `vmwareEmailAddress`

Here is an example registration form filled in with fake user values:

```bash
preferredEmailAddress: "janedoe@fakeaddress.com"  
firstName: "Jane"  
lastName: "Doe"  
twitterUsername: "janedoe"  
linkedinUsername: "janedoe"  
isVmwareEmployee: false  
vmwareEmailAddress: ""
```

After you have completed filling in the registration form, click the `Submit new issue` button and an automated workflow will commence that will trigger github to send an email invitation to join the ModernAppsNinja github org. This email will be sent from github to the email account associated with the registrants' github acount. 

You must accept the email invitation from GitHub to join the ModernAppsNinja github org. 

After you accept the Github invitation and join the organization, an automated workflow will commence that will build your member repository and github pages site. Once your site is ready, the workflow will post a message with the details of your new site on github mentioning you, which will trigger github to send you a notification to the email address associated with your github account. Your new member page will initially be blank, however as you register for courses and earn achievements, they will be posted to your member page. 

Please note that we are currently transitioning courses to a new backend system and some courses are still on the old system. Course records from the old system may not be immediately reflected on the member page, but we will ensure that all records from our previous system get transferred and reflected on your member page soon. 

### Link to Membership Registration Form

Before submitting your registration please note that ModernApps Learning is hosted on public Github Repositories, and the records of processing this information can be publicly accessed. All records of participation are reflected on our public github sites and repositories and may be visible to other members or the general public. Participation in ModernApps Learning does not require you to submit confidential information, and asks that you do not submit any information you desire to be kept secret, as all information and particiapation data on this site should be considered public information. 

**[Please click here to access the Membership Registration Form](https://github.com/ModernAppsNinja/modernappsninja.github.io/issues/new?assignees=modernappsninjabot&labels=newuserregistration&template=joinrequest.md&title=Request+to+Join+ModernApps+Ninja+Github+Org)**



--------