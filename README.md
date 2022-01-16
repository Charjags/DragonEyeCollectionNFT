# DragonEyeCollectionNFT
Development and Minting Process of My First NFT: Includes Collection Engine and smart contract for minting NFT onto OpenSea NFT hosting platform. 

The Images and json folders are the final products of the NFT engine. The images represent a collection of artwork developed from a multitiude of patterned layers.
The json files corespond to the metadata of each image. 
json files = metadata

How to Run This project:
- You can use this to develop and deploy any NFT collection you want. It isnt limited to mine.

The NFTArtCollectionEngine part of the project takes layers created on photoshop and randomizes them to create different varieties of patterned pieces of art. 
I have included the layers folder in the NFTArtCollectionEngine to view the way that I structured my layers. Follow the structure of organization when filing your
layers that you want randomized.

Download this repository as a zip.

Run it and change parameters in config.js to change quantity, style, and/or layers to create your collection of media.

Create an account on pinata.cloud. This saves the images and metadata to the cloud. Paste the CID of the uploaded images into the baseUri portion in config.js 
MAKE SURE TO INCLUDE ipfs://. OpenSea has certain requirements when wanting to upload to their testnet.

To save your recent changes, open terminal and type node utils/update_info.js

Pinata and the media in the program should now be linked with updated changes to the meta data.

Save the metadata json files and upload them to pinata as well. 

Now both the media and metadata is uploaded to the cloud.

Go to the online ethereum compiler, remix.ethereum.org

Paste the smart contract code into a new workspace. Delete any other example contracts. 

Once the contract is compiled, deploy and you are done!







