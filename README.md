# Transformers-Chain-Testnet-Nodes-Installation
Transformers Chain Testnet Nodes Installation 

Install Screen

" sudo apt-get update "
" sudo apt-get install screen "

Create new directory for transformers, and enter the folder

" mkdir transformers "
" cd transformers "

Download the nodes software latest version v33

" wget https://fastcdn.uscloudmedia.com/transformers/formal/tfs_v0.33.0_618b167_testnet.zip "
" apt install unzip "
" unzip tfs_v0.33.0_618b167_testnet.zip "
" chmod +x tfs_v0.33.0_618b167_testnet "

Run the software with -c flag to create configuration files

" ./tfs_v0.33.0_618b167_testnet -c​ "

Edit configuration

" sudo nano config.json "

Change/Add your IP to the file. the IP place, not the IP http.

Run the softwares

" ./tfs_v0.33.0_618b167_testnet -m " 

