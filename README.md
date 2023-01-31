# Morse-Code-Solidity-NFT
Morse Code NFT Smart Contract which generates SVG image containing the morse code of your input text. The SVG image is generated on the fly and will blink the message on the screen. Everybody can mint a new NFT with a text, if the text has been not minted before from someone else.

## Personalizations
The holders of the NFTs can personalize their NFTs by changing the colors of the off/on states, the size of the image (which is a square by default but it can be a rectangle) and the speed of the blinks.
Personalizations require a payment, the payment is a variable written into the code. Default is 0.01 ETH for changing colors and speed. The size of the square has a variable price depending on the total size of the rectangle.

## Minting
Everybody can mint the NFTs since the collection has not a MAX cap, but there is no possibility to mint already minted texts. So if you want to mint your name but some one else already did it, you cannot mint the same name anymore.
You could add a space at the end to obtain a similar result, but keep in mind that over a certain length of the text, it will be required a payment. Default is over 15 length but it may change. The default payment is set to 0.001 ETH but it may change also. It is to avoid spam or abuse, nothing more.

## Other
Everything is stored on chain. It means the NFTs do not depend from any centralized server or hosting. They will be permanently stored onchain and always available as long as the blockchain is up & running.
