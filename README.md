# AutoStakeRewards

AutoStakeRewards is a script designed to automatically claim all rewards for a validator and stake them back into the same validator. The script also allows you to specify the commission rate and the minimum amount of coins that should remain in the wallet.

## Key Features

- **Automatic Reward Claiming**: Automatically claims all rewards for the validator.
- **Automatic Staking**: Stakes the claimed rewards back into the same validator.
- **Commission Setting**: Allows you to specify the commission rate.
- **Minimum Balance Setting**: Ensures a minimum amount of coins remain in the wallet.
- **Logging**: Logs all transactions and actions for monitoring.

## Requirements

- **Bash**: Ensure you have a Bash shell environment.
- **Cosmos CLI**: Ensure you have the Cosmos CLI installed and configured properly.
- **jq**: Command-line JSON processor.

## Installation

1. **Clone the Repository**:

    ```sh
    git clone https://github.com/your-username/AutoStakeRewards.git
    cd AutoStakeRewards
    ```

2. **Make the Script Executable**:

    ```sh
    chmod +x autostake_rewards.sh
    ```

3. **Configure the Script**:

    Edit the `autostake_rewards.sh` script to include your validator address, commission rate, and minimum balance.

## Configuration

- **Validator Address**: Set your validator address.
- **Commission Rate**: Set the commission rate you want to apply.
- **Minimum Balance**: Set the minimum amount of coins that should remain in the wallet.

## Example Usage

Run the script to automatically claim rewards and stake them:

```sh
./autostake_rewards.sh
