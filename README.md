#Server Side Events with OpenShift

This is just a simple quickstart to go with a [blog post](http://www.html5rocks.com/en/tutorials/eventsource/basics/) on server side events. I did it with the node.js example but it should work with the PHP example on that page as well. 

To use this quick start just do this at the command line on your local machine (assuming you have already configured the rhc command line tools) 

	rhc app create ssedemo nodejs-0.1 --from-code https://github.com/thesteve0/ssedemo_node.github
	
which will spin up node.js, clone this code into the repo on the gear, and then clone the code down to your machine. 

To see the code in action go to:

{appname}-{namespace}.rhcloud.com/see-node.html
