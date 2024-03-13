# Interactive Account Linking

[Demo](https://zoom.us/clips/share/CwcvxH7dFgvtfWSHNOxcVMz5h0AHxTSx1s8bNbOaKPBL7pKa_zt__DFQv-cBEJycy6ziBaWHjD2ynWsHZ3WKinYf.dquuHh5vH8Jnuznf)
![interactive account linking seq](./interactive-account-linking.png)

# Interactive Account Linking with Confirmation Screen

This Auth0 Action provides a seamless way for users to link their accounts while ensuring proper confirmation through a user-friendly interface.

## Purpose
Account linking is essential for services that allow users to sign in using multiple identity providers. This Action streamlines the process by guiding users through the account linking process and confirming their actions with a clear confirmation screen.

## How It Works
1. **Trigger**: This Action is triggered when a user attempts to link their account.
2. **Confirmation Screen**: After the user initiates the linking process, they are presented with a confirmation screen detailing the action they are about to take.
3. **User Interaction**: The user can review the information presented on the confirmation screen and proceed with the account linking or cancel the operation.
4. **Account Linking**: If the user confirms the action, the accounts are linked as requested. If the user cancels, the process halts, and no changes are made.

## Prerequisites
- [Auth0 Page Templates](https://auth0.com/docs/universal-login/page-templates): Ensure you have the necessary [templates](/.interactive-account-linking-page-template.html) configured in your Auth0 Dashboard to customize the confirmation screen as per your requirements. 
- Have a Custom Domain Configured

## Installation
1. **Copy Action Code**: Copy the provided JavaScript code for this Action.
2. **Paste into Auth0 Dashboard**: Create a new Post Login Action and paste the code
3. **Create Secrets and Import NPM Packages**: Make sure to follow the instructions inside the action to create NPM Packages and needed Actions Secrets
4. **Save Changes**: Save the changes made to the Action.
5. **Configure Triggers**: Add the action to the Post Login flow

## Configuration
- Ensure that you have configured the necessary Page Templates in your Auth0 Dashboard, particularly for the confirmation screen, to provide a seamless user experience.
- Customize any messages or UI elements within the provided JavaScript code to match your application's branding and user expectations.

## Usage
1. When a user attempts to link their account, the Action will be triggered.
2. The user will be presented with a confirmation screen detailing the account linking action.
3. After reviewing the information, the user can proceed with the account linking or cancel the operation as desired.
4. Upon confirmation, the accounts will be linked accordingly. If canceled, no changes will be made.


# Silent Account Linking
TBA
