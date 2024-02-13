# AZTEC - How to use oracles

This little tutorial shows how to run a simple NOIR circuit as an Oracle. 

It is a copy of the AZTEC [code-snippets](https://github.com/AztecProtocol/dev-rel/tree/main/code-snippets/how-to-oracles) 

The original tutorial is [AZTEC How to oracles](https://noir-lang.org/docs/how_to/how-to-oracles#step-4---usage-with-noirjs)

## Description

This repo contains 3 parts:

- `packages/app` : a client App displaying the final Proof
- `packages/circuit` : The NOIR circuit with the circuit proof
- `packages/rpc_server` : An RPC server called by the client app

## How to run

- Clone the repo
- run `yarn` to install the modules required
- run `yarn start`, which will run the RPC Server, and then Oracle client app.
- We should see the Proof displayed in the console.


