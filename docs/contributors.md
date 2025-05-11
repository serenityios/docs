# Contributors


At Serenity, we have only 1 Developer working on it, which is also the one writing this document.
This is a Solo Project, multiple people's projects helped me.

## URL Schemes

URL Schemes, the thing that is letting us import .ipa's from repositories to apps like Scarlet.

It was very hard to find these URL Schemes, so we got a little help from the project **App Box**
URL: [https://app.appbox.click/](https://app.appbox.click/)


## iPA Parsing

To make our signer read and output the info when you import an .ipa, we used a api that someone on Code Sandbox made.
This was very useful because it didnt waste time.

URL: [https://codesandbox.io/p/sandbox/app-info-parser-x9pfzn](https://codesandbox.io/p/sandbox/app-info-parser-x9pfzn)

## Signing

Our Server is running on Linux, so we needed a **Code Signing** Alternative (for .ipa signing)
We found a code signing alternative called ZSign, it let us change the entitlements of an app, injecting dylibs and signing it using a .p12 and .mobileprovision.

URL: [https://github.com/zhlynn/zsign](https://github.com/zhlynn/zsign)

## Inserting Dylibs

Sometimes, injecting a .dylib in the Frameworks or .app folder wasnt so useful, so we had to improvise;
Inserting Dylibs inside **BINARIES** where the ViewControllers are located (ViewControllers is what you see when you open the app)

This is done with the tool insert_dylib on github by tyilo.

URL: [https://github.com/tyilo/insert_dylib](https://github.com/tyilo/insert_dylib)

## Retrieving UDID

Because we don't have a Developer Certificate yet, we cant make an UDID Retriever
So we spent time, looking for an API and we found one: S0n1c's UDID Retrieval API!

URL: [https://udid.s0n1c.ca/docs](https://udid.s0n1c.ca/docs)




[Return to Homepage](https://serenityios.github.io/docs)