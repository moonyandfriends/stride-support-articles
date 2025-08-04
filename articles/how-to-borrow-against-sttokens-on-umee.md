---
title: How to Borrow Against stTokens on Umee
description: Complete guide to supplying stAssets as collateral and borrowing against them on the Umee money market
category: Integrations
author: Stride Labs
date: 2024-12-19
---

# How to Borrow Against stTokens on Umee

## Table of Contents
- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Step 1: Prepare Your stAssets](#step-1-prepare-your-stassets)
- [Step 2: Transfer stAssets to Umee](#step-2-transfer-stassets-to-umee)
- [Step 3: Supply stAssets as Collateral](#step-3-supply-stassets-as-collateral)
- [Step 4: Borrow Against Your Collateral](#step-4-borrow-against-your-collateral)
- [Managing Your Position](#managing-your-position)
- [Getting Help](#getting-help)

---

## Overview

Umee is a cross-chain money market that allows you to supply stAssets (like stATOM) as collateral and borrow other assets against them. This guide walks you through the complete process of borrowing against your stTokens on Umee.

---

## Prerequisites

Before starting, ensure you have:
- stAssets in your wallet (e.g., stATOM, stOSMO)
- Native Umee tokens for transaction fees (0.5 UMEE recommended minimum)
- A compatible wallet (Keplr recommended)
- Understanding of borrowing risks and liquidation mechanics

---

## Step 1: Prepare Your stAssets

### Withdraw from DeFi Protocols
If your stAssets are deployed in other DeFi protocols:

1. Visit [app.osmosis.zone/assets](https://app.osmosis.zone/assets)
2. Find your stAssets in the asset list
3. Click "Withdraw" next to each stAsset
4. Complete the withdrawal to move tokens back to your wallet

### Acquire UMEE Tokens
You'll need UMEE tokens for transaction fees:
- Purchase UMEE tokens on Osmosis or other supported exchanges
- Transfer UMEE to your wallet
- Ensure you have at least 0.5 UMEE for fees

---

## Step 2: Transfer stAssets to Umee

### Navigate to Umee Dashboard
1. Visit [app.umee.cc/#/dashboard/](https://app.umee.cc/#/dashboard/)
2. Connect your wallet
3. Locate the stAsset you want to use as collateral

### Transfer Process
1. Find your desired stAsset (e.g., stATOM) in the available assets list
2. Click "Transfer" next to the asset
3. Enter the amount you wish to send from Stride chain to Umee chain
4. Click "Transfer" 
5. Approve the transaction in your wallet
6. Wait for the cross-chain transfer to complete

---

## Step 3: Supply stAssets as Collateral

### Access the Market
1. Select your stAsset (e.g., stATOM) from the Umee market chart
2. Review the Supply and Borrow charts
3. Check market details and key metrics
4. Verify you have a positive wallet balance after the transfer

### Supply Process
1. Click "Supply" button
2. Enter the amount of stAsset you wish to supply
3. Review the supply details:
   - Supply APY
   - Total supplied amount
   - Your supply position

4. Click "Supply" to confirm
5. Approve the transaction in your wallet
6. Wait for confirmation

---

## Step 4: Borrow Against Your Collateral

### Select Borrowing Asset
1. Choose the asset you want to borrow from the available market
2. You can borrow the same asset (e.g., borrow stATOM against stATOM collateral)
3. Or choose a different supported asset

### Borrowing Process
1. Click "Borrow" next to your chosen asset
2. Enter the amount you wish to borrow
3. **Critical:** Monitor these key metrics:
   - **Borrow Position:** Your total borrowed amount
   - **Supply Position:** Your total supplied collateral
   - **Borrow Limit Used:** Percentage of available borrowing power used

4. Click "Borrow" to proceed
5. Approve the transaction in your wallet

### Safety Considerations
- **Avoid approaching 100% borrow limit usage**
- **Leave buffer room to prevent liquidation**
- **Monitor your position regularly**

---

## Managing Your Position

### Dashboard Overview
After borrowing, your Umee dashboard will show:
- **Supply section:** Your stAsset collateral with outstanding balances
- **Borrow section:** Your borrowed assets with outstanding balances
- Real-time position health and utilization ratios

### Important Monitoring
1. **Borrow Limit:** Direct relationship to supplied collateral amount
2. **Liquidation Risk:** When borrowed amount approaches collateral value
3. **Interest Rates:** Both earning (supply) and paying (borrow)

### Position Management Actions
- **Add more collateral:** Increase borrow limit and improve position health
- **Repay debt:** Reduce borrow utilization and liquidation risk
- **Withdraw collateral:** Only possible if borrow limit allows
- **Borrow more:** Only if borrow limit permits additional borrowing

---

## Getting Help

If you need assistance with Umee borrowing:

- Join our [Discord server](http://discord.gg/stride-zone)
- Open a Support Ticket in the #📩-support-ticket channel
- Check [Umee documentation](https://docs.umee.cc/) for platform-specific questions
- Monitor your positions regularly to avoid liquidation

### Risk Warnings:
- **Liquidation Risk:** Your collateral can be liquidated if borrow limit is exceeded
- **Interest Rates:** Both supply and borrow rates fluctuate based on market conditions  
- **Cross-Chain Risk:** Transfers between chains carry inherent risks
- **Smart Contract Risk:** DeFi protocols have inherent smart contract risks

### Best Practices:
- Keep borrow utilization well below maximum limit
- Monitor position health regularly
- Understand liquidation thresholds
- Have a plan for position management during market volatility

---

*Last updated: December 19, 2024*