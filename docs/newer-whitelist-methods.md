# 2024-2025 Whitelists methods

Here we will give solutions on how to make your apps work again with methods from **2023-2024**

[Click here for older solutions](older-whitelist-methods.md)

Other Useful Guides:

[Avieshek's Wordpress Sideloading guide](https://avieshek.wordpress.com/2024/06/11/how-to-sideload-on-ios/)

# DNS Method

1. go to 
[https://khoindvn.io.vn](https://khoindvn.io.vn/) in the Safari app.
2. Click on the Download button of "Install DNS Profile"
3. It will redirect you and say "This website is trying to download a configuration profile. Do you want to allow this?" Click Allow
4. Click Cancel and open the **Settings App** and scroll down to "General" and click General
5. Scroll down to VPN & Device Management and click on it, click on the KhóinDNS profile in the "Downloaded Profile" section.
6. Click install and enter your passcode if you have one, after read the consent message and click Install and then Install again.
7. Now inside the VPN & Device Management page, click on "DNS" inside the "Restrictions and Proxies" section
8. Make sure you Pick one of the DNS (If you want ad's to still be in game, choose the X one, if you want ads to be removed choose the other one)
9. go back to [https://khoindvn.io.vn](https://khoindvn.io.vn/) scroll down to the "Esign bypass revoke" section, install each of them one by one till you see the ESign logo actually appearing. if its white, delete it.
10. Once ESign is installed successfully, you will click on it but see that the certificate is not trusted so follow step 11
11. Go to VPN & Device Management again, scroll all the way down and you'll see a section named "ENTERPRISE APPS" you will see a distribution there, click on it and click the "Trust "Distribution Name"" then Click "Allow & Restart" or just "Trust"/"Allow" if you arent on 18+ or 17+ (i forgot which version it was implemented in)
12. go back to [https://khoindvn.io.vn](https://khoindvn.io.vn/) and you will scroll down a bit and see "Download esign certificate" for it click on the download icon and click "Download" again once it redirects you.
13. Now you can open ESign, click on the 3 Dots at the top right and click **Import**
14. Find the downloaded .zip in your File Explorer and click on it to import it
15. Click on the imported file and you can Unzip it
16. You will see a new folder called "Esign-Certs" in the ESign app, click on it you will be in the folder
17. All the files will be named with a distribution name, click on the one you used for installing ESign successfully
18. When clicking the right Certificate, you can click "Import Certificate Management" and it will use the Certificate
19. Now to sign .ipa files, you can import an .ipa file by clicking the 3 Dots on esign File page and import then select the .ipa file and it will ask you if you wanna import it to the app library so allow it (if it didnt ask you, click on the .ipa file in the file explorer and import app library)
20. go to the apps page, make sure you are on the "Unsigned page" inside it and click on the app you wanna sign and first make sure you have the right certificate (look for the Select Certificate section, then click on it and select the only certificate you have and click **OK**) then click Signature then click Signature (the red button)
21. It will sign your .ipa file, after its done, click at the Install button at the bottom left
22. Have Happy Signing!

If you wanna sign with Serenity using this method,
[(click here to install it if you haven't already)](installation.md) you can go to the Signer page (Pencil icon at the bottom the third icon) and click Add Certificate then go to the Certificate Hub page and search for your distribution name, we have over 50+ Certificates in the Hub, and select the one that you used for ESign.


[Return to Homepage](https://serenityios.github.io/docs)