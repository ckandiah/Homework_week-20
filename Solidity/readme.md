\# Solidity Homework Week 20 \#

\#\# Level One: The AssociateProfitSplitter Contract \#\#

The level one is about transmitting the regular payroll direct
transmittance to wallets, instead of rather bank accounts. So, in this
solution, the Solidity Contract is registering the three addresses on
the start of the deployment. One of these addresses is reserved as owner
( CEO's address). In real world situation, the CEO may not draw for the
deposit from his account but would be doing from a company's bank
account. In my example, I used CEO's account to make deposit. So, for
level one and Level two I draw In order to supply three addresses
representing the three employees, I had to ETH for each, i.e 30 ETH.
Having decided that way I started Ganache : [Screenshots\\Ganache opened
with New Mnemonic
code.png](Screenshots/Ganache%20opened%20with%20New%20Mnemonic%20code.png)
and connect it with Metamask through the Local Chanel. Platform Remix
recognized owner address. Please see the attach screenshot. :
[Screenshots\\Solidity Fetched the owner\'s address from
Metamask.png](Screenshots/Solidity%20Fetched%20the%20owner's%20address%20from%20Metamask.png)

This shot is showing the status of Solidity and Metamask, just before
the first deposit get approved.:

[Screenshots\\Metamask finding the
Solidity.png](file:///C:\Users\chandra\Desktop\Homework%2020\Solidity\Screenshots\Metamask%20finding%20the%20Solidity.png).
The last shot on this level is the Account balances of Ganache:
[Screenshots\\After the deposit Ganache showing
balances.png](Screenshots/After%20the%20deposit%20Ganache%20showing%20balances.png).
The accounting behind the owner account is {100ETH starting , -15 ETH
deposit and the 1/3 of it get transferred back as payroll + 5 ETH, -
Transactions cost so it is = 89.99ETH }

\#\# Level Two: The TieredProfitSplitter Contract \#\#

In this level, all three individuals are receiving different amounts and
so the transfer amounts have to be calculated three times, in solidity.
The balances after the Profit transfers, that is their account balances
are in Ganache table: [Screenshots\\Level 2 Balances in
Ganache.png](Screenshots/Level%202%20Balances%20in%20Ganache.png)

\#\# Level Three: The DeferredEquityPlan Contract \#\#

In this there no ETH involved. Only share units recorded. First 250
shares got recoded in the end of first year. Second 250 shares recoded
in second year. Then the contract was closed for reason of leaving the
job:

Start Of First Year: [Screenshots\\Level 3 First Year start
.png](Screenshots/Level%203%20First%20Year%20start%20.png)

End of Second Year : [Screenshots\\Level 3 First Year start
.png](Screenshots/Level%203%20First%20Year%20start%20.png)
