# MN-Setup Guide (Follow below Steps)

`wget -q https://raw.githubusercontent.com/HarvestMasternodecoin/OneClick_MN_Setup/master/harvestcore_mn.sh`

`sudo chmod +x harvestcore_mn.sh`

`./harvestcore_mn.sh`

When prompted to Enter your harvest Masternode GEN Key.

Paste your Masternode GEN Key and press enter

Wait untill Node is fully Synced with the blockchain. To check enter the command below.

 `harvest-cli getinfo`

When Node Is Fully Synced enter the command below to , check you masternode status.

`harvest-cli masternode status`

You can check the blocks to match with explorer , use the command below.

`harvest-cli getblockcount`
