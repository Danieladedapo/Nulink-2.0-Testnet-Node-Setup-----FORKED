# NuLink Testnet Horus 2.0
About installing a node


![nlk](https://github.com/Lorento34/NuLink-Testnet-Horus-2.0/assets/84406096/5942336a-d881-4c50-8504-63fc6609c957)


<h1>Minimum System Requirements<h6>

 - Debian/Ubuntu 20.04 (Recommended)
 - 4 GB Ram
 - 30GB Available Storage
 - Minimum 2 CPU processors
 - x86 Architecture
 - Static IP address
 - Exposed TCP port 9151, make sure it's not occupied
 - Nodes can be run on cloud infrastructure

<h1>NuLink Worker Installer steps for Ubuntu 20.4<h6>

1- First of all, if you are going to install outside of vps providers where ports such as Contabo, Hetzner, Linode, Digital Oceon are open. You must open port 9151 with the codes below or from the virtual server provider's own site.

```
sudo ufw enable
sudo ufw allow 9151
```

2- Download Geth on your server.
 
```
wget https://gethstore.blob.core.windows.net/builds/geth-linux-amd64-1.10.23-d901d853.tar.gz
```

3- Unzip the downloaded installation package.

```
tar -xvzf geth-linux-amd64-1.10.23-d901d853.tar.gz
```

4- Enter the unzipped directory

```
cd geth-linux-amd64-1.10.23-d901d853/
```

5- Use. / get account new -- keystore. / keystore to generate Ethereum account and keystore

```
./geth account new --keystore ./keystore
```

6- After using ./geth account new --keystore ./keystore you will be asked to enter and confirm the password. Please remember this password for future use. Sample output should be as follows.

![keys](https://github.com/Lorento34/NuLink-Testnet-Horus-2.0/assets/84406096/b41caa54-2d62-47fb-a8ee-f861fd6ca894)





















