# How to Create an API Key on BitMart

This guide will walk you through the process of creating an API key on BitMart exchange.

---

## Step 1: Access API Management

1. Log in to your BitMart account
2. Click on your profile icon in the top right corner
3. Select **"API Management"** from the dropdown menu

![Account Menu](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitmart/assets/screenshots/Screenshot%201.png)

---

## Step 2: Create New API

On the API Management page:

1. Locate the **"Create New API"** section
2. Enter a **Memo** (name) for your API key (e.g., `ICGMM`)
3. Select the **Authority** (permissions) you need:
   - Read Only
   - Spot-Trade

4. Add an **IP whitelist** and include the IPs provided by the ICG Trading team:
   - Format: `11.111.111.111`
   - Multiple IPs can be separated by commas

5. Click **"Submit"**

![Create API Form](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitmart/assets/screenshots/Screenshot%202.png)

---

## Step 3: Complete Verification

1. A verification popup will appear
2. Enter the **Email Code** sent to your registered email
3. Click **"Submit"** to verify

![Email Verification](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitmart/assets/screenshots/Screenshot%203.png)

---

## Step 4: Save Your API Credentials

After successful verification, you'll see your API credentials:

- **Access Key:** Your public API key
- **Secret Key:** Your private key (shown only once!)



Click **"Confirm"** to complete the process.

![API Created Successfully](https://raw.githubusercontent.com/icgio/exchanges-api-guide/refs/heads/main/bitmart/assets/screenshots/Screenshot%204.png)
> ⚠️ **Important:** The Secret Key is displayed only once. Save it immediately in a secure location. If lost, you must delete the API and create a new one.

---

## Security Tips

- Only enable permissions you actually need
- Always bind IP addresses when possible
- Never share your Secret Key with anyone
- Disable or delete unused API keys