# Internal highload wallet

Based on [highload wallet](https://github.com/ton-blockchain/ton/blob/master/crypto/smartcont/highload-wallet-code.fc), but instead of public key authentication receives messages using internal transfer from owner account. Also it allows message recursion (sending messages to itself) to send more than 254 actions in one shot.
