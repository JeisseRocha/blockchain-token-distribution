# blockchain-token-distribution
Blockchain project to issue an Ethereum ERC20 token on an Ethereum testnet and provide a code-based mechanism to perform basic token distributions.


### Environment variables ###

You will need a .env file to hold some important keys.
On the main folder create a file called '.env' and put the following info:

```
INFURA_TOKEN=
CONTRACT_ADDRESS=
OWNER_ADDRESS=
SUPER_SECRET_PRIVATE_KEY=
```

## Easy way to run this application: use Docker Compose ##

to run a docker-compose instance:

```$docker-compose up```


___________________________________________________________


## More detailed way to run this application ##

To run a deterministic wallet:

```$node crypto/wallet.js```

### Sorting out dependencies ###

To manage dependencies we are using npm, so to install all dependencies run:

```$npm install```


### Docker Commands ###

check what docker containers are running

```$docker ps```

check what images I have built

``` $docker image ls ```

remove all docker images/networks etc.

``` $docker system prune -a -f ```

build an image

``` $docker build -t nci/erc20 . ```

run 

``` $docker run --name erc20 nci/erc20 ```
