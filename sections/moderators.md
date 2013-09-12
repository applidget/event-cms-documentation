#Doc for moderators


## Administration console

Once invited by an admin, after defining your password, you will have access to the website backoffice at this address : [http://events-cms.apxpo.com/admin](http://events-cms.apxpo.com/admin).

![admin homepage](https://raw.github.com/applidget/event-cms-documentation/master/images/admin_homepage.png "admin homepage")

Click on "admin" form adminstration console of the corresponding event.


## Import and synchronize guests with the Mobicheckin platform

By clicking on "Guest module" in the sidebar menu, you will see the form below :

![guest module](https://raw.github.com/applidget/event-cms-documentation/master/images/guest_module_1.png)

Your *Mobicheckin auth token* can be found on the [mobicheckin API doc](https://app.mobicheckin.com/fr/api)
The field *Mobicheckin event* is the mobicheckin unique identifier of your event, it can be found in the URL of the Mobichechin administration console (please contact Applidget dev team for support)

After settings these parameters, click on the button "synchronize guests". A background process will import all guests from Mobicheckin.
After every changes on Mobichekin (new guests, deleted guests, etc.), re-synchronized Event CMS by clicking on the same button.
Details of the synchronization will be displayed on the same page, don't hesitate to hit the refresh button of your web browser.

![guest module sync](https://raw.github.com/applidget/event-cms-documentation/master/images/guest_module_2.png)

## Invit your guests for registration on your event's website

When your website is ready for the launch, click on "Send invitations". All your guests will receive an invitation email and have the possibility to create an account on your website.

Hit the refresh button of your web browser to refresh details about the invitations background process displayed on the same page.

