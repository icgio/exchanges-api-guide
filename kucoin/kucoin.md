# How to Create an API Key on Bybit

## Step 1: Log in to Your Bybit Account
Go to the official Bybit website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/kucoin/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **Create New Key**.
2. Select **System-generated API Keys** as the API key type.

![Create New Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/kucoin/assets/screenshots/Screenshot%202.png)

## Step 4: Configure API Key Settings
1. Enter an **API Key Name** (e.g., "ICG-MM", "Liquidity Bot", or project name).
2. Under **API Key Permissions**, select **Read-Write**.
3. Under **IP Access Restriction**, choose **Restrict access to trusted IPs only (Recommended)** and enter the IPs provided by the ICG Trading team.

![API Key Configuration](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/kucoin/assets/screenshots/Screenshot%203.png)

## Step 5: Set API Permissions
Enable the following permissions based on your use case:

![API Permissions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/kucoin/assets/screenshots/Screenshot%204.png)

### Permissions to Enable:
| Permission | Description |
|------------|-------------|
| Spot Trading | Submit or cancel spot orders |

### Permissions to Leave Disabled:
- Derivatives — Trade
- Exchange — Subaccount Transfer
- Wallet — Account Transfer
- Wallet — Sub Member Transfer
- **Withdraw** (Never enable for security)

> **Important:** Do **NOT** enable withdrawal permissions for security reasons.

Click **Submit** to proceed.

## Step 6: Security Verification
Complete the required security checks:
- **Google Authenticator (2FA)** — Enter your TOTP code
- **Email verification code** — Enter the code sent to your registered email

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/kucoin/assets/screenshots/Screenshot%205.png)

## Step 7: Save API Credentials
After successful creation, Bybit will display your API credentials:
- **API Key** — Your public API identifier
- **Secret Key** — Your private secret key

> **Warning:** The Secret Key is shown only once. Click the **copy icon** next to each field and store them securely in a password manager or secure location.

## Security Best Practices
- Never share API keys publicly
- Always use IP restriction (trusted IPs only) for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Do NOT enable withdrawal permissions

