Pre-requisite: You need to have [node.js](https://nodejs.org/en/) installed on your machine.

# Install and run your first application with iexec

In this tutorial you will learn how to install and use the iexec software development kit (iexec-sdk).

You will create your first application HelloWorld that does a very simple off-chain computation (print 'helloworld').

Then you will create a smart contract and deploy it on the Ethereum blockchain.

At the end of the tutorial, you will see how your smart contract can now interact with iExec oracle.

Let's get started!

`npm -g install iexec`{{execute}}

check iexec help:

`iexec --help`{{execute}}

and iexec version:

`iexec --version`{{execute}}

# iexec init

This initializes a basic iexec dapp for you. Let's initialize the iexec "hello-world" dapp:

`iexec init hello-world`{{execute}}

# iexec migrate

This call truffle to migrate the dapp on a blockchain:

`iexec migrate --network ropsten`{{execute}}
