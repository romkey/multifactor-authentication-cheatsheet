# Multifactor Authentication Cheatsheet

Multifactor authentication dramatically improves personal security
over simple single factor authentication by requiring addiitonal
identification beyond just a password.

Have too many accounts? Prioritize them: financial accounts, social
media and publishing accounts and 

## Second Factors

Common second factors include:

### SMS

The system transmits a several digit code via SMS which you then type
into a web page or app.

This approach is also cumbersome and can easily leave you hamstrung if
you don't have access to your phone (battery dead, traveling somewhere
without service, etc).

Further, SMS has been shown to be insecure - phone numbers can be
spoofed 


### Personal Security Questions

Personal security questions are bullshit. They make services less
secure, not more secure. Avoid them whenever possible. When not
possible, treat them as like passwords - generate strong passwords and
add reminders to a password manager. Never give truthful answers to
questions like your mother's maiden name or your birth place unless
you're filling in a financial application.

### App Generated Code

Stronger than SMS, you download an application like [Authy](https://www.authy.com/) or [Google
Authenticator](https://support.google.com/accounts/answer/1066447?hl=en). When you need the second factor, start the app and copy
the code it shows you. You'll a brief window of time when the code is valid.

This approach is subject to a simple man-in-the-middle attack - if you
visit a malicious site or use a malicious app which records your
credentials, it can ask you for the second factor and then simply
supply the answer you gave it for immediate account access.

Otherwise, this approach is as secure as the device which runs the authenticator app.

Code-based authenticator apps do not require a live internet
connection for the app.

### App Notification




## The List

### Amazon

Amazon can send a code via SMS or use an app generated code as its
second factor.

You can find instructions [here](https://www.amazon.com/gp/help/customer/display.html?nodeId=201962420).

### Apple

Apple offers "Two-step authentication" which sends an SMS or iMessage
with a code. You should use Apple's Two-step authentication if you
only have one Apple device or if you're running iOS 8 or earlier or OS
X 10.10 ("Yosemite") or earlier.

They also offer more secure "Two-factor authentication, which sends a
notification to your other Apple devices. Your other Apple devices
then display a map indicating where the requester is located and a
button to allow authentication to proceed. You may be given a code to
enter into the device being authenticated.

Your Apple devices will have to be connected to the
Internet for Two-factor authentication to work.

Apple offers backup codes which you should store in a seure location.

You can find instructions for Two-step authentication
[here](https://support.apple.com/kb/HT5570).

You can find instructions for Two-factor authentication
[here](https://support.apple.com/en-us/HT204915).

Definitely use Two-factor authentication if you can (if you have more
than one Apple device).

### Dropbox

Dropbox can use SMS or an app for the second factor. It offers backup
codes which you should store in a secure location.

You can find instructions [here](https://www.dropbox.com/help/363/en).

### Google

Google can use SMS or an app for the second factor.

You can find instructions [here]().

If you use G Suite (formerly Google Apps) for your domain, you may
need to allow users to turn on second-factor first. You can find
instructions [here](https://support.google.com/a/answer/184711).

### Twitter

Twitter sends a code via SMS as its second factor.

You can find instructions [here](https://support.twitter.com/articles/20170388).

### Wordpress

Wordpress supports multifactor authentication via plugins.

You might try:

- [Google Authenticator](https://wordpress.org/plugins/google-authenticator/)
- [Authy Two Factor Authentication](https://wordpress.org/plugins/authy-two-factor-authentication/)

### World of Warcraft

World of Warcraft supports second factor via their "Battlenet"
app. They reward players for using the authenticator with a special
pet (the Core Hound Pup), which is only available when an
authenticator is actively attached to the player's account.

You can find instructions [here](https://us.battle.net/support/en/article/100588).

####Sites That Don't Support Multifactor Authentication

Adobe

