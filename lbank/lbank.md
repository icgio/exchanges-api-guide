# How to Create an API Key on LBank

## Step 1: Log in to Your LBank Account
Go to the official LBank website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **My API** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/lbank/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **+ Create New API** (top-right corner).

![My API Page](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/lbank/assets/screenshots/Screenshot%202.png)

2. Enter an **API Name** (e.g., "MM Bot", "Liquidity Bot", or project name).
3. Select a **Verification method** (HmacSHA256 recommended).
4. Add an **IP whitelist** and include the IPs provided by the ICG Trading team (**separate each IP using a comma without spaces**).

![Create API Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/lbank/assets/screenshots/Screenshot%203.png)

## Step 4: Set API Permissions
Choose the following permissions based on your use case:

### Available Permissions
- Read only
- Trade

> **Important:** Do **NOT** enable withdrawals for security reasons.

## Step 5: Security Verification
Complete the required security checks:
- Email verification code
- Google Authenticator (2FA)

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/lbank/assets/screenshots/Screenshot%204.png)

## Step 6: Save API Credentials
After creation, LBank will display:
- API Name
- Verification method
- API Key
- Secret Key

![API Key Created](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/lbank/assets/screenshots/Screenshot%205.png)

> **Warning:** The Secret Key is shown only once and cannot be recovered. Store it securely. If you forget the Secret Key, delete the key pair and create a new one.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
