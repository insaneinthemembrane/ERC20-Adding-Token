# Adding an ERC20 token to MyEtherWallet or MetaMask


This is a simple tutorial to show how to add a simple, fixed supply ERC20 token (Eth token)

Please read carefully.

------



![BANK](http://0-3.info/logo.png)





-----

**CONTENTS**


<p><div class="toc">


<a href="#10-your-eth-address">1.0 Your ETH address</a><br>
<a href="#11-adding-token-to-myetherwallet">1.1 Adding Token to myetherwallet</a><br>
<a href="#12-adding-token-to-the-metamask-app">1.2 Adding Token to the Metamask App.
</a><br>
<a href="#13-note-well-on-gas">1.3 Note Well on Gas</a>

-----


# 1.0 Your ETH address

**Send me your ETH address from either myetherwallet or the Metamask App (important you use either of these).** 

The address you give to me, will be the address I send the tokens to. Remember to keep some ETH in the wallet, as you neeed this to send a token (the transaction fee is paid in ETH).


------

# 1.1 Adding Token to myetherwallet

To add your token to your Eth wallet, it is recommended that you use [MyEtherWallet](https://myetherwallet.com). If you have not created a wallet there simply sign up, and back-up your wallet.

On the right-hand side, you will see:



![TokenBalances](https://cdn.pbrd.co/images/H7tsK3H.png)




> **Click: Add Custom Token**
> 
> Three text boxes will appear. **This is the  information you need:**
> 
> **Box 1 (Contract Address)** 
> 
>  (insert the supplied contract address here 0x)
> 
> **Box 2 (Token Symbol)** 
> 
> (insert the token symbol here, e.g. BTC)
> 
> **Box 3 (Number of Decimals)** 
> 
> 18
> 
> 
> Then press "save"
>
> The token is now added to your myetherwallet. You can see it by clicking on the main wallet's "Amount to Send" dropdown box. > 
> (It will say "Your tokenś symbol", e.g. "BTC").
>

-----

# 1.2 Adding Token to the Metamask App

Metamask is a simple Google Chrome App, which is available [here](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn)

Firstly, back up your wallet (Metamask uses seed words, which you will find in "Settings"


To start, on the right, you will see "Add Token"


> Click: Add Token
>
>Three text boxes will appear. Usually with Metamask, once you paste the Contract Address in, it will automatically fill in the next two boxes. This is the information you need anyway:
>
> **Box 1 (Contract Address)** 
> 
>  (insert the supplied contract address here 0x)
>
> **Box 2 (Token Symbol)**
>
> (insert the token symbol here, e.g. BTC)
>
> **Box 3 (Decimals of Precision)**
>
> 18
>
> Then press "Add"
>
>  The token is now added to your Metamask App (wallet)


------

# 1.3 Note Well on Gas



> Be aware, there are different gas requirements for ERC20 tokens than there are to ETH itself. Be sure to use enough gas when sending an ERC20 transaction.
>
> To send ERC20 tokens you must sign a transaction, which uses some itself gas. Gas is sold at a cost per unit price.
>
> TransactionCost = gasUsed * gasPrice
>
> An ERC20 token's gasUsed is "fixed".
>
> If you can make any sense out of this, see: [Ethgasstation](https://ethgasstation.info/predictionTable.php). 

