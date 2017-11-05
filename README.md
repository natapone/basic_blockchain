# basic_blockchain
Test Blockchain concept

Source
 https://medium.com/@lhartikk/a-blockchain-in-200-lines-of-code-963cc1cc0e54
code
https://github.com/lhartikk/naivechain

cd /home/vagrant/project/basic_blockchain


# Show blocks
http://localhost:3001/blocks

# Add data to block
curl -H "Content-type:application/json" --data '{"data" : "Some data to the first block"}' http://localhost:3001/mineBlock
