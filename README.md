

# 3dcoin-masternode

[![](https://images.microbadger.com/badges/version/hodlitio/3dcoin-masternode.svg)](https://microbadger.com/images/hodlitio/3dcoin-masternode "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/image/hodlitio/3dcoin-masternode.svg)](https://microbadger.com/images/hodlitio/3dcoin-masternode "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/commit/hodlitio/3dcoin-masternode.svg)](https://microbadger.com/images/hodlitio/3dcoin-masternode "Get your own commit badge on microbadger.com")

## Can also be found at Docker Hub:
[3dcoin-masternode@DockerHub](https://hub.docker.com/r/hodlitio/3dcoin-masternode/)

## What is 3dcoin-masternode project?
This is a Docker image that starts a 3dcoin daemon and start a masternode. You need 1000 3DC for spinning up your own masternode. You can have as much masternodes as you can afford. This project aims to automate the process of spinning up a new masternode.

## Is it free?
Anyone can use this image whenever they like. It is MIT licensed so do whatever you want with it, we are not responsible for anything caused by the usage of it. More masternodes makes network faster and secure. Unlike our miner projects, this one has no fees associated with usage, it is totally free of charge, a gift to the community from us.

## What are the requirements?
You need to have [Docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/) installed. How? Check out our [Digital Ocean](https://www.digitalocean.com/?refcode=fc06220e24cc) Ubuntu 16.04 image security hardening guide. (this is not ready yet, will be added later).

Here is a quick script before we release a detailed tutorial to install it on Ubuntu 16.04:

    apt-get update && apt-get install -y apt-transport-https ca-certificates curl software-properties-common && curl -fsSL https://download.docker.com/linux/ubuntu/gpg | apt-key add - && add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" && apt-get update && apt-get install -y docker-ce && docker --version

## I have Docker installed, now what?
You just have to run the command below, that's all:

    docker run -d --name hodlit-masternode -p 6695:6695 hodlitio/3dcoin-masternode REPLACE_THIS_WITH_HOST_IP_ADDRESS REPLACE_THIS_WITH_MASTERNODE_PRIVATE_KEY

here is a concrete example:

    docker run -d --name hodlit-masternode -p 6695:6695 hodlitio/3dcoin-masternode 127.0.0.1 5P1xqTgJMtXwEEeE3TgJHYn26fWz8UkqN1cUmt2345qUdSaEtH4

## I would like to support HODLit.io team
Thanks! You can support us by registering to [Digital Ocean](https://www.digitalocean.com/?refcode=fc06220e24cc) with our referral link or donating to addresses below:

Bitcoin (BTC) donation address:
Ethereum (ETH) donation address:
Litecoin (LTC) donation address:
Monero (XRM) donation address:

3DCoin (3DC) donation address:

    AaMmmB5c3DKYuQEeTB6vc5fPt8gsUnJaVz

## I would like to contact HODLit.io team
Mail:
Twitter:
Telegram:
