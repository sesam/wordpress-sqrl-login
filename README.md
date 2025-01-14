# WordPress SQRL Login Plugin

SQRL can be used to log in to a site in a secure manner without giving away any personal information. This plugin enables that functionallity.

Instead of using a username, email and a password, SQRL uses an app to login to SQRL-aware websites.

When SQRL logs you into a website, your identity is a long code that looks like this: E6Qs2gX7W-Pwi9Y3KAmbkuYjLSWXCtKyBcymWloHAuo.

Your SQRL identity is a different long code for every website you login to, but it is always the same code when you return to a site you visited before. This means that websites never know who you are, but they do know when you return.

You may choose to remain anonymous to a website, such as when you post a response to someone's blog. SQRL never identifies you by anything other than that long code.

In other cases you will want to be known, like when you use SQRL to login as you at Amazon, Facebook, Netflix, or your bank. In those cases, you would inform Amazon that that particular code is actually you. SQRL lets you do that.

Special thanks to:

@davidshimjs (Sangmin, Shim) for writing a great javascript library for QRCode creation. (https://github.com/davidshimjs/qrcodejs)
@jaredatch (Jared Atchison) for writing a plugin for disabling users that I took inspiration from. (https://github.com/jaredatch/Disable-Users)


![Login screen](assets/screenshot-1.png)
![Profile screen without association](assets/screenshot-2.png)
![Profile screen with association](assets/screenshot-3.png)
