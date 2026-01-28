# How to Create an API Key on BingX

## Step 1: Log in to Your BingX Account
Go to the official BingX website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu under the "More" section.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bingx/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **Create API**.

![Create API Button](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bingx/assets/screenshots/Screenshot%202.png)

2. Enter a **Label the API Key** (e.g., "MM Bot", "Liquidity Bot", or project name).
3. Add an **IP Address Whitelist** and include the IPs provided by the ICG Trading team (**separate each IP using a comma without spaces**).
4. Set **API Permissions**
Choose the following permissions based on your use case:
- Read
- Spot Trading

![Create API Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bingx/assets/screenshots/Screenshot%203.png)

> **Important:** Do **NOT** enable withdrawals for security reasons.

## Step 4: Security Verification
Complete the required security checks:
- Email Verification
- Google Authenticator (2FA)

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bingx/assets/screenshots/Screenshot%204.png)

## Step 5: Save API Credentials
After creation, BingX will display:
- API Key
- Secret Key

![API Key Created](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bingx/assets/screenshots/Screenshot%205.png)

> **Warning:** The Secret Key only shows once and will be hidden after refreshing or closing the page. Store it securely.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
