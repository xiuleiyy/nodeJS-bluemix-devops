Get started with nodeJS-bluemix
-----------------------------------
Welcome to your new Node.js app!

Node.js app runs on a server-side high performance, highly scalable, event-driven environment with non-blocking I/O that is programmed with the JavaScript programming language.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://ace.ng.bluemix.net:443/rest/../rest/apps/eca1844e-6602-45ad-b7d9-34ac0555f6e1/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u xiuleizh@cn.ibm.com
		cf target -o OE_Runtimes_SVT -s RT_SVT

6. Deploy your app:

		cf push nodeJS-bluemix

7. Access your app: [nodeJS-bluemix.mybluemix.net](//nodeJS-bluemix.mybluemix.net)

