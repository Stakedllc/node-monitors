# node-monitors
Monitoring &amp; health-check scripts for various protocols

Key checks we need to handle:
1. Is the application running? 
2. Is the blockchain adding blocks regularly (i.e. is block height increasing)?
3. Is our version of the blockchain up to date with 1 or more peers(i.e. is our block height the same as others? 
4. Are we producing blocks when we are expected to? 

This should be a standard healthcheck that we can use to alert / start or stop instances, etc. 

We will want to handle these questions for every blockchain we work with, which includes EOS, Cosmos, Ethereum, et al. 

The following sample for Cosmos handles some basics and sends an email: 
https://github.com/Proof-Of-Audit/CosmosValidatorDjango/blob/master/mysite/monitor.py

We have a cosmos node running at: 54.209.118.64:46657



