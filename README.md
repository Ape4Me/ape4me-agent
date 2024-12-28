# Ape4Me Agent
Telegram useragent Windows application that connects your telegram account and watch for the Solana / pump.fun token address in groups and channels you sets in configuration, then sends buy signal to our trade API. When trade API gets Token Address and Wallet ID it will buy this token as soon as possible. You can generate up to 3 free wallets, gets their public and private keys and also set amount of SOL for token purchase when API gets address. The app don't share or have access to information about your channels and groups, also they can be private. The logic of the telegrams part, where it watch groups and channels works on users PC, our API gets only token address and wallet id that was given to user by our telegram bot.

## How to get Telegrams Channel/Group ID
Method 1 (Web A)
This is based on JayeshRocks’s question with some extra steps to make the ID work with Bot API.
Login to Telegram Web A.
Open the chat you want to get its ID.
Your browser’s address should look like https://web.telegram.org/a/#-1527776602.
Remove the scheme, the hostname and the path, keeping the anchor so your result looks like #-1527776602.
Replace “#-” so it looks like 1527776602.
You can now use your final result which should look like 1527776602.

Method 2 (Private Supergroups)
If the chat is a private channel/supergroup, you can do the following:
Copy a link of a message. (It will look like https://t.me/c/1527776602/1002.)
Remove the protocol and domain name, so it looks like c/1527776602/1002.
Remove the first and last path, so it looks like 1527776602.
You can now use your final result which looks like 1527776602.
