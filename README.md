# cad-integration
Integrates a cad system.

Insert link of your cad in the ""


Installing Discord Roles
Download and extract Discord Roles into your resources folder. The resource name must be discordroles.

Now open a command terminal and navigate to the resource foler. Use the CD command to do this.

Once navigated used the below command and press enter. This will install the required modules for the resource to run.

npm install
If this doesn’t work make sure Node.Js and NPM are installed on your machine.

Create a new application from the Discord Developer Portal.

Click on ‘Bot’ on the left navigation bar and enable the bot. Then copy the Bot Token and place into the config.js file along with your guild ID.

Now in the ‘General Information’ tab copy the ‘Client ID’ and replace CLIENT_ID_HERE in the below template.

https://discord.com/oauth2/authorize?client_id=CLIENT_ID_HERE&scope=bot&permissions=8
Invite the bot into your guild.

Add ensure discordroles to your server.cfg file.
Installing Discord Whitelist
Download and extract Discord Whitelist into your resources folder.

Open the server.js file in the resource and edit to include the settings you want reflected.

Add ensure DiscordWhitelist into your server.cfg.


Made by discord.gg/9Tpb7cc
