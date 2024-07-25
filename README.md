# Package Prerequisites
```bash
#Update
sudo apt update && sudo apt upgrade

#Install Prerequisites
sudo apt install curl
Verify install of curl by running: curl --version
```
# If You Are New To VOI

Use this method if you are new to Voi and want to set up a new node. During the process, you will be asked for a few details to set up your node, and where we have automated as much as possible.

To set up a new Voi node, run the following command:
```bash 
/bin/bash -c "$(curl -fsSL https://get.voi.network/swarm)"
```

# Using an Existing Account/Address with Mnemonic
For installing with an existing account or mnemonic, use this method. After installation, update your name and GUID for health rewards if setting up on a new server.

To import your account and set up a new Voi node, run the following command:
```bash
export VOINETWORK_IMPORT_ACCOUNT=1
/bin/bash -c "$(curl -fsSL https://get.voi.network/swarm)"
```
# Setting Up Telemetry
# Updating Your Telemetry Name After Installation
To update your telemetry name after installation, or to opt-out, you can run the following command:
```bash
 ~/voi/bin/set-telemetry-name
```
# Getting Your Telemetry Status
To get your telemetry status, including enablement/name/GUID, you can run the following command:
```bash
~/voi/bin/get-telemetry-status
```
# Setting Your Telemetry Name and GUID
When updating servers or reinstalling, it may be desirable to keep the same telemetry name and GUID for health rewards purposes.

To set your telemetry name and GUID, you can run the following command:
```bash
~/voi/bin/set-telemetry-name <telemetry_name> <telemetry_guid>
```
# Creating a Node Wallet 
Create a new wallet with the following command:
```bash
~/voi/bin/create-wallet <wallet_name>
```
# Creating an Account
Create a new account with the following command:
```bash
~/voi/bin/create-account
```
# Retrieving Account Mnemonic
Retrieve the mnemonic of an existing account with the following command:
```bash
~/voi/bin/get-account-mnemonic <account_address>
```
# Importing an Account
Import an existing account with the following command:
```bash
~/voi/bin/import-account
```
# Generating Participation Key
Generate a participation key for an existing account with the following command:
```bash
~/voi/bin/generate-participation-key <account_address>
```
# Checking Participation Status
Check the participation status of an existing account with the following command:
```bash
~/voi/bin/get-participation-status <account_address>
```
# Regenerating Participation Key
After 2 million blocks or in an estimated 60 days, you will need to regenerate a new participation key with the following command:
```bash
/bin/bash -c "$(curl -fsSL https://get.voi.network/swarm)"
```
# Going Online
Bring an existing account online with the following command:
```bash
~/voi/bin/go-online <account_address>
```
# Going Offline
Take an existing account offline with the following command:
```bash
~/voi/bin/go-offline <account_address>
```
# Executing Goal Commands
Execute goal commands with the following command:
```bash
~/voi/bin/goal <goal_command>
```
# Opening a Bash Shell in the AVM Container
Open a bash shell in the AVM container with the following command:
```bash
~/voi/bin/start-shell
```
# Getting Node Health
To retrieve health information about your node, execute the following command:
```bash
~/voi/bin/get-node-status
```
The get-node-status command prints out the following information

Running Voi Swarm image identifier
AVM version
Node health status
High-level service status
Health status and if service is running
If the node is fully caught up with the chain
Account status
Address
Balance
Participation key status
Telemetry status
Enablement
Name
Short GUID
# Set Telemetry Name and GUID
To set telemetry name or to opt-out, execute the following command:
```bash
~/voi/bin/set-telemetry-name
```
To set telemetry name and GUID, execute the following command:
replace <telemetry_name> & <telemetry_guid> 
```bash
~/voi/bin/set-telemetry-name <telemetry_name> <telemetry_guid>
```
# Get Telemetry Status
To get status of your telemetry including enablement, name, and GUID, execute the following command:
```bash
~/voi/bin/get-telemetry-status
```

