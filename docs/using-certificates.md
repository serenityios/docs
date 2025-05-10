# Using Certificates

Firstly, adding the certificates:

## Certificate Hub
If you wanna add one from the Certificate Hub, [This page will show you](docs/certificate-hub.md), however here we will not cover it.

## Custom Certificate
If you wanna add a custom certificate heres the guide:

1. Open The Serenity App ([if you haven't installed it heres the guide](docs/installation.md)) 
2. Click on the Third Icon in the Tab-Bar at the bottom (that looks like a pencil)
3. Click on "Add Certificate" this will show a page
4. In the page, input your .p12, .mobileprovision and .p12 password and hit Submit, these will save your certifiates so you don't always have to put it in again.
5. after that, you have a certificate added (For Devs, its in LocalStorage)
6. You can now Sign .ipa's from repositories or sign your own .ipa from the Signers page!

If you wanna know what happens to your certificates & ipa files, please read our [Privacy & Security Document](docs/security.md)

## Signing Apps
After you have successfully added your Certificate using the guide above, you can now Sign Apps and heres how:

> Signing Your own .ipa
- Firstly, Open Serenity then go to the Signer tab (Pencil Icon)
- Click import .ipa file and you will see the App's info of the App your trying to sign
- Make modifications if you want by clicking at the top right on the Settings icon
- Click Sign and it will give you a prompt to directly install your signed app after its done.

> Signing Apps from Repositories
- First, add a repository using [this guide](docs/adding-repositories.md)
- Then, sign apps from the repository using [this guide to know how to use repositories and how to sign apps from repositories](docs/using-repositories.md)

[Return to Homepage](https://serenityios.github.io/docs)
