/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// Variable to hold NFTs
let nfts = [];

// Function to mint a new NFT
function mintNFT(name, description, creator, owner) {
    const nft = {
        name: name,
        description: description,
        creator: creator,
        owner: owner
    };
    nfts.push(nft);
}

// Function to list all NFTs
function listNFTs() {
    for (let i = 0; i < nfts.length; i++) {
        console.log("Name: " + nfts[i].name);
        console.log("Description: " + nfts[i].description);
        console.log("Creator: " + nfts[i].creator);
        console.log("Owner: " + nfts[i].owner);
        console.log("-------------------------");
    }
}

// Function to get the total supply of NFTs
function getTotalSupply() {
    return nfts.length;
}

// Minting three NFTs
mintNFT("NFT1", "This is the first NFT", "Alice", "Bob");
mintNFT("NFT2", "This is the second NFT", "Charlie", "Dave");
mintNFT("NFT3", "This is the third NFT", "Eve", "Frank");

// Listing all NFTs
listNFTs();

// Printing the total number of NFTs
console.log("Total NFTs: " + getTotalSupply());

