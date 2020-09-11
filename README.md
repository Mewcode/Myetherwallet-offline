# Myetherwallet-offline
Release v5.7.7
Bug
Add a max check to Aave withdraw #2540
Devop
Update gasprice calculations #2559
Allow users to renew expired ENS names #2554
Using MEW Offline (Cold Storage)
3 min read
For increased security, you can run MyEtherWallet (MEW) on your local computer, instead of from the GitHub servers through our website. The main computer being used to generate the transactions should not be connected to the internet. You can generate a wallet completely offline and send transactions on a different computer, which must be connected to the internet, from our ‘Send Offline’ section. In this way, your sensitive information (i.e. private key, keystore file, mnemonic phrase) is kept on an offline device, and it is never transmitted off your device.

There are two ways to use MEW offline, through the use of PWA or by downloading the client.

Using MEW Offline as a Progressive Web App (PWA)
Step 1. In order to use MEW as a PWA, you’ll first need to head to our website on Google Chrome and install MEW.

Image of MEW main page
Step 2. On your online computer, scroll down to the footer to find our Offline Helper tool.

Image of MEW footer
Step 3. Enter the address you’re sending from and click ‘Export JSON File’.

Keep this safe, you’ll need it momentarily on your offline computer. Export it onto a USB for easy transfer.
Image of MEW's Send Offline Helper
Step 4. On your offline computer, access your wallet as you would normally.

It will look a bit strange, since you’re offline.
Image of MEW offline accessed wallet
Step 5. To the left, select ‘Send Offline’.

Image of MEW 'Send Offline'
Step 6. Scroll down and import the JSON file you received earlier. This will fill in a few details. After that, paste the address you’re sending to and the amount you’d like to send.

Image of MEW offline transaction filled out
Step 7. Now select ‘Generate Transaction’ and download the JSON file, or copy the Signed Transaction.

You’ll need to use the USB from before for this step as well.
Image of MEW offline signed transaction
Step 8. Back to your online computer, head to the Offline Helper tool again and enter the Signed Transaction section.

Upload the JSON file here, or paste the Signed Transaction, then press ‘Continue’. Details should generate in the next section.
Image of MEW offline transaction details
Step 9. Double-check all your transaction details, then click ‘Send’.

Image of MEW offline final transaction confirmation
Step 10. You’re done! You’ve just sent an offline transaction.

Image of MEW offline transaction sent
Downloading and Running MEW Offline
Step 1. In order to set up your local MEW, start by downloading the latest release of MEW.

Image of MEW offline download
Step 2. Click on MyEtherWallet-vX.X.X.X.zip to download the file. Move this file to a USB stick (or another storage transfer device), and transfer it to your permanently-offline computer.

Image of MEW offline zip file
Step 3. Plug the USB into your offline computer and extract all the files into the archive of the computer. Extracting the files is important, otherwise MEW will not open correctly and will look like a bunch of nonsense. You should end up with a folder containing these files:

Image of MEW offline extracting zip file
Step 4. To open MEW, double-click the ‘index.html’ file. This will open MEW in your browser. You will get a warning saying it is unable to connect to the network, which is normal. You’re not connected to the internet. You won’t be able to see your ETH or token balances because of this, but these are viewable in a secure, public way by using an Ethereum blockchain explorer such as etherscan.io or ethplorer.io.

Image of MEW offline 'Index' file
Congratulations, you’re running MEW offline! Make sure to repeat this process periodically, to ensure you’re on the most up-to-date version of our interface.
