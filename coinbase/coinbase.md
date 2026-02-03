# How to Create an API Key on Coinbase

## Step 1: Log in to Your Coinbase Account
Go to the official Coinbase website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Navigate to **Settings**.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%201.png)

3. Select **API** or **API Management** from the menu.

![Create API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%202.png)

## Step 3: Create a New API Key
1. Click on **Create API Key** or **New API Key**.

![API Permissions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%203.png)

2. Enter an **API Key Nickname** (e.g., "ICG-MM", "Liquidity Bot", or project name).

3. Set **API Permissions**,
choose the following permissions based on your use case:

| Permission | Description |
|------------|-------------|
| View | View account balances and details |
| Trade | Submit or cancel orders |

### Permissions to Leave Disabled:
- **Transfer** (Never enable for security)
- **Withdraw** (Never enable for security)

> **Important:** Do **NOT** enable withdrawal or transfer permissions for security reasons.


4. Under **Allowed IP addresses** or **IP Whitelist**, enter the IPs provided by the ICG Trading team (separate multiple IPs using commas).

5. Click **Create & download** to proceed.


![IP Whitelist Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%204.png)

> **Note:** Binding IP addresses is highly recommended to restrict API access to authorized servers only.

## Step 5: Security Verification
Complete the required security checks:
- **SMS Verification** — Confirm via the link or code sent to your phone number

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%205.png)

## Step 6: Save API Credentials
After successful creation, Coinbase will display your API credentials:
- **API Key** — Your public API identifier
- **API Secret** — Your private secret key


![API Credentials Display](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/coinbase/assets/screenshots/Screenshot%206.png)

> **Warning:** The API Secret is shown only once. Click the **copy icon** next to each field and store them securely in a password manager or secure location.

## Security Best Practices
- Never share API keys publicly
- Always use IP whitelist for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Do NOT enable withdrawal or transfer permissions
- Coinbase API keys may have expiration dates — monitor and renew as needed
