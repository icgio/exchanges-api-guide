# How to Create an API Key on XT

## Step 1: Log in to Your XT Account
Go to the official XT website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/xt/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **Create API**.

![Create API Button](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/xt/assets/screenshots/Screenshot%202.png)

2. Enter an **Alias Name** (e.g., "MM Bot", "Liquidity Bot", or project name).
3. Add a **Whitelist IP** and include the IPs provided by the ICG Trading team (**separate each IP using a comma without spaces**).
4. Set API Permissions
Choose the following permissions based on your use case:

### Available Permissions
- Read
- Trade

![Create API Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/xt/assets/screenshots/Screenshot%203.png)

> **Important:** Do **NOT** enable withdrawals for security reasons.

## Step 4: Security Verification
Complete the required security checks:
- Google Authentication Code

## Step 5: Save API Credentials
After creation, XT will display:
- Public Key (AccessKey)
- Private Key (SecretKey)

![API Key Created](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/xt/assets/screenshots/Screenshot%204.png)

> **Warning:** The Private Key is shown only once. Store it securely. If forgotten, you must regenerate a new API key.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
