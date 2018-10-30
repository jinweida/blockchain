# blockchain


echo "# blockchain" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/jinweida/blockchain.git
git push -u origin master


# Usage:
  getbalance -address ADDRESS - Get balance of ADDRESS
  createblockchain -address ADDRESS - Create a blockchain and send genesis block reward to ADDRESS
  printchain - Print all the blocks of the blockchain
  send -from FROM -to TO -amount AMOUNT - Send AMOUNT of coins from FROM address to TO