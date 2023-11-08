Transformers Chain is an open-source fork network based on The United Engine Chain. It continues and optimizes its lightweight consensus algorithm and renamed it the Raindrop consensus protocol making it decentralized, fast, and with low energy consumption. Through the reconstruction of the incentive layer protocol, the network will enter into harmonious development again. Transformers will build a prosperous global ecosystem with its unique advantages.

Hardware requirements：​

CPU: Recommend for Intel Pentium CPU series and above, core number 8 core and above.
Memory: Recommend for 16G And above
Disk: Recommend for 500G And above
Software requirements：​

Operation system：Run on CentOS 7、ubuntu-20.04-desktop-amd64 system.

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

Creating a session in `Screen`

" screen -S tfsc " 

Run the softwares

" ./tfs_v0.33.0_618b167_testnet -m " 

You’ll find your TFSC address, copy the wallet address and request from #faucet channel on TFSC discord.

**Stake** 1000 TTFSC
**Delegate** 10000 TTFSC

Wait for the next task (after you get some delegation from dev), you need to claim bonus daily (start on 01.00 UTC).
