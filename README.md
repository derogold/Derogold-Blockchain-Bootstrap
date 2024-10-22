# Derogold-Blockchain-Bootstrap
### Don't wait for your node to sync, grab the bootstrap!
##### If you don’t want to wait to sync your node, grab the whole DeroGold Blockchain DB for your node from our IPFS.

### How to download
The most recent DeroGold Blockchain Bootstrap DB is from 22nd October 2024. 

- On Windows Right click [this link](https://ipfs.io/ipns/k51qzi5uqu5dk7pioop6pphvx03nks4f4o39h0ksfvdmfo1p3su3aj1mbzqtiz) and choose `Save link as...` to download the latest bootsrap .tar file.
- On Linux, your fav command-line tool will do the job, use wget for example `wget https://ipfs.io/ipns/k51qzi5uqu5dk7pioop6pphvx03nks4f4o39h0ksfvdmfo1p3su3aj1mbzqtiz`
- Rename the downloaded file `k51qzi5uqu5dk7pioop6pphvx03nks4f4o39h0ksfvdmfo1p3su3aj1mbzqtiz` to `derogold-bootstrap.tar`
- Untar the file `tar xvf derogold-bootstrap.tar` to your DeroGold's daemon `--data-dir` (inside the `.DeroGold` directory (or whatever alternative name you use for your DeroGold data dir)
- Start your DeroGoldd daemon pointing to the data directory where you just untar-ed the bootstrap.
- The DeroGoldd daemon will use the DB bootstrap and sync up the delta between the bootsrap last block and the network top block.

Keep in mind the file is over 305GB large! 
It may take several hours to download from IPFS, especially in the first few days of publishing the bootstrap before it propagates to other IPFS nodes.
It may take several attempts before the file starts to download. 
Tools like wget work best in our experience. You can also use IPFS desktop if you got one installed. 
Yet, downloading the bootstrap file will 100% be much faster to get your node synced with the DeroGold network than syncing from scratch with or without checkpoints. 

Safe yourself a few days, download and use DeroGold bootstrap today. 

### Credits
`DeroGold Developers`
