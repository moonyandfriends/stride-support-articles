---
title: How to Unstake Tokens
description: Complete guide to unbonding and redeeming your staked tokens from the Stride protocol
category: Liquid Staking
author: Stride Labs
date: 2024-12-19
---

# How to Unstake Tokens

## Table of Contents
- [Overview](#overview)
- [Understanding the Unbonding Process](#understanding-the-unbonding-process)
- [Step-by-Step Unbonding Process](#step-by-step-unbonding-process)
- [Timeline and Important Notes](#timeline-and-important-notes)
- [Tracking Your Unbonding Status](#tracking-your-unbonding-status)
- [Getting Help](#getting-help)

---

## Overview

After liquid staking your tokens and using your stTokens in DeFi, you may want to unstake (unbond) your tokens from Stride. This guide explains the complete unbonding process and important timelines to understand before initiating the process.

**Important:** Unstaking and unbonding are interchangeable terms that mean informing the Stride protocol you want to unlock your tokens and initiate the unbonding period.

---

## Understanding the Unbonding Process

The Stride unbonding process follows these key steps:

### Step 0: Prerequisites
- You must have stTokens in your wallet (e.g., stATOM)
- You can use stTokens in DeFi while deciding when to unbond

### Step 1: Move stTokens to Stride
- Transfer your stTokens from your wallet to the Stride protocol

### Step 2: Initiate Redemption
- Notify Stride you're ready to redeem your stTokens
- Your stTokens are burned and replaced with an unbonding record
- Stride calculates the underlying token amount you'll receive

### Step 3: Epoch Processing  
- Unbonding requests are grouped and processed every 4 days
- This grouping is required due to Cosmos chain limitations (max 7 unbondings per 21-day period)

### Step 4: 21-Day Unbonding Period
- Standard Cosmos unbonding period applies
- You can still earn some rewards during this period from certain integrations

### Step 5: Automatic Token Movement
- Tokens automatically move to Stride's withdrawal account
- Unbonding records are updated

### Step 6: Claiming (Automated)
- Claims are processed automatically
- Transactions show tokens being transferred to user accounts

---

## Step-by-Step Unbonding Process

### Starting the Unbonding Process

1. **Ensure stTokens are in your wallet**
   - Remove stTokens from any DeFi protocols if necessary
   - Confirm you have the amount you want to unbond

2. **Initiate the redeem process**
   - Navigate to the Stride app
   - Select the "Redeem" or "Unbond" option
   - Enter the amount of stTokens to unbond
   - Confirm the transaction

3. **Confirm the transaction**
   - Approve the transaction in your connected wallet
   - Your stTokens will be burned and an unbonding record created

---

## Timeline and Important Notes

### Key Timing Information:
- **Epoch timing:** All unbonding logic occurs at 2PM EST / 19:00 UTC daily
- **Processing frequency:** Unbonding requests are grouped and processed every 4 days
- **Unbonding period:** 21 days from initiation
- **Claiming:** Automated, but tokens aren't claimable until the next 19:00 UTC after unbonding completes

### Example Timeline:
If your tokens finish unbonding at 19:05 on Day 21, they won't be claimable until 19:00 the following day (Day 22).

### During Unbonding:
- You cannot access or trade your tokens
- You may continue earning some rewards from certain integrations
- You cannot reverse the unbonding process once started

---

## Tracking Your Unbonding Status

### Check Unbonding Records:
You can monitor your unbonding status using these endpoints:

- **General epoch unbonding records:** 
  [Stride API - Epoch Unbonding Records](https://stride-fleet.main.stridenet.co/api/Stride-Labs/stride/records/epoch_unbonding_record)

- **Specific user redemption records:**
  Use the Stride API to check your specific unbonding record status

### What to Look For:
- Unbonding record creation
- Current unbonding period progress  
- Automatic claim processing status
- Final token transfer confirmation

---

## Getting Help

If you need assistance with the unbonding process:

- Join our [Discord server](http://discord.gg/stride-zone)
- Open a Support Ticket in the #📩-support-ticket channel
- Check your unbonding status using the API endpoints above
- Allow up to 30 minutes after the claim period for automatic processing

### Common Issues:
- Tokens not appearing after 21 days: Check if the next epoch (19:00 UTC) has passed
- Unbonding record not found: Verify the transaction was successfully submitted
- Questions about timing: Remember all processing happens at daily epochs

---

*Last updated: December 19, 2024*