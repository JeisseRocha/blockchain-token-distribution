# blockchain-token-distribution
Blockchain project to issue an Ethereum ERC20 token on an Ethereum testnet and provide a code-based mechanism to perform basic token distributions.


Requirements

    1. Create an Ethereum account and MetaMask wallet
    2. Create an ERC20-compliant, fixed-supply token
    3. Deploy the token contract to the Ethereum Test Net Network
    4. Build a Node.js application to distribute Tokens

Assignment Output:

    * Nanipulation of an Ethereum account and MetaMask wallet. 
    * Ethereum Test Net ETH Address
    * Node.JS application
    * Docker File containing application
    * Docker Hub URL
    * Report


## Run Blockchain Token Distribution ##

To run a deterministic wallet:

```$node crypto/wallet.js```

## Sorting out dependencies ##

when we use a dependency, we have to npm install it

but we can make this simpler by using a package.json file

which remembers the deps.

then, we can install all deps by running:

```$npm install```


### Docker Commands ###

check what docker containers are running

```$docker ps```

check what images I have built

``` $docker image ls ```

remove all docker images/networks etc.

```docker system prune -a -f```

build an image

```$ docker build -t nci/erc20 .```
