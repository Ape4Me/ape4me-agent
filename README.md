# Ape4Me Agent
Telegram useragent Windows application that connects your telegram account and watch for the Solana / pump.fun token address in groups and channels you sets in configuration, then sends buy signal to our trade API. When trade API gets Token Address and Wallet ID it will buy this token as soon as possible. You can generate up to 3 free wallets, gets their public and private keys and also set amount of SOL for token purchase when API gets address. The app don't share or have access to information about your channels and groups, also they can be private. The logic of the telegrams part, where it watch groups and channels works on users PC, our API gets only token address and wallet id that was given to user by our telegram bot.