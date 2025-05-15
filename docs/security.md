# Security & Privacy

In this section, we’ll explain what happens to your UDID, .ipa files, and Certificates. Your privacy and security are our top priorities, and we want to be fully transparent about how we handle your data.

---

## Privacy

### UDID

When you link your device through the app, we store your UDID (Unique Device Identifier) in our secure database. This is necessary to ensure that your access to Deluxe features persists even after relinking your device.

Here’s exactly what we store:

- **UDID** – The unique identifier of your iOS device.
- **Deluxe Status** – A boolean value (`true` or `false`) indicating whether you've purchased Deluxe.
- **Created At** – The timestamp of when you linked your device.

We do not collect any additional personal information. All of this data is provided solely through **your** manual inputs.

---

## Certificates

When you import a certificate via the app, it is uploaded to our server. The server returns secure URLs pointing to the certificate files, which are then stored locally in your browser (LocalStorage) for later use during the signing process.

If you choose a certificate from our Certificate Hub, the app fetches the corresponding prepared URLs from our GitHub repository and stores them in your browser’s LocalStorage as well.

> **Note:** At no point is your certificate password sent to or stored on our servers.

---

## iPAS

When you import a .ipa file via the app, it is uploaded to our server. The server signs the .ipa using an CodeSigning tool for Ubuntu called **ZSign**, the signed .ipa will be parsed using **CFPropertyList** library by rodneyrehm for PHP. a Manifest.plist will be made to work using that Library, and you can install it through itms-services://

Please note the .ipa signing process can be slow which is in an order:
1. Uploading the .ipa, .p12 and .mobileprovision to a newly generated folder on the website
2. Running a CodeSigning command with the settings you prefer and it gets signed
3. Generating the Manifest.plist for you to install through the app.

60-80mb from Switzerland to Netherlands > Amsterdam takes about 20 Seconds with a 70-80 Megabit/s Wifi, because of these steps.

If you have a better internet, it will be faster.

> **Note:** The .ipa's get deleted after 5 minutes

---

## Security

We take multiple measures to protect your data and ensure safe operation of the app:

- **Password Handling:** Certificate passwords are stored only in your browser’s LocalStorage and are never transmitted to our servers. This keeps your private keys safe and under your control.
  
- **File Type Validation:** We strictly verify file types to prevent malicious files (such as PHP, JavaScript, or CGI) from being uploaded or disguised as certificates. This ensures no one can tamper with or spy on your certificates via crafted URLs.

- **Rate Limiting:** Our iPA signing system implements two layers of rate limiting:
  - **DoS Protection:** Prevents individual users from overloading the signing system.
  - **DDoS Mitigation:** Prevents coordinated attacks that attempt to take down the service.
  
- **Code Obfuscation:** Our backend PHP code is obfuscated to make it harder for attackers to analyze and exploit. While not a silver bullet, it adds an extra layer of protection.

- **HTTPS Everywhere:** All communications between the app and our servers are encrypted using HTTPS to ensure your data is secure during transmission.

- **No Persistent Logging:** We do not log personal data or certificate contents beyond the minimum required for operation. Temporary logs are rotated regularly.

---

## Summary

We only collect the data we need to provide our services, and we store it securely. Most sensitive information, especially certificate passwords, never leaves your device. We’re committed to maintaining your trust through transparency and best-in-class security practices.

If you ever have concerns, please feel free to contact us through our Discord Server, which you will find in the Home Page.

[Return to Homepage](https://serenityios.github.io/docs)