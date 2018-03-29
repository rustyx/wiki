# Parity Signer Mobile App tutorial with MyCrypto


This tutorial will walk through setting up an account with Parity Signer Android or iOs App and sign a transaction on [MyCrypto](https://mycrypto.com/) to transfer Ether from one account to another.

## Summary
- [1. Get Parity Signer Mobile App](#1-get-parity-signer-mobile-app)
- [2. Setup or recover an account](#2-setup-or-recover-an-account)
  - [Create an account](#create-an-account)
  - [Recover an account with your recovery phrase](#recover-an-account)
- [3. Sign a transaction on MyCrypto](#3-sign-a-transaction-on-mycrypto)

## 1. Get Parity Signer Mobile App
Get a Smartphone and install the Parity Signer Mobile App making sure that it originated from **Parity Technologies**
- [Android](https://play.google.com/store/apps/details?id=com.nativesigner)
- [iOs](https://itunes.apple.com/us/app/parity-signer/id1218174838)

## 2. Setup or recover an account
When launching the app for the first time, no account has been setup yet. At this stage, you will either want to create an account directly from your mobile device or recover an account already created in with Parity Signer Mobile App or [Parity Wallet](https://wiki.parity.io/Parity-Wallet) (Desktop)
 
### Create an account
 
Click on `create account` or `add` in the top right corner, you will be asked to select an image for your account.

In the next step, you will be presented your newly created address with your recovery phrase.
**Write this recovery phrase down and store it in a safe place**.
If your phone gets stolen/broken/forgotten this will be the only way to recover your funds.

You will then be able to enter a pin number of your choice. This pin will be needed later on to unlock your account to sign a transaction.

![create account](images/Parity-Signer-android-0.png)


### Recover an account with your recovery phrase

If you already created an account using either Parity Signer Mobile App or Parity Ethereum Client, and you wish to recover it, you will want to:
- Click on `create account` or `add` in the top right corner
- Select an image
- Replace the given recovery phrase manually with the one from the account you want to recover
- Set up the pin


## 3. Sign a transaction on MyCrypto

To be able to follow this tutorial and send Ether from a Parity Signer Mobile App account, you will obviously need to get some Ethers on this account. Use the account address or the QR code available on your account main view to get Ether.

Assuming that your account now has funds, you will be able to send securely some Ethers to anyone, without transfering your private key, and without needing any internet connection on your mobile phone.

To do so, visit [https://mycrypto.com/](https://mycrypto.com/) and click on `Parity Signer` and let the website have access to your webcam. This is needed to scan the QR code from your phone.

![Mycrpto parity mobile signer app](images/MyCrypto-Parity-Signer-1.jpg)

On your phone, select the account you want to send Ethers from and make sure that the QR is fully displayed on the phone screen before showing your phone screen to your webcam.

![Mycrpto parity mobile signer app](images/MyCrypto-Parity-Signer-2.jpg)

MyCrypto will now allow you to enter the address of the account you want to send Ethers to as well as the amount of gas. Make sure to try with a small amount of Ethers before. Click on `Send transaction` when you're done.

![Mycrpto parity mobile signer app](images/MyCrypto-Parity-Signer-3.jpg)

You will now be presented with a QR quode that represents the transaction from your phone account, to the adress entered in the previous step on MyCrypto. Now obviously only the account that sits on your phone can sign and authorize this transaction. This is what we'll do.
- From the Parity Mobile Signer App, click on `Scan transaction QR` and scann the QR code presented by MyCrypto
- Review the transaction addresses and the amount to send
- Make sure everything matches, if you got phished, this is where you can realize and reject the transaction!
- Once you're sure, scroll down and click `Next` to enter your pin

![create account](images/Parity-Signer-android-1.png)

Your phone has now *signed the transaction offline* using your Parity Signer Mobile App account private key. The QR code that is now on your phone represents a signed transaction that can be broadcasted. Will will do this in the next steps.
- On MyCrypto, click on `scan`
- Allow the website to access your webcam
- Show your phone to your webcam for MyCrypto to be able to read the signed transaction
- Verify one last time that the account addresses are correct as well as the amount to transfer
- Click on `send` on MyCrypto
- :) you just sent Ether from an air-gapped wallet!

![Mycrpto parity mobile signer app](images/MyCrypto-Parity-Signer-4.jpg)
![Mycrpto parity mobile signer app](images/MyCrypto-Parity-Signer-5.jpg)
