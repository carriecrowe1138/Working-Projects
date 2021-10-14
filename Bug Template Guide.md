# Bug Template Guide

  The Good Docs project aims to help open source projects be more effective by
helping them lift the quality of their documentation. We do this by creating
processes, templates, and guides covering the numerous aspects of writing good
documentation. Every project deserves a minimum level of Good Docs, but it can
be really hard to know where to start or what to write.

Bug reporting demonstrates an issue and supplies developers valuable information
to find the solution. You may be tempted to write a lengthy, twenty page report
on what you discover, but we’ve found that the simpler and more concise your
bug report is, the better your team and your project will be in the long run.
Our Bug Template consists of eight  key fields that when filled out correctly
 and completed, will result in the ideal bug report.

 Let’s discuss these fields while providing good (ideal),
 bad (needs improvement) and ugly (meaning what absolutely not to do)
 examples of each one.

 1. Title
 2. Environment
 3. Steps to Reproduce
 4. Expected Result
 5. Actual Result
 6. Visual Proof
 7. Priority
 8. Severity

## Title
A title should be a short and specific description of the issue. It is likely
you’ll want to return to the title after completing the full bug report to ensure
the title is concise and reflective of the problem.

| Quality      | Example |
| ----------- | ----------- |
| Good    | Returning to App after being backgrounded causes App to crash. Error 5412.     |
| Bad   |  Application crashes when I load it.        |
| Ugly      | App is broken. Please fix ASAP. Help!  |

## Environment
As technology continues to change and progress, so do our options for interacting
with software and the web. This means we need to be very specific about our
environment or what we’re using, this usually includes operating systems,
browser configurations and connectivity rates. Without the exact platform or
environment, the application may behave differently and the bug at the
tester/user end may not replicate on the developer’s end.
So, it is best to list the environment in which the bug was detected.

| Quality      |Example  |
| ---------| ----------- |
| Good     | iPhone  / iOS 9 / Safari 14       |
| Bad    | iPhone        |
| Ugly     | My Phone  |

## Steps to Reproduce
Providing a step-by-step process of what you did to find the bug gives direction
to your users and/or developers. Each step should be a specific and separate action.
If you’re doing it correctly, your reader should be able to easily navigate through
your software. A good practice here is to go through the steps you wrote,
line by line, making sure every detail is written out. This gives you the chance
to fine tune and add anything you may have forgotten the first time around,
leaving no room for confusion.

| Quality      | Example |
| ----------- | ----------- |
| Good      | Open and Log in "myorganization" APP on Iphone 12. Log-In using "myorganization"@software.com and "myorganization" password. Click "Submit". Click the Home button to minimize "myorganization" APP. Open "Clock" APP. Click the "Home" button to minimize "Clock" APP. To see all your open apps in the App Switcher, Double click the "Home" button. Select the "myorganization" app in the App Switcher.    |
| Bad   |     Open and Log-In App then minimize, open separate app then reopen first app.
| Ugly   |    Open App while already running multiple Apps.


## Expected Behavior
It is necessary to understand and outline what the user should expect.
What were you expecting to happen after your last step?
Again, be as clear as impossible with your description.

| Quality      |Example  |
| ---------| ----------- |
| Good     | The app should return from being backgrounded seamlessly -after being selected in the  App Switcher - continuing  to run properly, meeting all requirements outlined from criteria 3.2b.      |
| Bad    |  App doesn’t crash or abruptly end after returning from being backgrounded.        |
| Ugly     | App doesn’t crash.  |

## Actual Result

Here’s the result of the bug. Does the application crash? Does nothing happen at all?
Is an error displayed? In our experience, testers can be a little vague in this department, so encourage them to be as distinct as possible and provide some information on isolation to make the bug report more actionable – “Button does not work as expected” isn’t helpful, whereas “Button closes app across different platforms, different os versions, or different screen sizes” gives developers a much better feel for the problem. It also provides them with additional details to help start their investigation. What actually happened? Did you receive any error messages?

| Quality      | Example |
| ----------- | ----------- |
| Good      | A “654321 Update Error” popup message appears and the application closes.       |
| Bad   | An error pops up and crashes the application.
  Ugly        |	It crashes.

## Visual Proof
Proof or Evidence is any valuable video, screenshot, or log files that shows the issue
and is helpful in reproducing it.

| Quality      | Example |
| ----------- | ----------- |
| Good      | Videos or Screenshots of the instance of failure with proper captioning to highlight the bug. Error messages are highlighted.        |
| Bad   | The instance of failure is captured and highlighted. No captioning is provided.        |
  Ugly |  Screenshots or Videos don’t feature the instance of failure or bug.

## Priority
Priority defines how soon the bug should be fixed. Usually, the priority of the
bug is set by the Managers or Project Leads. Based on the priority, developers
could decide how soon it must be fixed and set the order in which a bug should be
resolved.

#### Categories of Priority

* High
* Medium
* Low

## Severity
Severity talks about the Impact of the bug on the customer’s business.
Usually the severity is set by the Managers or Project Leads.
Sometimes testers will choose severity but in most cases, it will be chosen by
Project Leads.

#### Categories of Severity

* Blocker
* Critical
* Major
* Minor
* Trivial

By combining those eight key components, The Good Docs Project has created a bug
template that when completed correctly results in a short, specific and accurate
bug report to ensure effective communication and time management by isolating
the bug/incident and providing enough information for a clear description of
the problem which in turn will lead to a faster solution.

## Summary:
* The bug report title needs to summarize the reported issue.
* Provide accurate details of the environment.
* Provide a clear description of what the reported issue is.
* Provide steps that will easily allow the bug to be reproduced.
* Take note of what the expected behavior should be.
*Attach all relevant files – screenshots, screencasts, logs, etc.
* Work with your team to assign the correct priority and severity.
