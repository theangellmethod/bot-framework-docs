## Next steps
After you have deployed your bot to the cloud and verified that the deployment was successful by testing the bot using the Bot Framework Emulator,
the next step in the bot publication process will depend upon whether or not you've already registered your bot with the Bot Framework.

### If you have already registered your bot with the Bot Framework:

1. Return to the <a href="https://dev.botframework.com" target="_blank">Bot Framework Portal</a> and [update your bot's registration data](~/portal-register-bot.md#maintain) to specify the **HTTPS** endpoint for the bot.

2. [Configure the bot to run on one or more channels](~/portal-configure-channels.md).

### If you have not yet registered your bot with the Bot Framework:

1. [Register your bot with the Bot Framework](~/portal-register-bot.md).

2. [Update the Microsoft App Id and Microsoft App Password values](~/portal-register-bot.md#updateConfigSettings) in your deployed application's configuration settings to specify the **app ID** and **password** values that were generated for your bot during the registration process.

3. [Configure the bot to run on one or more channels](~/portal-configure-channels.md).