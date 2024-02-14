# Nulink

https://docs.nulink.org/products/stakers/nulink_worker/worker_running

## Requirement

Have a Worker account: https://docs.nulink.org/products/stakers/nulink_worker/eth_account

## Configuration

```yaml
nulink_config_operator_address: '0x00000000000000000000000000000' # Public address of the wallet
nulink_keystore_password: 'ThatsNotASecurePwd'
```



## Installation

1. Play this role to create directories and install files.
2. Connect to the host and run the script `generate-validator-keys.sh`. Backup the values provided in the script.
3. Run the ``docker-compose.yml`` by running the playbook again with the variable `nulink_account_created` to true.
4. Follow the instruction on `https://docs.nulink.org/products/stakers/dashboard`.

