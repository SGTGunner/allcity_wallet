# allcity_wallet

Very modern and usefull display of the money (ESX). 

This script was made by **Kalu** and **Kashnars** of All City, they own the contents.

This script allows you to change the display of your money, on your ESX server and to HIDE IT !

You will have to display “none” the standar ESX HUD to dont have two times : the display of the money.

The current KEY to open it the wallet is `[K]`

This script is made for ESX servers -- requires es_extended.

To use the script, use the following steps:

1. Clone the repo into the resource server folder by `git clone https://github.com/SGTGunner/allcity_wallet.git`
2. Add `start allcity_wallet` to the `server.cfg` file
3. To display none the ESX/Essential mode standard money HUD :

	Open essentialmode / ui.html

	Then find this

	```
	<body>
	     <div id="starter" style="font-family: 'roboto'; color: white; position: absolute; left: 20%; top: 5%; width: 60%; background: rgba(40, 40, 40, 0.8)"></div>
	     <div id="container">
	         <div id="money">
	             <div id="cash"/>
	         </div>
	     </div>
	 </body>
	 ```

4. Then delete this row:

	`<div id="cash"/>`

5. Then open es_extended / html / ui.html
	
	And delete this row:
	
	`<div id="hud"></div>`

