## EOS Voting steps

* Download your OS version from the awesome guys at EOS Canada and unzip it somewhere. ( https://github.com/eoscanada/eosc/releases)
* Open a terminal / cmd window to that directory
* Your machine can be offline for this part if you want
* ```./eosc vault create --import```
  * Create a vault password (don’t lose it or give it out!) Its a wallet password basically
  * Put in your Private key
  * You should get confirmation back of your public key.  compare it to your known public key just to make sure.
* Machine needs to be online to vote now
* Go here and get your Username (https://eosauthority.com/account).  Put your *PUBLIC* Key in this tool, *not* your private one.  Store your Username, you will need it
* Now to Vote
* ```./eosc vote list. (This will display all producers for you to select from)```
* ```./eosc vote producers [your account] [producer1] [producer2] [producer3]```

         For Example:   eosc vote producers  hambhs3  cypherglass eoscanadacom
  * Enter your vault password from above
  * It should say successfully voted
* Verify your vote and tokens here:  https://eosflare.io/account/<your account name>

Your private key is stored encrypted in the wallet file on the computer you ran this on.  If you are not comfortable with this you can delete the wallet file called `eosc-vault.json` when you are done

You can also delete all this shit off your computer if you want.  It created a software wallet that you can use to buy EOS on launch since the HW wallets don’t support it yet.   Your call
