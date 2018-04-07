# 0x1
Shell script to install a [0x1 Masternode](http://0x1project.com/) on a Linux server running Ubuntu 16.04. Use it on your own risk.
***

## Installation
```
wget -q https://raw.githubusercontent.com/zoldur/ox1/master/ox1_install.sh
bash ox1_install.sh
```
***

## Desktop wallet setup  

After the MN is up and running, you need to configure the desktop wallet accordingly. Here are the steps:  
1. Open the 0x1 Desktop Wallet.  
2. Go to RECEIVE and create a New Address: **MN1**  
3. Send **10000** 0x1 to **MN1**. You need to send all 10000 coins in one single transaction.
4. Wait for 15 confirmations.  
5. Go to **Help -> "Debug Window - Console"**  
6. Type the following command: **masternode outputs**  
***

## Usage:
```
ox1-cli mnsync status
ox1-cli masternode status  
ox1-cli getinfo
```
Also, if you want to check/start/stop **0x1**, run one of the following commands as **root**:

```
systemctl status ox1 #To check if 0x1 service is running  
systemctl start ox1 #To start 0x1 service  
systemctl stop ox1 #To stop 0x1 service  
systemctl is-enabled ox1 #To check if 1 service is enabled on boot  
```  
***

## Donations

Any donation is highly appreciated

**BTC**: 3MQLEcHXVvxpmwbB811qiC1c6g21ZKa7Jh  
**ETH**: 0x26B9dDa0616FE0759273D651e77Fe7dd7751E01E  
**LTC**: LNZpK4rCd1JVSB3rGKTAnTkudV9So9zexB  
