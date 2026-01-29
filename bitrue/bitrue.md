# How to Create an API Key on Bitrue

## Step 1: Log in to Your Bitrue Account
Go to the official Bitrue website and log in using your account credentials.

## Step 2: Open API Management
1. Click on your **profile icon** (top-right corner).
2. Select **API** from the dropdown menu.

![API Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%201.png)

## Step 3: Navigate to API Page
You will be directed to the API landing page showcasing Bitrue's API services.

1. Click on **Get API Key** button.

![Get API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%202.png)

## Step 4: Create a New API Key
1. Enter an **API Key Name** (e.g., "ICG-MM", "Liquidity Bot", or project name).
2. Click **Create API key** to proceed.

![Create API Key](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%203.png)

## Step 5: Email Verification
A verification email will be sent to your registered email address.

1. Check your inbox (and spam folder if needed).
2. Follow the prompts in the email to verify and create the API Key.
3. Whitelist @bitrue.com to ensure you receive the verification email.

![Email Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%205.png)

## Step 6: Security Verification
Complete the required security check:
- Google Authenticator (2FA) - Enter your Google verification code

Click **Confirm** to finalize the API key creation.

![Google Authentication](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%204.png)

## Step 7: Save API Credentials
### Set API Permissions
Under **Read-Write**, enable the following:

- Read-Only 
- Trade 

> **Important:** Do **NOT** enable **Withdrawal** or **Futures** permissions for security reasons.

### Set IP Access Restrictions
1. Select **Only allow the following IP access (recommended)**.
2. In the **Trust IP** field, enter the IPs provided by the ICG Trading team (**separate each IP using a comma**).
3. Click **Save settings** to finalize.

![API Credentials](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitrue/assets/screenshots/Screenshot%206.png)

> **Warning:** The Secret Key is shown only once. Store it securely.

## Security Best Practices
- Never share API keys publicly
- Use IP whitelist whenever possible
- Disable or delete unused API keys
- Review permissions regularly
