---
title: How to Mint IST with stATOM on Agoric
description: Complete guide to minting IST stablecoin using stATOM as collateral on Inter Protocol vaults
category: Integrations
author: Stride Labs
date: 2024-12-19
---

# How to Mint IST with stATOM on Agoric

## Table of Contents
- [Overview](#overview)
- [Understanding Inter Protocol Vaults](#understanding-inter-protocol-vaults)
- [Prerequisites](#prerequisites)
- [A. Depositing Assets to Agoric Chain](#a-depositing-assets-to-agoric-chain)
- [B. Understanding Vaults and Fees](#b-understanding-vaults-and-fees)
- [C. Creating a Vault](#c-creating-a-vault)
- [D. Adjusting a Vault](#d-adjusting-a-vault)
- [E. Closing a Vault](#e-closing-a-vault)
- [Getting Help](#getting-help)

---

## Overview

Inter Protocol on Agoric now supports stATOM as collateral for minting IST, a decentralized stablecoin. This integration allows you to mint IST against your stATOM holdings while continuing to earn staking rewards on your ATOM assets.

**Key Milestone:** stATOM is only the second form of collateral to meet Inter Protocol's rigorous economic and risk standards, joining ATOM as an accepted asset.

---

## Understanding Inter Protocol Vaults

### What are Vaults?
- Inter Protocol's flagship product and IST minting mechanism
- Over-collateralized positions subject to governed parameters
- Users lock collateral to mint corresponding amounts of IST

### Unique Advantages of stATOM
- Preserve staking rewards while minting stablecoins
- Continue earning ATOM staking yields on your collateral
- Maintain exposure to ATOM appreciation

---

## Prerequisites

Before starting, ensure you have:
- An Agoric Smart Wallet (see [creation guide](https://docs.inter.trade/user-how-to/wallet-usage/create-your-agoric-account-and-smart-wallet))
- stATOM tokens in your wallet
- Understanding of vault parameters and liquidation risks
- Some ATOM for transaction fees

---

## A. Depositing Assets to Agoric Chain

### Step 1: Access the Deposit Interface
1. Launch [app.inter.trade](https://app.inter.trade/)
2. Ensure your Agoric Smart Wallet is provisioned
3. Click "Deposit" button for the asset you wish to deposit

### Step 2: Approve Chain Addition (if needed)
You may receive a Keplr prompt to add 'Cosmos Hub':
- Click "Approve" to add the chain to your wallet
- This enables cross-chain transfers

### Step 3: Specify Deposit Amount
1. Enter the amount you wish to deposit
2. Source chain address defaults to native token chain
3. Your Agoric chain address should auto-populate
4. Click "Deposit ATOM" (or relevant token)

### Step 4: Complete IBC Transfer
1. This performs an IBC transfer from source chain to Agoric
2. Approve the IBC transfer transaction in Keplr
3. Select your preferred fee level (Low, Average, High)
4. Click "Approve"
5. Wait for transfer completion - your balance will update

---

## B. Understanding Vaults and Fees

### Fee Structure

#### Minting Fee
- One-time fee charged in IST when minting
- Applied at vault creation and when minting additional IST
- Governed parameter set by Economic Committee

#### Stability Fee  
- Ongoing cost of holding debt position
- Charged in IST as % APY
- Added to IST debt position over time
- Governed parameter set by Economic Committee

#### Liquidation Penalty
- Charged if vault is liquidated due to under-collateralization
- Penalty taken from collateral asset
- Sent to protocol reserve
- Governed parameter set by Economic Committee

### Risk Management
- Monitor collateralization ratio closely
- Maintain adequate buffer above liquidation threshold
- Consider market volatility when setting position size

---

## C. Creating a Vault

### Step 1: Navigate and Connect
1. Visit [app.inter.trade](https://app.inter.trade/)
2. Click "Connect Wallet" in top right
3. If prompted about "Read Only" mode, approve dApp connection in your Agoric Wallet

### Step 2: Initialize Vault Creation
1. Click "Add New Vault"
2. Review and choose collateral type (stATOM should be available)
3. Review vault parameters and current rates

### Step 3: Configure Vault Parameters
1. **Enter collateral amount:**
   - Input the stATOM amount to lock up
   - Click "Max" to use maximum available balance
   - Consider leaving buffer for fees and safety

2. **Enter IST amount to mint:**
   - Input desired IST amount to receive
   - Collateralization percentage auto-calculates
   - Click "Max" to mint maximum IST based on minimum ratio
   - Manual adjustment available for custom ratios

### Step 4: Review and Submit
1. Review vault details in the Vault Summary preview
2. Verify collateralization ratio is safe
3. Click "Create Vault"
4. You'll be prompted to navigate to Agoric Smart Wallet

### Step 5: Approve in Wallet
1. Click "Go To Wallet" to open wallet interface
2. Review the offer details in your Agoric Smart Wallet
3. Click "Approve" on the offer tile
4. Click "Approve" in Keplr pop-up to sign transaction
5. Wait for transaction confirmation

---

## D. Adjusting a Vault

### Available Actions
You can perform single or multiple vault adjustments in one transaction:

#### Deposit (Collateral)
- Add more stATOM collateral
- Increases collateralization ratio
- Improves position safety

#### Withdraw (Collateral)
- Remove collateral to your wallet  
- Decreases collateralization ratio
- Only possible if borrow limit allows

#### Repay (IST)
- Reduce IST debt
- Increases collateralization ratio
- Improves position health

#### Mint More (IST)
- Increase IST debt
- Decreases collateralization ratio
- Only possible within borrow limits

### Adjustment Process
1. Select desired actions and enter amounts
2. Monitor key metrics during adjustment
3. Click "Adjust Vault" in Vault Summary pane
4. Navigate to Agoric Smart Wallet for approval
5. Click "Approve" and sign with Keplr
6. Vault updates automatically after confirmation

---

## E. Closing a Vault

### Closure Process
1. Navigate to your vault in the Vaults dApp
2. Click the vault you wish to close
3. Click "Close Out Vault" button (bottom left)
4. Review closure preview:
   - IST amount to repay
   - Collateral amount to receive back
5. Click "Close out Vault" to confirm
6. Approve in Agoric Smart Wallet
7. Sign transaction in Keplr

### Important Notes
- Vault closure is permanent - no further actions possible
- Ensure you have sufficient IST to repay debt
- All collateral returns to your wallet upon closure

---

## Getting Help

If you need assistance with Inter Protocol vaults:

- Join our [Discord server](http://discord.gg/stride-zone)
- Open a Support Ticket in the #📩-support-ticket channel
- Check [Inter Protocol documentation](https://docs.inter.trade/)
- Review [Agoric wallet creation guide](https://docs.inter.trade/user-how-to/wallet-usage/create-your-agoric-account-and-smart-wallet)

### Additional Resources:
- [Minting IST - PSM](https://docs.inter.trade/user-how-to/minting-ist/minting-ist-psm)
- [Acquiring BLD Tokens](https://docs.inter.trade/user-how-to/wallet-usage/acquiring-bld-tokens)

### Risk Considerations:
- **Liquidation Risk:** Maintain safe collateralization ratios
- **Smart Contract Risk:** Inter Protocol and cross-chain bridge risks
- **Market Risk:** ATOM price volatility affects collateral value
- **Interest Rate Risk:** Stability fees compound over time

---

*Last updated: December 19, 2024*