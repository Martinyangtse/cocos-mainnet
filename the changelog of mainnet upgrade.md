# 2019/12/24 upgrade to v1.0.9
## solve bugs：
1.display of small negative position.

## add changes：
1.display of small negative position

2.The contract size is configured in congfig, currently 2%，transaction size limit 40K.

3.The mortgage interface change from only accept the name of account to account ID or account name.

# 2020/1/16 upgrade to v1.1.0
## solve bugs：
1.get the calling contract ID in the called contract

## add changes：
1.income distribution of unsuccessful candidates changed from average distribution to voting weight.

2.contract private area size limit.

# 2020/2/13 upgrade to v1.1.1
## add changes：
1.format help info of cli_wallet.

2.Can restrict the contract calling permission, and the contract private key independent signature calling is added.

# 2020/3/3 upgrade to v1.1.2
## add changes：
1.The voting threshold of online governance has been changed from 1 / 2 of the number of councils to 2 / 3 of the number of councils, making community voting more equitable.

2.Optimize websocket network connection to make the link between the developer and the main network more robust

3.Supports Ubuntu 16.04, Ubuntu 18.04, CentOS 7, Mac OS High Sierra, which is convenient for developers to compile on multiple platforms.

4.Developer wallet supports quit command, enabling developers to exit gracefully.

5.Test module is added to the main chain, which is convenient for developers to test and develop




