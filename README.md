# Derogold-Blockchain-Bootstrap
### Don't wait for your node to sync, grab the bootstrap!
##### If you don’t want to wait to sync your node, grab the whole DeroGold Blockchain DB for your node from our site.

### How to download
The most recent DeroGold Blockchain Bootstrap DB is from 22nd October 2024. 

- On Windows Right click [this link](https://bootstrap.derogold.online/derogold-7.2.2-db-bootstrap-10222024.tar) and choose `Save link as...` to download the latest bootsrap .tar file.
- On Linux, your fav command-line tool will do the job, use wget for example `wget https://bootstrap.derogold.online/derogold-7.2.2-db-bootstrap-10222024.tar`
- Untar the file `tar xvf derogold-bootstrap.tar` to your DeroGold's daemon `--data-dir` (inside the `.DeroGold` directory (or whatever alternative name you use for your DeroGold data dir)
- Start your DeroGoldd daemon pointing to the data directory where you just untar-ed the bootstrap.
- The DeroGoldd daemon will use the DB bootstrap and sync up the delta between the bootsrap last block and the network top block.

Keep in mind the file is over 305GB large! 
It may take several hours to download.
Yet, downloading and using the bootstrap file will 100% be much faster to get your node synced with the DeroGold network than syncing from scratch with or without checkpoints. 

Save yourself a few days, download and use DeroGold bootstrap today. 

### Credits
`DeroGold Developers`
