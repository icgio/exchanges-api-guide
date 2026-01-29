# How to Create an API Key on Biconomy

## Step 1: Log in to Your Biconomy Account
Go to the official Biconomy website (biconomy.com) and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API Management** from the dropdown menu.

## Step 3: Create a New API Key
1. Click on **Create API** or **Create New API Key**.
2. Enter an **API Note / Remark** (e.g., "ICG-MM", "Liquidity Bot", or project name).

## Step 4: Set API Permissions
Choose the following permissions based on your use case:

### Recommended Permissions
| Permission | Description |
|------------|-------------|
| Read | Query account balance, order history, and trade records |
| Trade / Spot Trading | Submit, modify, or cancel spot orders |

> **Important:** Do **NOT** enable **Withdrawal** permissions for security reasons.

## Step 5: Set IP Whitelist (Recommended)
1. Enable **IP Restriction** or **Bind IP Address**.
2. Enter the IPs provided by the ICG Trading team (**separate multiple IPs using commas**).

> **Note:** Binding IP addresses significantly improves API security by restricting access to authorized servers only.

## Step 6: Security Verification
Complete the required security checks:
- Email verification code
- Google Authenticator (2FA) - if enabled
- SMS verification - if enabled

Click **Confirm** or **Submit** to finalize the API key creation.

## Step 7: Save API Credentials
After creation, Biconomy will display:
- **API Key** (Access Key)
- **Secret Key**

> **Warning:** The Secret Key is shown only once. Store it securely in a password manager or secure location.

## Security Best Practices
- Never share API keys publicly
- Always use IP whitelist for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Use separate API keys for different applications or purposes
