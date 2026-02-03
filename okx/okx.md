# How to Create an API Key on OKX

## Step 1: Log in to Your OKX Account
Go to the official OKX website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API** from the dropdown menu.

![API Management Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%201.png)

## Step 3: Create a New API Key
1. Click on **Create API Key**.

![Create API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%202.png)

## Step 4: Configure API Key Settings
1. Enter an **API Key Label** (e.g., "ICG-MM", "Liquidity Bot", or project name).
2. Enter a **Passphrase** — This is a custom password required for API authentication. Store it securely along with your API Key and Secret Key.
3. Under **IP Whitelist**, enter the IPs provided by the ICG Trading team (**separate multiple IPs using commas**).
4. Set **API Permissions**,
enable the following permissions based on your use case:

| Permission | Description |
|------------|-------------|
| Read | View account and order information |
| Trade | Submit or cancel orders |

### Permissions to Leave Disabled:
- **Withdraw** (Never enable for security)
- Transfer

5. Click **Submit all** to proceed.

![API Key Configuration](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%203.png)

> **Important:** Do **NOT** enable withdrawal permissions for security reasons.




## Step 5: Security Verification
Complete the required security checks:
- **Google Authenticator (2FA)** — Enter your TOTP code
- **SMS Verification Code** — If enabled on your account
![API Permissions](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%204.png)
- **Email Verification Code** — Enter the code sent to your registered email
![Security Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%205.png)

## Step 6: Save API Credentials
After successful creation, OKX will display your API credentials:
- **API Key** — Your public API identifier
- **Secret Key** — Your private secret key
- **Passphrase** — The custom passphrase you created (required for API calls)

![API Credentials Display](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/okx/assets/screenshots/Screenshot%206.png)
> **Warning:** The Secret Key is shown only once. Click the **copy icon** next to each field and store them securely in a password manager or secure location.

## Security Best Practices
- Never share API keys or passphrase publicly
- Always use IP whitelist for production environments
- Disable or delete unused API keys
- Review permissions regularly
- Enable two-factor authentication (2FA) on your account
- Do NOT enable withdrawal permissions
- Store the API Passphrase securely — it is required for all API calls
