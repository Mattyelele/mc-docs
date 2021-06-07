# How to add a resource pack to your Minecraft Server

Resouce Packs change the look of everything in Minecraft. You can change the Resource Pack whenever you want. In order to use a Resource Pack on a Minecraft server, it must first be hosted on a Website, so that each player who joins the Minecraft server can be prompted to download the Resource Pack. The Minecraft server itself cannot host the files.

One of the cheapest and easier ways to do this is to upload the Resource Pack to any kind of file sharing site that is provides public and direct file downloads.

Some examples of file sharing sites include:

- Dropbox
- Google Drive 
- One Drive
- iCloud

## Size Limit

The maximum file size for Resource Packs that can be automatically downloaded by Minecraft on versions before **1.15** is **50 megabytes**.

When 1.15 launched, they changed the Resource Pack to version 5, which increased the client-side downloading from 50 megabytes to **100 megabytes**.

## Uploading the Resource Pack

In this guide we will be using Dropbox as our file sharing platform of choice. Firstly you will need to find a texturepack of your choice, the pack can be found on an official website [CurseForge](https://www.curseforge.com/minecraft/texture-packs). Confirm that the Resource pack is the correct one for your Minecraft server; same verison and then you can Download the pack to a known location on your computer.

## Setting up Dropbox

1. Sign into the [Dropbox](https://www.dropbox.com/) Website.
2. On the Dropbox website, Click the "Upload Files" button located on right-hand side.
3. Navigate to your chosen Resource pack on your computer, select it and click "Open".
4. Wait for the file to upload, once it has finished click done.
5. Find you Resource pack in the Dropbox file list and press the share button.
6. Ensure that your link settings for the file are set to "Anyone with the link can see it", so it will be public.
7. Finally, copy the link your clipboard for later.

## Configuring the server

1. Log into your server.pro panel and select your minecraft server.
2. Stop the server and head over to "Files" on the left-hand side.
3. Locate `server.properties` on in the **Root** directory and open it.
4. Find `resource-pack=` and paste the link you copied from the Dropbox afterwards.
5. The public link that you copied from Dropbox must be changed from `https://www.dropbox.com/somestring…?dl=0 ` to `https://dl.dropboxusercontent.com/somestring…?dl=1` (You change the 0 to 1 at the end).
6. Remember to click "Save File" on the bottom of the page once you have done this.
7. Start your server again

## SHA-1

In some cases you are required to add SHA1 to your `server.properties`. In order to do this you just need to simply head over to: http://onlinemd5.com/. Upload your texture pack ZIP file an select `SHA1` and copy the response given in the input field. Then you can go over to your `server.properties` and add the SHA1 to `resource-pack-sha1=`.
