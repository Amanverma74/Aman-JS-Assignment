# Creating a Javascript code for Holding NFTs

The project aims to create a Solidity smart contract for managing non-fungible tokens (NFTs). It includes functions for minting new NFTs with metadata, listing existing NFTs, and getting the total supply of minted NFTs. This contract can be used as a basis for developing NFT marketplaces, digital asset management systems, or blockchain-based applications involving unique digital assets.

## Description
This project revolves around the creation of a Solidity smart contract designed for managing non-fungible tokens (NFTs) on the Ethereum blockchain. NFTs are unique digital assets that are indivisible and cannot be exchanged on a one-to-one basis like cryptocurrencies. They have gained popularity in various domains such as digital art, collectibles, gaming assets, and more, due to their ability to represent ownership and scarcity in the digital world.

The smart contract includes essential functionalities for NFT management:

1. Minting NFTs: The contract allows for the creation of new NFTs with associated metadata. Users can specify attributes such as name, description, image URL, and other relevant information during the minting process.

2. Listing NFTs: A function is implemented to list all minted NFTs along with their metadata. This feature enables users to view and explore the collection of NFTs managed by the contract.

3. Total Supply Tracking: The contract keeps track of the total number of minted NFTs, providing insights into the overall supply and availability of these digital assets.


### Getting Started

### Installing

Clone this repository to your local machine:

git clone https:(https://github.com/Amanverma74/Aman-JS-Assignment/new/main?filename=README.md)

#### 1. Create an Array to Hold NFTs:
let mintedNFTs = [];

This line creates an empty array named mintedNFTs that will be used to store NFT objects.

#### 2. mintNFT Function:
function mintNFT(name, creator, description) {
    const nft = {
        name: name,
        creator: creator,
        description: description
    };
    nfts.push(nft);
}
mintNFT is a function that takes three parameters: name, creator, and description. Inside the function, it creates a new object nft with properties name, creator, and description. The object nft represents a Non-Fungible Token (NFT) with metadata. Finally, the nft object is added to the nfts array using push.

#### 3. listNFTs Function:
function listNFTs() {
    for (let i = 0; i < nfts.length; i++) {
        console.log("Name: " + nfts[i].name);
        console.log("Creator: " + nfts[i].creator);
        console.log("Description: " + nfts[i].description);
        console.log("-------------------------");
    }
}
listNFTs is a function that logs the metadata of all minted NFTs in the nfts array. It iterates through each NFT object in nfts and logs the name, creator, and description properties to the console.


#### 4. getTotalSupply Function:
function getTotalSupply() {
    return nfts.length;
}
getTotalSupply is a function that returns the total number of minted NFTs in the nfts array. It simply returns the length property of the nfts array, which represents the number of elements (NFTs) in the array.

#### 5. Example Usage:
mintNFT("Art Piece 1", "Artist A", "A beautiful piece of art.");

mintNFT("Art Piece 2", "Artist B", "A stunning sculpture.");

mintNFT("Art Piece 3", "Artist C", "A captivating digital painting.");

listNFTs();

console.log("Total Supply: " + getTotalSupply());
Three NFTs are minted using the mintNFT function with different metadata (name, creator, description). listNFTs is called to log the metadata of all minted NFTs to the console. getTotalSupply is called to get the total number of minted NFTs, which is then logged to the console.

### Help
If you encounter any issues or have questions, please refer to the documentation or contact the contributors:

### Authors

Aman Verma

https://github.com/Amanverma74




