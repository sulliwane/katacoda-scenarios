
# I Install the iexec-sdk


Pre-requisite: You need to have [node.js](https://nodejs.org/en/) installed on your machine.

`npm -g install iexec`{{execute}}

check iexec help:

`iexec --help`{{execute}}

and iexec version:

`iexec --version`{{execute}}

# Install and run your first application with iexec

Let's get started!

This initializes a basic iexec dapp for you. Let's initialize the iexec "hello-world" dapp:

`iexec init hello-world`{{execute}}

This will populate your directory with a template that can be use for any application.

Your iexec Dapps is composed at the minimum of two parts:

* an offchain app, which can be any kind of legacy application. The offchain app will be executed by the iexec decentralised cloud.
* a smart contract that interfaces your iexec Dapp from Ethereum to the offchain app.

For the rest of this tutorial, we will work with the factorial function.

`iexec init factorial`{{execute}}

Factorial is already installed and deployed in the iexec network. 

You can see the smart contract here (vizualize) 

