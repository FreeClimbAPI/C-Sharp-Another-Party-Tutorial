# C# - Connect Caller To Another Party

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/connect-a-caller-to-another-party-1#section-c). Specifically, the project will:

- Create a conference
- Make an outbound call during the phone call
- Add the caller to the conference

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk --version 1.0.0.1
   ```

2. Configure environment variables

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                               |
   | HOST | The url of where your app is being hosted (e.g. yourHostedApp.com)

3. Add the phone number you would like to connect to in the `lookupAgentPhoneNumber` method.

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ dotnet run
   ```
