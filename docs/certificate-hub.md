# Certificate Hub

A Place to get Certificates for Serenity and any other Third Party Store.

## Where in the app is this Certificate Hub?
Open Serenity, if you didn't install it yet [click here to see how](docs/installation.md). Then wait for the App to load fully and click the **third** icon at the bottom in the tabbar.
then click the "Add Certificates" button and you will see a "Certificate Hub" Button, Click on that to then see the Certificate Hub.

## From Where are these?
These are **Enterprise Certificates** for Sideloading, which means they are issued through Apple’s Enterprise Developer Program. They allow apps to be installed directly on iOS devices without going through the App Store.

## How to Use
1. Select a certificate from the Serenity Certificate Hub (on the app)
2. Download both the `.p12` and `.mobileprovision` files or Select an Enterprise one to straightly use in Serenity.
3. Use our or another signing tool to sign your `.ipa` file with the selected/downloaded certificate.
4. Install the signed app on your device.

## Certificate List
Certificates are displayed in the serenity app. You can search the Certificates by Name only. Each certificate includes:
- Certificate Name
- `.p12` File
- `.mobileprovision` File
- Password (if required)
- Current Status (e.g. Active, Revoked)

> ⚠️ Certificates may stop working without notice. Always have a backup option.

## Need Help?
If you're unsure how to sign apps using these certificates, [Click here](docs/using-certificates.md)

[Return to Homepage](https://serenityios.github.io/docs)
