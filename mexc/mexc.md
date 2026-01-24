# How to Create an API Key on MEXC

## Step 1: Log in to Your MEXC Account
Go to the official MEXC website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/mexc/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click **Create API** and enter an **API Name / Label** (e.g., “MM Bot”, “Liquidity Bot”, or your project name).
2. Add the required **IP whitelist**, inserting all IPs provided by the ICG Trading team, **separated by commas with no spaces**.
3. Set the **API permissions** according to your use case. For Spot access, enable:
   - View Account Details
   - View Order Details
   - Trade
   - View Deposit/Withdrawal Details
   - Read Transfer Information

![Create API Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/mexc/assets/screenshots/Screenshot%202.png)

> **Important:** Do **NOT** enable withdrawals for security reasons.

## Step 5: Security Verification
Complete the required security checks:
- Email verification code
- Google Authenticator (2FA)

![API Permissions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/mexc/assets/screenshots/Screenshot%203.png)

## Step 6: Save API Credentials
After creation, MEXC will display:
- API Key
- Secret Key

![API Key Created](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/mexc/assets/screenshots/Screenshot%204.png)

> **Warning:** The Secret Key is shown only once. Store it securely.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
