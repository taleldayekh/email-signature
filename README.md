# Email Signature

Custom email signature with HTML and CSS.

# Table of Contents

- [Setup Signature for Apple Mail on macOS](#setup-signature-for-apple-mail-on-macos)
- [Setup Signature for Apple Mail on iPhone](#setup-signature-for-apple-mail-on-iphone)

# Setup Signature for Apple Mail on macOS

1. In Apple Mail, navigate to **Settings** -> **Signature**.

2. Under `All Signatures`, create a new signature.

3. Navigate to `/Users/<user>/Library/Mail/V10/MailData/Signature`.

4. Open the signature file ending with `.mailsignature`.

5. Replace the `<body>` and its content with the HTML code from the `email-signature.html` file. Leave any other code as is and close the file.

6. Right click on the `.mailsignature` file and click `Get Info`.

7. Tick the `Locked` checkbox.

8. Restart Apple Mail.

9. The HTML signature will now be available and selectable whenever composing an email.

|                                                               |
| ------------------------------------------------------------- |
| ![Compose Email macOS](/screenshots/compose-email-macos.jpeg) |

# Setup Signature for Apple Mail on iPhone

1. Send the `email-signature.html` file as an attachment in an email to yourself.

2. Open the `email-signature.html` attachment on iPhone, select and hold to copy the signature.

3. Navigate to **Settings** -> **Mail** -> **Signature**.

4. Hold to paste the signature into the field.

5. Three finger tap and press the back arrow to revert the formatting.

6. Tap `Mail` to leave the signature view and get back to Mail settings.

7. The HTML signature will now be available an appear whenever composing an email.

|                                                     |                                                           |                                                                 |
| --------------------------------------------------- | --------------------------------------------------------- | --------------------------------------------------------------- |
| ![Copy Signature](/screenshots/copy-signature.jpeg) | ![Revert Formatting](/screenshots/revert-formatting.jpeg) | ![Compose Email iPhone](/screenshots/compose-email-iphone.jpeg) |
