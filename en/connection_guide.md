---
title: "How to connect to Akatsuki"
old_id: 1
---
- [Register](https://akatsuki.pw/index.php?p=3) an account
- Download the [Akatsuki server switcher](https://akatsuki.pw/static/switcher.zip)
- Move all files from switcher.zip <b>into a single folder</b>.
- Open `switcher.exe`. A prompt should appear asking if you'd like to install our certificate, click Yes.
- Click **Switch to Akatsuki**. (You can now close the switcher)
- Open [This page](https://c.ppy.sh), it should look like [This](https://akatsuki.pw/static/successful_c_page.png).
- Restart osu! and login with your newly created Akatsuki account.
- Enjoy!

## Troubleshooting
If you have any errors, open the **Inspect** tab of the switcher.

The important part of this tab is the Hosts file tab. If you had an error when
switching to Akatsuki, most likely it will say your hosts file is not writable.

This is generally caused by antivirus programs; the switcher edits a system file at
`C:\Windows\System32\drivers\etc` called `hosts`; this allows us to redirect traffic
from *.ppy.sh to *.akatsuki.pw (so you can connect to the server), however many adware
programs also use the hosts file to redirect traffic to their less-than-reputable
sites, so it it somewhat understandable that antivirus programs are careful.

Please diable your antivirus/firewall and try again.
If issues persist, please consider joining our [Discord](https://akatsuki.pw/discord)'s #help channel, or check out our [FAQ](https://akatsuki.pw/doc/5).

### How to play on Akatsuki
- Make sure you have [Microsoft Visual C++ Redistributable for Visual Studio 2019](https://aka.ms/vs/16/release/vc_redist.x64.exe) installed!
- Run `switcher.exe`
- Click on **Click to Activate**
- Make sure that the switcher says **Switch was successful! Please make sure to restart your client.**
- Open osu! and login with your Akatsuki account
- Enjoy

## Switching back to osu!
To switch back to the official osu! servers, simply open the switcher and click **Switch to osu!**.
**NOTE**: You may find that your browser begins redirecting all osu! pages to Akatsuki.
Don't worry as this is normal - your browser 'caches' data so that it can repeat requests
it has already done more efficiently. Some people are simply able to restart their browser,
although more often than not you'll have to manually clear your browser's cache (5 second job).
Simply hit Ctrl + H, click on "clear browsing data", and select "Cookies and other site data".
You only need to select the time range your PC was switched to Akatsuki. Once that's been cleared,
a simple browser restart should fix it.
