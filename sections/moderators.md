#Doc for moderators


## Administration console

Once invited by an admin and after defining your password, you will have access to the website backoffice at this address : [http://events-cms.apxpo.com/admin](http://events-cms.apxpo.com/admin).

![admin homepage](https://raw.github.com/applidget/event-cms-documentation/master/images/admin_homepage.png "admin homepage")

Click on the "Admin" button of the event you want to manage so you can go to its administration console.

## Guests

### Enable the guest module

By clicking on "Guest module" in the sidebar menu, you will see the form below :

![guest module](https://raw.github.com/applidget/event-cms-documentation/master/images/guest_module_1.png)

Your *Mobicheckin auth token* can be found on the [mobicheckin API doc](https://app.mobicheckin.com/fr/api)
The field *Mobicheckin event* is the mobicheckin unique identifier of your event, it can be found in the URL of the Mobicheckin administration console (please contact Applidget development team for support)

### Import and synchronize guests with the Mobicheckin platform 

After activating the guest module, click on the button "synchronize guests". A background process will import all guests from Mobicheckin.
After every changes on Mobichekin (new guests, deleted guests, etc.), re-synchronize Event CMS by clicking on the same button.
Details of the synchronization will be displayed on the same page, don't hesitate to hit the refresh button of your web browser.

![guest module sync](https://raw.github.com/applidget/event-cms-documentation/master/images/guest_module_2.png)

### Invite your guests for registration on your event's website

When your website is ready to be launched, click on "Send invitations". All your guests will receive an invitation email and have the possibility to create an account on your website.

Hit the refresh button of your web browser to refresh details about the invitations background process displayed on the same page.

## Live module

The live module includes these functionalities :
* Questions & Answers (Q&A)
* Polls
* Quizzes (coming soon)


### Enable Live Module

Click on 'Live Module' in the sidebar and on the 'Enable' button.

This module requires sessions (a session is a subset of an event : a room, an assembly, a conference, a meeting, …).
Create these sessions by clicking on 'Sessions' in the sidebar and add as many sessions as needed.
On the New Session form, just set the name for now, other fields will be explained below.
On the Live module page, click on the 'Moderate' button of a session, here you have the functionalities of the live module (listed above) in a menu. 

### Q&A

Q&A is a tool for guests to share a comment, ask a question related to the session. Doing so, the guests will be able to start a debate on the subject and answer to each other.
Q&A can be upvoted by guests :
* Upvoting a Question means that it would be interesting for the speaker to talk about it during the session
* Upvoting an Answer means that the guest agrees with it and wants to highlight it

You can also add a Question from the back-office : click on "Post a question/comment" and specify the content in the form.
After that, you will be able to publish/unpublish the Q&A so the Questions is available or not in the front-office.
When the Q&A is published, a direct link to the public page appears right next to the label.
Click on "Moderate", here you have all the answers given by the guests for this question, as well as the number of upvotes.



