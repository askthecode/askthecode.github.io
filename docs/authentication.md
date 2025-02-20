---
label: "Authentication"
icon: key
order: 900
---

# Authentication in AskTheCode Plugin

To ensure a seamless experience with the AskTheCode plugin, users are required to authenticate.

### Authentication Methods

1. **Passwordless Login via Email**

This method allows users to quickly start exploring the features of the AskTheCode plugin without the need for a password. It's a hassle-free way to get started, especially for those who are new to the plugin and want to explore its capabilities. However, this method is recommended for exploration purposes only.

2. **GitHub OAuth Authentication**

Authenticating with your GitHub account unlocks additional features, such as the ability to ask questions about private repositories. For an enhanced experience and to take full advantage of the plugin's capabilities, we recommend using the GitHub OAuth method.

### Managing Your Account and Subscription

[!embed](/resources/authentication/manage-subscription.mp4)

To manage your account, subscription plan, view your quota or cancel subscription:

1. Visit the [Account Management Page](https://c7d59216ee8ec59bda5e51ffc17a994d.auth.portal-pluginlab.ai/pricing).
2. Here, you can view your current quota and available subscription plans.
3. To manage your current subscription, click on the **Manage subscription** icon located at the top-right corner of the page.

### Changing the Authentication Method

To change the authentication method, you indeed need to reinstall the plugin. When you install it, it will ask you to log in and will show you the authentication page:

![](/resources/authentication/auth-page.png)

On this page, you can press the "Change account" link, and you'll be redirected to the main Login page. It's important to note that GitHub caches the account you have previously used, so you might need to clear cookies for the github.com domain to see the prompt again.

### Troubleshooting

#### Couldn't Log in with Plugin

If you encounter an issue where you're unable to log in using the plugin, it might be related to a known OpenAI issue experienced by some users who use a non-English language in their browser.

To resolve this issue:

1. Change the browser language to English.
2. If the browser translation feature is turned on and set to a language other than English, change it to English as well.

#### Unable to Retrieve Data from Private Repository

If you encounter an error when trying to retrieve data from your private repository, the issue might be related to the following error message:

> Although you appear to have the correct authorization credentials, the `<YOUR ORGANIZATION NAME HERE>` organization has enabled OAuth App access restrictions, meaning that data access to third-parties is limited. For more information on these restrictions, including how to enable this app, visit [here](https://docs.github.com/articles/restricting-access-to-your-organization-s-data/).

To resolve this issue, ensure that you have approved the AskTheCode OAuth app within your organization. To see how to approve the app, consult the [Approving OAuth apps for your organization](https://docs.github.com/en/organizations/managing-oauth-access-to-your-organizations-data/approving-oauth-apps-for-your-organization) documentation.

#### Subscription Quota Not Applied

If you encounter an error when after purchasing a subscription, the new quota may not immediately reflect in your account, leaving you unable to access the increased limits, you should follow the next steps:

1. **Log Out and Log Back In:** The first step is to ensure that your account recognizes the new subscription status. Please log out of your account and then log back in. This action refreshes your session and applies any pending updates to your account.

   1. To log out of your account, navigate to the account settings and select the "Log Out" option. To log out of the account, pelase follow the steps from the video: [!embed](/resources/authentication/sign-out.mp4)
   2. Log back in by entering the email or GitHub account details associated with the subscription purchase.

2. **Use the Correct Account:** It's crucial to log back in using the same account that was used to purchase the subscription. Logging in with a different account will not reflect the subscription benefits.

By following these steps, you should be able to resolve issues related to the subscription quota not being immediately applied to your account. If the problem persists, please contact our support team for further assistance.
