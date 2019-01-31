# payment-gateways docs

<br>

## Recover missed XOV deposit
<b>* Recover missing XOV deposit having eth tx hash
  1. You need to get the receiver (to) address and amount of transfered XOV tokens via eth tx hash on https://etherscan.io
  2. You need to login to your server with database and match the receiver address with your current addresses and get the Bitshares account ID of the receiver. The name of SQL table with xov wallets is wallets.
  3. You need to check whether there were made such transaction on the xov-main transfers history (you can match it with the time and amount transfered) https://wallet.bitshares.org/#/account/xov-main - transfers history (active tab).
  4. You need to manually send the transaction from xov-main to the user & wait till he receives it
  
---
<br>

## Recover missed BTC deposit
<b>* Recover missing BTC deposit having btc tx hash
  1. You need to get the receiver (to) address and amount of transfered BTC via btc tx hash on https://www.blockchain.com/
  2. You need to login to your server with database and match the receiver address with your current addresses and get the Bitshares account ID of the receiver. The name of SQL table with btc wallets is btc_wallets.
  3. You need to check whether there were made such transaction on the xov-main transfers history (you can match it with the time and amount transfered) https://wallet.bitshares.org/#/account/xov-main - transfers history (active tab).
  4. You need to manually send the transaction from xov-main to the user & wait till he receives it
