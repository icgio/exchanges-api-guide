# How to Create an API Key on Gate.io

## Step 1: Log in to Your Gate.io Account
Go to the official Gate.io website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **Create API Key**.
2. Enter an **API Key Remark** (e.g., "ICG-MM", "Liquidity Bot", or project name).

![Create API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%202.png)

## Step 4: Set IP Whitelist
1. Select **Bind IP** option for enhanced security.
2. Enter the IPs provided by the ICG Trading team (**separate multiple IPs using commas**).


![IP Whitelist Settings](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%203.png)
> **Note:** Binding IP addresses is highly recommended to restrict API access to authorized servers only.


## Step 5: Set API Permissions
Under **Permissions**, enable the following:

| Permission | Access Level | Description |
|------------|--------------|-------------|
| Spot/Margin Trade | Read And Write | Submit or cancel spot/margin orders |

### Permissions to Leave Disabled:
- Perpetual Contract
- Delivery Contract
- Earn
- Wallet
- Custody
- **Withdraw** (Never enable for security)
- Option
- Subaccount
- Commission Details
- P2P
- Enable trading pairs allowlist

Click **Submit** to proceed.


![Risk Reminder](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%205.png)

## Step 6: Accept Risk Reminder
A **Risk Reminder** popup will appear. Please confirm that you are aware of the following risks:

1. ☑️ Check the box acknowledging that API Key & Secret equals your account credentials and should be kept safe.
2. ☑️ Check the box confirming you are solely responsible for any damages arising from API Key or Secret leak.

Click **I Accept** to continue.

![API Permissions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%204.png)

## Step 7: Security Verification
Complete the required security checks:
- **Fund Password** - Enter your fund/trading password
- **TOTP Code** - Enter your Google Authenticator (2FA) code

Click **Confirm** to proceed.

![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%206.png)

## Step 8: Save API Credentials
After successful creation, Gate.io will display your API credentials:
- **API Key** - Your public API identifier
- **Secret** - Your private secret key

Click **Confirm** after you have safely stored both credentials.

![API Credentials Display](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/gate/assets/screenshots/Screenshot%207.png)
> **Warning:** The Secret Key is shown only once. Click the **copy icon** next to each field to copy and store them securely in a password manager or secure location.

## Security Best Practices
- Never share API keys publicly
- Always use IP whitelist (Bind IP) for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Do NOT enable withdrawal permissions
