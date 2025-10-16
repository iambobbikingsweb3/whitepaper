I contributed a new feature and improved deployment instructions
const landContract = new web3.eth.Contract(LAND_ABI, LAND_ADDRESS);
async function verifyLand(tokenId) {
  return await landContract.methods.ownerOf(tokenId).call();
}
