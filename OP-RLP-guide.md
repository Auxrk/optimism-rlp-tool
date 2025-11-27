# Manual RLP & Block Analysis Guide for Optimism

This document collects my notes on:
- How to read raw block fields
- How to compute or understand RLP values without writing scripts
- Useful RPC calls (via curl, Postman, or browser-based tools)
- Typical fields and how Optimism modifies them compared to Ethereum Mainnet

Examples include:
- Fetching a block with `eth_getBlockByNumber`
- Understanding hex -> decimal conversion
- Why some RLP components are different in Optimism
