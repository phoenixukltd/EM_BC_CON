# EM_BC_CON
This repo will guide you through the installation and setup of your node on the eigomonster blockchain.

The Eigomonster blockchain runs on the Multichain blockchain and you will need to have a suitable machine on which to install this in order to setup your node. By default, all keys generated by the system come with:

- connect
- send
- receive

permissions already enabled. This will allow you to carry out the basic operations required to maintain your on block profile (OBP)

It is EXTREMELY IMPORTANT to realise that there is no fall back when working with blockchain driven applications. You should NEVER share you private keys as this will compromise your account and you may lose any inputs that you have accumulated to date. There is NO WAY to recover private keys if lost. There is NO WAY to recover inputs that have been spent.

### Download and install the Multichain blockchain

System requirements

Linux: 64-bit, supports Ubuntu 12.04+, CentOS 6.2+, Debian 7+, Fedora 15+, RHEL 6.2+.
Windows: 64-bit, supports Windows 7, 8, 10, Server 2008 or later.
Mac: 64-bit, supports OS X 10.11 or later.
512 MB of RAM
1 GB of disk space

#### Installing MultiChain Community on Linux

Please check for the latest version to download.

    su (enter root password)
    cd /tmp
    wget https://www.multichain.com/download/multichain-2.0.2.tar.gz
    tar -xvzf multichain-2.0.2.tar.gz
    cd multichain-2.0.
    mv multichaind multichain-cli multichain-util /usr/local/bin (to make easily accessible on the command line)
    exit (to return to your regular user)

#### Installing MultiChain Community on Windows

Download https://www.multichain.com/download/multichain-windows-2.0.2.zip and extract its contents to your chosen directory.
