To install Google Drive, click the Plugins menu option on the left from your web Dashboard.  Then click the Catalog option up top on the right side.  Scroll down until you find.

![googledrive1.png](images/plugins/googledrive1.png)

You will be prompted to restart your Emby Server.  Please do this, then after restart navigate back to Plugins and you should see the plugin installed.

Click on the Google Drive image to bring up the popup menu

![googledrive1b.png](images/plugins/googledrive1b.png)

Choose the “Settings” option and you will be in the Google Drive Settings menu

![googledrive1c.png](images/plugins/googledrive1c.png)

Click the “Create a Google Drive Client Id and Secret” link.  You will then get a screen with instructions

![googledrive1d.png](images/plugins/googledrive1d.png)

Click the “Open Google Drive” link at the top which will open a NEW TAB.  Refer to the instructions above if needed.

![googledrive1e.png](images/plugins/googledrive1e.png)

Here we create a new project, select “Create a project” and then click the continue button.

![googledrive1f.png](images/plugins/googledrive1f.png)

Click the “Go to credentials” button above. You’ll be met with a wizard that trys to determine what type of credentials you’ll need.  Just ignore this and click the “Credentials” menu on the left.

Click the “OAuth consent screen” option in the middle

Type “Emby” for the application name

![googledrive1g.png](images/plugins/googledrive1g.png)

Scroll down to the bottom of the page and click the “Save” button.

You should now be at this screen.

![googledrive1h.png](images/plugins/googledrive1h.png)

Click the “Create credentials” button

Select the “OAuth client ID” option

![googledrive1i.png](images/plugins/googledrive1i.png)

Click “Create credentials

![googledrive1j.png](images/plugins/googledrive1j.png)

Select applicate type of “Other” and name this “Emby”.  Press the “Create” button.

You should now have your Client ID & client secret codes.

![googledrive1k.png](images/plugins/googledrive1k.png)

Copy these to notepad or other program for safe keeping.  You will need this again soon.
Now switch back to the Emby tab and click the “Close” button.

You can now paste the client ID and client secret codes into this dialog.

![googledrive1l.png](images/plugins/googledrive1l.png)

Click the save button to save your Client ID and Client Secret.

Now click the +Add button next to Google Drive Accounts

![googledrive1m.png](images/plugins/googledrive1m.png)

Type in “Emby” as the display name and click the “Grant Access” button.

You may then be prompted with a typical Google Login page.

Select your username and login if needed.  You should then be at this screen.

![googledrive1n.png](images/plugins/googledrive1n.png)

Click the “Allow” button.

![googledrive1o.png](images/plugins/googledrive1o.png)

Click the little box to the right to copy this auth code.

Switch tabs back to the Emby tab in your browser.

Paste the code into the code box

![googledrive1p.png](images/plugins/googledrive1p.png)

Click the “Save” button.

Congratulations, you have now setup Google Drive to work with Emby Cloud Sync!

























Cloud sync allows you to copy content to cloud storage accounts, for backup as well as archiving in multiple resolutions.

When content is archived in multiple resolutions, Emby apps will automatically choose the version that is most efficient for them. This will help relieve stress on your internet connection as well as your server's CPU. Apps will browse the content through your Emby Server as normal, but will stream from the cloud during playback.

## Installation

To install folder sync, open the **Emby Server Dashboard** and navigate to **Sync** -> **Services**. 

Click on Google Drive underneath **Available Services**.

![](images/plugins/googledrive1.png)

Then proceed to install it on the installation page.

## Configuration

To configure Google Drive, open the **Emby Server Dashboard** and navigate to **Sync** -> **Services**.  Click on Google Drive underneath **Installed Services**. 

Configuring Google Drive is a two step process. 

### Create a Client Id and Secret

First you'll need to create a client Id and Secret. To do this, click on the link titled "Create a Google Drive Client Id and Secret". Follow the instructions in the popup message.

### Add Google Drive Accounts

After you're configured the Client Id and Secret, you'll need to add one or more Google Drive accounts. To do this, click the + button next to Google Drive Accounts. You'll then be guided through the process of adding a Google Drive account.

## Ready to Sync

Once a Google Drive account has been added, it will then show as as an available destination when creating sync jobs:

![](images/plugins/foldersync3.png) 

## Playback

Once synced, Emby apps will automatically use the additional media sources when possible. For example, suppose you have a high bitrate movie that requires transcoding to Roku. By syncing to the cloud and selecting a conversion profile that is compatible with Roku, the Roku app can then direct play the synced version rather than transcoding the original.