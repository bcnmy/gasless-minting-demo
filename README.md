# Gasless-NFT

## Table of Contents
- [Deployed Website url](#deployed-website-url)
- [Deployed Contract Address](#deployed-contract-address)
- [Clone, Install and Build steps](#clone-install-and-build-steps)
  - [Prerequisites](#prerequisites)
  - [Cloning and installing dependencies](#cloning-and-installing-dependencies)
  - [Running the frontend](#running-the-frontend)
  - [Environment variables](#environment-variables)

## Deployed Website url

https://gasless-metatx.vercel.app/

## Deployed Contract Address

`0x954961aAa708423828db1047c320521d25EC31cC`

## Clone, Install and Build steps

### Prerequisites

1. [Git](https://git-scm.com/)
2. [Node JS](https://nodejs.org/en/) (everything was installed and tested under v16.13.0)
3. A Browser with the [MetaMask extension](https://metamask.io/) installed.

<br>

### Cloning and installing dependencies

1. Clone the project repository on your local machine

```
 git clone https://github.com/bcnmy/gasless-minting-demo.git
 cd gasless-minting-demo
```

2. Installing dependencies

-   For contracts -
    ```
    npm install
    ```
-   For client -
    ```
    cd client
    npm install
    ```

### Running the frontend

For running frontend locally run command:

```
cd client
npm run dev
```

### Environment variables

```
ALCHEMY_KOVAN_URL = ''
ACCOUNT_KEY = ''
```
