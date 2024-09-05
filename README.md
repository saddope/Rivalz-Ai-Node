# Rivalz AI Client CLI Guide

## Hardware Requirements

- **CPU:** 4 Cores (2.2GHz)
- **RAM:** 4GB
- **Storage:** 50GB
- **Internet:** 1Mbps

## System Update

Before installing the `rClient`, ensure your system is up-to-date:

```bash
sudo apt update && sudo apt upgrade -y
```

## Installation and Setup

1. **Install the Rivalz Node CLI:**

   ```bash
   sudo npm install -g rivalz-node-cli
   ```

2. **Run the Rivalz Client:**

   ```bash
   rivalz run
   ```

3. **Configuration:**

   - **Submit your EVM Address.**
   - **CPU Core Number:** Choose 50% of your total cores (e.g., if you have 4 cores, select 2 cores).
   - **RAM Size:** Allocate 60% to 70% of your total RAM.
   - **Disk Type:** Choose SSD.
   - **Disk Serial Number:** You can skip this field.
   - **Disk Size:** Choose 300GB or less.

4. **Verification:**

   After running the client for 6 to 12 hours, you can verify your address here:

   [Rivalz Verification](https://be.rivalz.ai/api-v1/orbit-db/verify-orbit-db/(YOUR-EVM-ADDRESS))

## Updating rClient

To update your rClient:

```bash
rivalz update
```

To check for available updates:

```bash
rivalz update-version
```

## Help Command

For help and additional information:

```bash
rivalz -h
```

## Uninstallation

To remove rClient:

```bash
rm -rf .rivalz
```

## Source

For more details, refer to the [Rivalz Documentation](https://docs.rivalz.ai/testnet/testnet-guide/download-and-run-rclient/rclient-cli-guide).
