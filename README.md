# whitepaper
the whitepaper of metaverse
I contributed a new feature and improved deployment instructions
// Check LAND ownership
const landContract = new web3.eth.Contract(LAND_ABI, LAND_ADDRESS);
const owner = await landContract.methods.ownerOf(tokenId).call();
console.log(`LAND Owner: ${owner}`);
