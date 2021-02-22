Program update address: https://github.com/nofeeeth/NoDevFee

Email: nofeeeth@gmail.com

Download link: https://wws.lanzous.com/s/nofee

V2.0 has been released: 
1. Fix the problem of high CPU usage   
2. 2. Increase en_us language selection   
3. 3. Increase NBMiner&T-rex core interception  

Port definition: For example, the mining pool address cn.sparkpool.com:3333, the mining pool port is 3333.   
Monitoring the mining pool: adding the mining pool address to this window means that all addresses connected to the mining pool will be blocked.   
Port: need and Monitoring the mining pool with the use of   
mining configuration-mining pool: the address of the mining pool you are using    
mining configuration-port: the port of the mining pool you are using    
mining configuration-wallet: your own mining pool sub-account or ETH Wallet address   
mining configuration-miner name: the name of the machine submitted to the mining pool by your own hashrate   
mining configuration-interception name: the name of the machine submitted to your mining pool with the intercepted hashrate    

EasyGuide  
1. Stop mining
2. Fill in your real pool address and port at this program
3. Fill in wallet,miner,and refund miner
4. Click start
5. Start your minercore at server 127.0.0.1 port any listing port
6. Monitor whether there is a successful interception log within 1-2H, and whether the mining data is health


F&Q  

F: What if the software is blocked by the core? For example (when the software is named NoDevFee.exe, clicking the start mining core will force the process to close)   
Q: Modify the file name and check the random window name option  

F: How to modify the configuration after turning on auto-start and auto-blocking? (Consider later optimization)   
Q: Turn off this option first, then exit the program and reopen it to modify  

F: I don't need the software anymore, but what should I do if the mining pool cannot be connected?   
Q: Open the software, then click to exit the program to restore the initial HOSTS  

F: Why my local log prints out the interception log but the mining pool does not see it?   
Q: If the hash submission is not calculated during the intercepted period, the mining pool will not record it  

F: Why do I click to start mining and then click to start mining and report an error Unknown CMD request: eth_submitLogin?   
Q: Because the port 3333 used by the mining software is forwarded to 127.0.0.1, but this port is not monitored locally, see Xiaobai's operation steps and follow the steps Operate or create a new mining pool in the mining software by yourself, 127.0.0.1 + port in the listening list  

F: ERROR - ethash - Failed to establish connection to mining pool: Connection refused  
Q：The mining software is modified to connect to the non-3333 port mining pool address or 127.0.0.1:13333  

Interception scheme  
1. Hijack the pumping address and change it to your wallet address  
2. Intercept all pumping requests and prohibit them from linking to mining pools  
