이것은 원작자인 Btran1291님의 TMPlugin-Imagen3의 Fork 버전입니다. 
비공식 버전이므로, 사용에 주의를 요하며, 개인의 책임으로 사용하여 주십시오.

🖼️ **Google Imagen 3 Image Generator**

Generate images from your text prompts using Google's Imagen 3 model! ✨

**Important: This plugin requires you to configure a Google Cloud OAuth 2.0 connection. Follow these steps carefully:**

1.  **Create a Google Cloud Project:** If you don't have one already, create a new project in the Google Cloud Console: [https://console.cloud.google.com/](https://console.cloud.google.com/).
2.  **Enable the Vertex AI API:** In your Google Cloud project, navigate to "APIs & Services" > "Enabled APIs & services" and enable the "Vertex AI API."
3.  **Create OAuth Credentials:**
    *   Navigate to "APIs & Services" > "Credentials."
    *   Click "+ CREATE CREDENTIALS" and choose "OAuth client ID."
    *   **Application type:** Choose "Web application."
    *   **Name:** Give your OAuth client a descriptive name (e.g., "TypingMind Imagen Plugin").
    *   **Authorized JavaScript origins:** `https://www.typingmind.com` or your self-hosted URL.
    *   **Authorized redirect URIs:** `https://www.typingmind.com` or your self-hosted URL.
    *   Click "Create."
    *   You'll receive a **Client ID** and a **Client Secret**, which can be used in the Auth Settings. **Keep the Client Secret *secret*.**

**Note:** If you encounter an "app is not verified" error during authentication, you can authorize yourself by navigating to your Google Cloud Console > "APIs & Services" > "OAuth Consent Screen" > "Audience." Then, click "ADD USERS" under the "Test Users" section and enter your email address.
