
# Dex-Aptos

## Overview

Dex-Aptos is a decentralized exchange (DEX) built on the Aptos blockchain, leveraging the Move programming language to ensure security, efficiency, and scalability. This project provides various smart contract modules to facilitate token swaps, liquidity pools, and trading analytics.

## Features

The project includes several key Move modules, each serving a specific function within the DEX ecosystem:

### 1. `permission.move`

-   Manages user permissions and access control within the DEX.
    
-   Ensures only authorized actions are executed.
    

### 2. `pool.move`

-   Implements liquidity pools for token swapping.
    
-   Allows users to add or remove liquidity.
    
-   Ensures efficient pricing and trade execution.
    

### 3. `pool_backtest_data.move`

-   Provides historical data for liquidity pools.
    
-   Supports backtesting of trading strategies.
    

### 4. `ratio.move`

-   Maintains and calculates token exchange ratios.
    
-   Helps determine fair trade values in the DEX.
    

### 5. `sbalance.move`

-   Manages and tracks token balances.
    
-   Ensures accurate balance accounting across trades.
    

### 6. `token.move`

-   Handles token standards and interactions within the DEX.
    
-   Supports transfers and approvals.
    

### 7. `utils.move`

-   Provides utility functions used across multiple modules.
    
-   Enhances efficiency and code reusability.
    

### 8. `vpt.move`

-   Implements Virtual Price Tracking (VPT) to optimize trading and liquidity management.
    
-   Helps reduce impermanent loss.
    

## Installation & Usage

1.  Clone the repository:
    
    ```
    git clone https://github.com/thuthuy59/dex-aptos.git
    cd dex-aptos
    ```
    
2.  Install the Move CLI and Aptos framework:
    
    ```
    aptos init
    ```
    
3.  Compile the Move modules:
    
    ```
    move build
    ```
    
4.  Deploy contracts on Aptos Testnet:
    
    ```
    aptos move publish --profile testnet
    ```
    

## Contribution

We welcome contributions to improve Dex-Aptos. To contribute:

-   Fork the repository.
    
-   Create a feature branch.
    
-   Submit a pull request with a detailed description of your changes.
    

## License

This project is licensed under the MIT License. See the LICENSE file for details.
