# Twoku (for Roku)
An Improvable™ Twitch app for Roku. Still a little buggy, so feel free to suggest improvements (and code and features).

## Discord
https://discord.gg/kV5SXkZ

## Support
If you would like to support Twoku:

 [![Support with PayPal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=YRPQDG5UY26DS&currency_code=CAD&source=url)

## Contributing
If you have an idea (feature, etc.) that you would like to contribute (with code) to the project with, DM one of the developers on the Discord with your idea. Otherwise, if you just have an idea, post it in the ```#features``` channel on the Discord server.

## How to Install
<em>Note: the GitHub version is currently outdated because of some security concerns (use the access code for the updated version). If you are in Mexico or Brazil the access code version might not work due to Roku's region restrictions. Instead, try to install the app manually. </em>
### With Access Code
Install with access code: TWOKU (https://my.roku.com/account/add?channel=TWOKU)

Beta version: TTWOKU (https://my.roku.com/account/add?channel=TTWOKU)

### Manual Developer Install
1. [Enable developer mode for Roku](https://blog.roku.com/developer/developer-setup-guide)
2. Log into your Roku from your browser using IP from previous step (http://192.168.x.x)
3. Get your own Twitch client ID from https://dev.twitch.tv/
4. Get your own App access token (https://dev.twitch.tv/docs/authentication/getting-tokens-oauth#oauth-client-credentials-flow)
5. Put your client ID (step 3) right after (no spaces) ```CLIENT-ID=``` and put your App access token (step 4) right after (no spaces) ```AUTHORIZATION=``` in the ```env``` file. <em>Note: due to some unresolved whitespace issues, this step may not be correctly done</em>
6. ZIP (into a ZIP file) all contents of this repo (you do not have to include README.md) (using 7-Zip, WinRAR, etc.)
7. Upload previous ZIP file in Roku Development Application Installer (step 2)
8. Press Install
9. Twoku should now be installed on your Roku

## Supported Features
<em>Note: some features are not on the GitHub version</em>
* Browsing live channels and categories by viewer count (press down to load more)
* Search (with buggy auto-complete) (Press * on remote to load Search menu)
* Viewing followed live streamers
* Viewing popular clips from the past 7 days for each category
* Chat
* VODs (except subscriber-only)

## Notable Unsupported Features
* All clip functionality not mentioned
* Everything else not mentioned

## Screenshots
![Image of categories](https://i.imgur.com/M6nS93X.jpg)

![Image of live channels](https://i.imgur.com/mFmkztf.jpg)

![Image of selected category](https://i.imgur.com/ulzJFuK.jpg)

![Image of search](https://i.imgur.com/EMXEfUE.jpg)
