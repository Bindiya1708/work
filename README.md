# NFT Management Script

This project is a simple JavaScript script to demonstrate basic NFT (Non-Fungible Token) management functionality. The script includes functions to mint new NFTs, list all created NFTs, and get the total supply of NFTs. This example uses plain JavaScript objects and arrays to manage NFT metadata, making it easy to understand the basic principles behind NFT creation and management.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Features](#features)
3. [Getting Started](#getting-started)
4. [How to Use](#how-to-use)
5. [Examples](#examples)
6. [License](#license)

## Project Overview

This script provides a basic example of how to create and manage NFTs. It defines a function to mint new NFTs by creating objects that store metadata such as the NFT's name, description, creator, and owner. The NFTs are stored in an array, and functions are provided to list all NFTs and to get the total number of minted NFTs.

## Features

- **Mint New NFTs**: Create new NFTs by specifying their metadata.
- **List All NFTs**: Display all NFTs and their associated metadata.
- **Get Total Supply**: Retrieve the total number of NFTs that have been created.

## Getting Started

To use this script, you will need:

- A JavaScript environment, such as Node.js or a web browser's developer console.

### Installation

No installation is required. You can copy and paste the script into your JavaScript environment or include it in an HTML file within a `<script>` tag.

## How to Use

1. **Minting NFTs**: Use the `mintNFT()` function to create a new NFT. You need to provide the name, description, creator, and owner of the NFT as parameters.

    ```javascript
    mintNFT("NFT1", "This is the first NFT", "Alice", "Bob");
    ```

2. **Listing NFTs**: Call the `listNFTs()` function to print all the NFTs and their metadata to the console.

    ```javascript
    listNFTs();
    ```

3. **Getting Total Supply**: Use the `getTotalSupply()` function to get the total number of NFTs that have been created.

    ```javascript
    console.log("Total NFTs: " + getTotalSupply());
    ```

## Examples

Below is an example of using the provided functions:

```javascript
// Minting three NFTs
mintNFT("NFT1", "This is the first NFT", "Alice", "Bob");
mintNFT("NFT2", "This is the second NFT", "Charlie", "Dave");
mintNFT("NFT3", "This is the third NFT", "Eve", "Frank");

// Listing all NFTs
listNFTs();

// Printing the total number of NFTs
console.log("Total NFTs: " + getTotalSupply());
