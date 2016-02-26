# Netflix Auto login for Chrome


Usage:

```
git clone https://github.com/Cjones90/Netflix-Autologin.git flix
```

Navigate to the `flix` folder and enter your Netflix credentials into login.js.

Go to chrome://extensions and click Developer Mode at the top.

Click `Load unpacked extenson...`.

Navigate to the `flix` folder you cloned the project into and select it.

Done


Now whenever you navigate to

`https://www.netflix.com/Login?locale=en-US`  
or  
`https://www.netflix.com/Login`


in a few short seconds you'll navigate to the show selection screen.

* The folder must stay put for the extension to work, so pick a good permanent place for it.
 * You can always move and reload it though.



# TODO

Create a script for www.netflix.com to click the Sign In button as well.

# Background

Reason I made this was I was tired of, when coming home, always booting up the computer, waiting,
then opening up chrome, going to Netflix, entering my credentials, clicking my profile
_then_ selecting my show.

Now I use ConnectBot on my Samsung S2 and use the automation feature to:

SSH into my Pi  
From Pi, send a WOL signal to wake my computer  
Sleep 10 seconds  
Have Pi open chrome up to   `https://www.netflix.com/Login?locale=en-US`  
Then have my netflix auto login take over

All with 2 button pushes on my phone :)

# Note

I don't know the terms of use for including jquery.js directly in the repo, but it
of course belongs to the jQuery foundation and I have taken no part in editing its code base.
