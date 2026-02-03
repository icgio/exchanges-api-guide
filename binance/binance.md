# How to Create an API Key on Binance

## Step 1: Log in to Your Binance Account
Go to the official Binance website and log in using your account credentials.

> **Note:** Your account must be fully verified (KYC completed) before you can create API keys. If you haven't completed verification, go to **Identification** in your account settings to verify your identity first.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **Account** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%201.png)

3. Navigate to **API Management** from the left sidebar.

![Select API Type](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%202.png)

## Step 3: Create a New API Key
1. Click on **Create API**.

![API Label](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%203.png)

2. Select **System generated** as the API key type (recommended for most trading use cases).

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%204.png)

## Step 4: Label Your API Key
1. Enter an **API Label** (e.g., "ICG-MM", "Liquidity Bot", or project name).
2. Click **Next** to proceed.

![API Credentials Display](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%205.png)

## Step 5: Security Verification
Complete the required security checks:
- **Email Verification Code** — Enter the code sent to your registered email
- **Phone Number Verification Code** — Verify using SMS code
- **Google Authenticator (2FA)** — Enter your TOTP code

![Edit Restrictions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%206.png)

## Step 6: Save API Credentials
After creating the API key, you must configure the restrictions:

1. Click **Edit restrictions** next to your newly created API key.

2. Under **API restrictions**, enable the following permissions:

| Permission | Description |
|------------|-------------|
| Enable Reading | View account and order information |
| Enable Spot & Margin Trading | Submit or cancel spot/margin orders |

### Permissions to Leave Disabled:
- Enable Futures
- Enable Vanilla Options
- Enable Withdrawals (Never enable for security)
- Enable Internal Transfer
- Permits Universal Transfer

> **Important:** Do **NOT** enable withdrawal permissions for security reasons.

3. Under **IP access restrictions**, select **Restrict access to trusted IPs only (Recommended)** and enter the IPs provided by the ICG Trading team.

4. Click **Save** to apply the restrictions.

After successful verification, Binance will display your API credentials:
- **API Key** — Your public API identifier
- **Secret Key** — Your private secret key

![API Restrictions Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/binance/assets/screenshots/Screenshot%207.png)

> **Warning:** The Secret Key is shown only once. Click the **Copy** button next to each field and store them securely in a password manager or secure location.


## Security Best Practices
- Never share API keys publicly
- Always use IP restriction (trusted IPs only) for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Do NOT enable withdrawal permissions
- Binance requires periodic review of API keys — monitor expiration notices
