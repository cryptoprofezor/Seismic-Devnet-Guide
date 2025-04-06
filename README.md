# 🚀 Seismic DevNet Encrypted Contract Deployment Guide By MCT

This guide provides a streamlined approach to deploying encrypted contracts on Seismic DevNet, tailored for our community


# 🛠 System Setup Requirements

# 1. Install Rust

Rust is essential for building the necessary binaries.

```
curl https://sh.rustup.rs -sSf | sh  
. "$HOME/.cargo/env"
```

After installation, verify with 

```
rustc --version
```

# 2. Install jq

For WSL/Ubuntu

```
sudo apt install jq
```

For Mac

```
brew install jq
```

# 3. Install sfoundryup

```
curl -L \
     -H "Accept: application/vnd.github.v3.raw" \
     "https://api.github.com/repos/SeismicSystems/seismic-foundry/contents/sfoundryup/install?ref=seismic" | bash
source ~/.bashrc
```

# 4. Run sfoundryup

```
sfoundryup
```
🔺This process might take some time, especially when it appears to stall at 98%. Patience is key


# 📜 Deploying the Encrypted Contract

# 1. Clone the Repo

```
git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git
cd try-devnet/packages/contract/
```

# 2. Deploy the Contract 

```
bash script/deploy.sh
```

This script will generate a new wallet and provide a faucet URL along with the wallet address. Use the faucet link to fund your wallet ✅


# 🤖 Interacting with the Deployed Contract


# 1. Navigate to home directory

```
cd $home
```

# 2. Install Bun

```
curl -fsSL https://bun.sh/install | bash
```

# 3. Install Node Dependencies

```
cd try-devnet/packages/cli/
bun install
```

# 4. Send transactions
Use the provided script to send transactions

```
bash script/transact.sh
```

Done ✅

👉 Join TG for more Updates: https://telegram.me/Mrcrypto_tamilan

If U have any issue then open a issue on this repo or Dm me on TG~

Thank U❤️

