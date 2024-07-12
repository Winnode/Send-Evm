# Send Balance Winsnip Testnet

This project is allows users to interact with the Ethereum blockchain to send ETH to multiple wallets, generate new wallets, and load wallet addresses from a file. It uses the Web3.py library for blockchain interactions and provides 

## Features

- Generate new Ethereum wallets.
- Send ETH to multiple wallets loaded from a JSON file.
- Send ETH to multiple wallets loaded from a text file.
- Log all transactions and errors.
- Customizable through a `config.json` file.

## Installation

### Prerequisites

- Python 3.6 or higher
- `pip` package manager

### Libraries

Install the required Python libraries using pip:

```bash
git clone https://github.com/Winnode/Send-Evm.git
cd Send-Evm
```

```bash
pip install -r requirements.txt
```

OR

```bash
pip install web3 pyfiglet colorama
```

Create a config.json file in the same directory as the script with the following content:

```json
{
    "rpc_url": "YOUR_RPC_URL_HERE",
    "private_keys": ["YOUR_PRIVATE_KEY_1", "YOUR_PRIVATE_KEY_2"],
    "gas_price_gwei": "YOUR_GAS_PRICE_IN_GWEI",
    "gas_limit": "YOUR_GAS_LIMIT",
    "min_eth": "MINIMUM_ETH_AMOUNT",
    "max_eth": "MAXIMUM_ETH_AMOUNT"
}
```

### Run
```
python run.py
```

OR

```
pyrhon3 run.py
```


