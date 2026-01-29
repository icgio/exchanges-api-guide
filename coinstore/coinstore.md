# How to Create an API Key on Coinstore

## Step 1: Log in to Your Coinstore Account
Go to the official Coinstore website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinstore/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **+ Create API Key**.

![Create API Key Button](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinstore/assets/screenshots/Screenshot%202.png)

2. Enter a **Remark Name** (e.g., "ICG-MM", "Liquidity Bot", or project name).
3. Add an **Bind IP Address (required)** and include the IPs provided by the ICG Trading team (**separate each IP using a comma without spaces**).
4. Set **API Permissions**
Choose the following permissions based on your use case:
- Read
- Trade
5. Click **Confirm** to proceed.

![API Configuration](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinstore/assets/screenshots/Screenshot%203.png)

> **Important:** Do **NOT** enable withdrawals for security reasons.


## Step 5: Security Verification
Complete the required security checks:
- Email verification code (sent to your registered email)
- Google Authenticator (2FA)

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinstore/assets/screenshots/Screenshot%204.png)

## Step 6: Save API Credentials
After creation, Coinstore will display:
- API Key
- Secret Key
- Bind IP Address
- Permission
- QR Code (for quick import)

![View API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinstore/assets/screenshots/Screenshot%205.png)

> **Warning:** The Secret Key is shown only once. Store it securely before clicking Confirm.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
