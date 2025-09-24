# Proof-to-Payout

Escrow releases only when proofs pass.

## Overview

Agent does a task → emits a signed **receipt**.  
Independent **validator** checks it and posts an **ERC-8004 Validation** result on-chain.  
On pass, **ACP** escrow (Base L2) auto-releases funds.  
Anyone can **verify locally** in the browser by hashing the receipt and matching it to the on-chain commitment.
