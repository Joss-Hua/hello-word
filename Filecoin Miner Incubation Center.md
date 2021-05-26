# Foreword

So far, there are about [2700](http://filscan.io/)miners in the Filecoin Network，accounted to more than [5.8EiB](http://filscan.io/) storage power, in the meantime, daily growth of storage power are [30-60PiB](http://filscan.io/)，There are a lot of data that is now stored in the Filecoin network. We found most of the storage power are generaged by miners in Asia, a few of large miners contributed to a larger percentage of storage power to the Filecoin network, for a better Filecoin network and resilent ecosystem, improve the storage power proportions from small and medium miners are essential. But due to the cost of investment, software and hardware configuration, and the rapid growth of Filecoin network, that's not easy to maintain a proper Lucky Value to earn proper reward with providing storage power to the network.  In the meantime, the slower growth of storage power by small&medium miners also reflects the current Filecoin network needs to be strengthened to better support the small&medium miners. 

*Distribution of Miners Based on Storage Power*

| Storage Power/PiB | 0 - 0.1 | 0.1 - 0.5 | 0.5 - 1 | 1 - 2 | 2 - 5 | 5 - 10 | 10 - 50 | 50 - 100 | 100 - ♾ |
| ----------------- | ------- | --------- | ------- | ----- | ----- | ------ | ------- | -------- | ------- |
| No. of Miners     | 995     | 500       | 297     | 341   | 319   | 138    | 100     | 9        | 3       |

</br>

# What is Miner Incubation Center?

### What we have done

We have supported distributed mining pool on Filecoin network based on Implementation-[Venus](https://venus.filecoin.io/Home.html), and the distributed mining architecture is designed for small miners. Small miners friendly from a distributed mining pool can be seen in different aspects, including but not limited to:

1, Venus implementation consists of Public and Independent modules which is cost-effective to bring down the overall cost of hardware maintenance and save the time usage when mining on Filecoin network. Thus, can bring more miners to the Filecoin network with lower barrier to entry. 

2, Through independent module(Venus-miner, Venus-sealer, Venus-wallet,etc) management, that's convient and simple for small miners to manage a single or a few nodes within this system. 

3, With the block generation power/right gathered, miners can combined their resources together, in another way, to preventing the situation like no message can be packed for small miners.

4, Stable rewards to small miners from a distributed mining pool is possible, there are multiple plans under design through a better reward distribution mechanism. 

</br>

### Miner Incubation Center

Miner Incubation Center provide a series of free service to small miners from Venus team supported by resources from public module，operation and maintenance, technical consultancy, the reason to do so is make it simple and convient for small miners to join this network with lower cost and lower barrier to entry.

</br>

### What do we provide

We made it possible through[Venus Distributed Ming Pool Architecture](https://github.com/filecoin-project/venus-docs/blob/master/docs/zh/Overview.md)
The incubation center will keep running public modules like（[venus](https://github.com/filecoin-project/venus)、[venus-auth](https://github.com/filecoin-project/venus-auth)、[venus-messager](https://github.com/filecoin-project/venus-messager)、[venus-miner](https://github.com/filecoin-project/venus-miner)），**miner can only run with（[venus-sealer](https://github.com/filecoin-project/venus-sealer)、[venus-wallet](https://github.com/filecoin-project/venus-wallet)）** and make sure to connect with distributed mining pool then can run with one or a few nodes at the same time.

There maybe some issues to join the incubation center, but we have venus team to support you to do so. 

Due to the different situation with miners, the time and resources required varies too, we do welcome all miners who are interested in the incubation center to read all the rules and check about the requierements first.

</br>

# Rules and Requirements

### Is it suitable for you? 

The incubation center do welcome new or small miners to join immediately, **you need to seal at least 160 sectors per day(5TiB）to join this program, when a miner's storage power reached 1PiB or has participated this program over 90days, then the miner has to withdraw from this program,** and the others who meet the requirements can be joined.

The first term of Miner Incubation Center started from **2021/07/01 - 2021/09/30 with 15 miners**. If you want to join this program, please register it here [Application Form](http://ipfsforce.mikecrm.com/OVZb0Dv)，please fill as more contents as you can so we can review and feedback to you within a short time. Please be known, due to the software and hardware varied a lot, we have to learn more about your application before make the right choice. 

</br>

### Quota of Incubation center

Based on the vision of Filecoin, we hope this program can reach miner in different regions,  but due to the current situation of miners distributed, the number of miners we support within program is as follows:
| Region | Asia | Africa | Ocenaia | Europe | South America | North America |
| ------ | ---- | ------ | ------- | ------ | ------------- | ------------- |
| No.    | 20   | 10     | 10      | 20     | 20            | 20            |

Joining this program will make you one of Venus MinerX program too, we do hope you can work with us to test and feedback about the release of Venus versions later on. In current situation, the block rewards are generated by its own proportion of storage power in the Filecoin network, we are also working on a better mechanism to distribute rewards within a distributed mining pool， and this mechanism can be decided by your feedback.

</br>

# Things you show know

### Incubation center lower the barrier to entry

The public modules of this program is free for miners who joined this program, you can save at least 1 or more servers' cost to run with independent modules only**（servers are required to run with [lotus](https://github.com/filecoin-project/lotus)/[venus](https://github.com/filecoin-project/venus)），de tails about the accurate number of servers reduced need to view case by case.

**Resources provided by Incuation Center (Public Modules)：**

| Modules                     | CPU  | RAM  | HARD DRIVE | No.                   |
| --------------------------- | ---- | ---- | ---------- | -----------------     |
| venus                       | 32C  | 128G | 4T         | 2（1 for backup）      |
| venus-messager + venus-auth | 16C  | 32G  | 100G       | 2（1 for backup）      |
| mysql                       | \    | \    | \          | 1（RDS）               |
| venus-miner                 | 32C  | 64G  | 300G       | 1                     |
| *bandwidth*                 |  \   | \    |      \     | *Based on actual needs* |
 
**Resources provided by miner（Independent Module）：**

| Module                      | CPU                   | RAM                   | HARD DRIVE            |
| --------------------------- | --------------------- | --------------------- | --------------------- |
| venus-sealer + venus-wallet | Based on actual needs | Based on actual needs | Based on actual needs |

For miners successfully joined this program there will be cost saved to participate into filecoin network, in the meantime, you will see lower rate of Orplan Block, more stable message signed successfully, higher gas premium and safe wallet to manage your asset.

</br>

### Run with Venus Implementation - User case（based on Venus v0.9.6 releases）

Deploy Venus Node：https://github.com/filecoin-project/venus-docs/blob/master/docs/zh/How-To-Deploy-MingPool.md

Switch from Lotus to Venus：https://github.com/filecoin-project/venus-docs/blob/master/docs/zh/Venus-replace-lotus.md

</br>

**About  [Application Form](http://ipfsforce.mikecrm.com/OVZb0Dv), [Incubation Center](https://github.com/Joss-Hua/hello-word/edit/main/%E7%9F%BF%E5%B7%A5%E5%AD%B5%E5%8C%96%E5%99%A8%E8%AE%A1%E5%88%92.md)、[Venus Node Deployment](https://github.com/filecoin-project/venus-docs/blob/master/docs/zh/How-To-Deploy-MingPool.md)，if you have any questions, feel free to contact us:**

- Slack: [fil-venus](https://filecoinproject.slack.com/archives/CEHHJNJS3)
- Email: [venus@ipfsforce.com ](venus@ipfsforce.com )

