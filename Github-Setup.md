# GitHub Webhook Integration Setup

Follow these steps to configure the webhook for your repository:

---

## 1. Navigate to Repository Settings
- Go to your GitHub repository.
- Click on **Settings** in the top menu.

---

## 2. Open Webhooks
- In the left sidebar, click **Webhooks**.

---

## 3. Add a New Webhook
- Click the **Add webhook** button.

---

## 4. Configure Payload URL
- Enter the following URL in the **Payload URL** field:
{url}/tenants/{url}/webhooks/github

yaml
Copy code
> Replace `{url}` with your tenant-specific value.

---

## 5. Set Content Type
- Under **Content type**, select **`application/json`**.

---

## 6. Set Secret
- Enter your webhook **secret key** in the **Secret** field.

---

## 7. Enable SSL Verification
- Make sure **Enable SSL verification** is checked.

---

## 8. Choose Individual Events
- Under **"Which events would you like to trigger this webhook?"**, select:
  - **"Let me select individual events."**

---

## 9. Select Events
Enable the following events:
- Branch or tag creation  
- Commit comments  
- Deployment statuses  
- Deployments  
- Discussion comments  
- Discussions  
- Issue comments  
- Pull request review comments  
- Pull request review threads  
- Pull request reviews  
- Pull requests  
- Releases  
- Workflow runs  
- Statuses  

---

## 10. Save the Webhook
- Click **Add webhook** at the bottom to save your configuration.

---

✅ Your GitHub webhook integration is now set up successfully!
