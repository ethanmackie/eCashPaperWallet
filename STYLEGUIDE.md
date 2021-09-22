**Contributing new wallet designs**

If you'd like to contribute new design options for this wallet, but don't know how to test whether it fits properly with the generated output, then follow the instructions below:

1. Download a [zip of the eCash paper wallet](https://github.com/ethanmackie/eCashPaperWallet/blob/main/master.zip)

2. Go to the /img/ folder and replace "style2_inksaver.png" with your own style image. This effectively changes the 'Default' style option to your design.

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic1.png)

3. Go back to the root of the project folder and open the Index.html file in your web browser

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic2.png)

4. Do the usual randomisation via mouse or keyboard to generate the paper wallet

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic3.png)

5. Select the Default design on the left to see how your new design looks when the paper wallet is generated

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic4.png)

6. A properly fitted paper wallet template will have the public address, private key and the corresponding QR codes showing as highlighted in yellow below.

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic5.png)

7. The default font colour for addresses is black so if you're doing a design with a dark background then you'll need to adjust the font colour for contrast. Look for this line in Index.html to change the colour accordingly, around line 10877.

![](https://github.com/ethanmackie/eCashPaperWallet/blob/main/img/guidepic6.png)


If it looks all ok then either raise a PR or ping me on [twitter.](https://twitter.com/pungentaura)
