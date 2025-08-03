---
title: "Troubleshooting Guide - Stride Liquid Staking"
description: "Solutions to common issues with Stride liquid staking, wallet connections, transactions, and rewards."
category: "Getting Started"
featured: "yes"
readTime: "20 min read"
tags: ["troubleshooting", "problems", "solutions", "errors", "connection-issues", "transactions", "staking", "unstaking", "rewards", "wallet-problems", "support"]
---

# Troubleshooting Guide - Stride Liquid Staking

## Quick Reference

**Emergency Contacts:**
- **Stride Discord**: [discord.gg/stride](https://discord.gg/stride)
- **Support**: Use #support channel in Discord
- **Documentation**: [docs.stride.zone](https://docs.stride.zone)

**Before Starting:**
- Don't panic - most issues are easily resolved
- Try basic solutions first
- Take screenshots of error messages
- Note exactly what you were doing when the issue occurred

---

## Table of Contents

1. [Connection Issues](#connection-issues)
2. [Transaction Problems](#transaction-problems)
3. [Staking Issues](#staking-issues)
4. [Unstaking Problems](#unstaking-problems)
5. [Reward Issues](#reward-issues)
6. [Wallet Problems](#wallet-problems)
7. [Network Issues](#network-issues)
8. [Token Display Issues](#token-display-issues)
9. [DeFi Integration Issues](#defi-integration-issues)
10. [Emergency Procedures](#emergency-procedures)

---

## Connection Issues

### Problem: Cannot Connect Wallet to Stride

**Symptoms:**
- "Connect Wallet" button doesn't work
- Wallet doesn't open when clicking connect
- Connection fails silently

**Solutions:**

#### Quick Fixes:
1. **Refresh the page** and try again
2. **Disable other wallet extensions** temporarily
3. **Clear browser cache** and cookies
4. **Try incognito/private browsing** mode
5. **Check wallet extension** is enabled and updated

#### Advanced Solutions:
1. **Update your browser** to the latest version
2. **Disable ad blockers** that might interfere
3. **Try a different browser** (Chrome, Firefox, Edge)
4. **Reinstall wallet extension**:
   - Remove extension
   - Restart browser
   - Reinstall from official source
   - Restore wallet with seed phrase

#### Still Not Working?
- Check if [app.stride.zone](https://app.stride.zone) is down
- Try from a different device
- Contact support with browser/wallet details

### Problem: Wallet Connects But Networks Missing

**Symptoms:**
- Wallet connects but can't see Stride network
- Missing networks in wallet dropdown
- Balances not loading

**Solutions:**
1. **Auto-add networks**:
   - Visit [app.stride.zone](https://app.stride.zone)
   - Allow network additions when prompted
   - Refresh wallet

2. **Manual network addition**:
   - Open wallet settings
   - Add Stride network manually
   - Use official RPC endpoints

3. **Reset network settings**:
   - Remove problematic networks
   - Clear wallet cache
   - Re-add networks

---

## Transaction Problems

### Problem: Transactions Fail to Sign

**Symptoms:**
- Wallet opens but transaction doesn't sign
- "Transaction failed" error
- Wallet freezes during signing

**Solutions:**

#### Check Transaction Details:
1. **Verify amounts** are correct
2. **Check you have enough tokens** for gas fees
3. **Ensure you're on the correct network**
4. **Verify recipient addresses**

#### Common Fixes:
1. **Increase gas fees**:
   - Set gas to "High" in wallet
   - Manually increase gas limit
   - Wait for network congestion to clear

2. **Check network connectivity**:
   - Test internet connection
   - Try different RPC endpoint
   - Switch networks and back

3. **Wallet issues**:
   - Close and reopen wallet
   - Restart browser
   - Clear wallet cache

### Problem: Insufficient Funds Error

**Symptoms:**
- "Insufficient funds" despite having tokens
- Can't complete transactions
- Gas estimation failures

**Solutions:**
1. **Check gas token balance**:
   - Need native tokens for gas (ATOM, OSMO, etc.)
   - Small amounts needed (usually $1-5 worth)
   - Get gas tokens from exchanges or DEXs

2. **Verify correct network**:
   - Make sure you're on the right network
   - Check token is on the expected network
   - Switch networks if needed

3. **Reduce transaction amount**:
   - Leave buffer for gas fees
   - Try smaller test transaction first
   - Account for network fees

### Problem: Transactions Stuck or Pending

**Symptoms:**
- Transaction shows "Pending" for a long time
- No confirmation after 10+ minutes
- Transaction appears successful but doesn't complete

**Solutions:**
1. **Wait for network confirmation**:
   - Cosmos networks can take 5-10 minutes
   - Check network status pages
   - Be patient during high congestion

2. **Check transaction status**:
   - Use block explorer to verify transaction
   - Look up transaction hash
   - Confirm transaction was broadcast

3. **If truly stuck**:
   - Try sending a new transaction with higher gas
   - Contact support with transaction hash
   - Wait for network resolution

---

## Staking Issues

### Problem: Cannot Stake Tokens

**Symptoms:**
- Staking button doesn't work
- Transaction fails when trying to stake
- Tokens don't appear in staking interface

**Solutions:**

#### Pre-requisites Check:
1. **Verify token availability**:
   - Check token is supported by Stride
   - Ensure you have tokens on the correct network
   - Confirm tokens are not already staked elsewhere

2. **Check minimum requirements**:
   - No minimum staking amount
   - But need enough to cover gas fees
   - Consider transaction costs vs. stake amount

#### Common Solutions:
1. **Network issues**:
   - Switch to correct network in wallet
   - Refresh Stride app
   - Wait for network sync

2. **Token issues**:
   - Verify token balance is correct
   - Check if tokens are locked/vesting
   - Ensure tokens are transferable

3. **Wallet connectivity**:
   - Reconnect wallet
   - Approve all network additions
   - Check wallet permissions

### Problem: Staking Transaction Succeeds But No LSTs Received

**Symptoms:**
- Transaction shows as successful
- Tokens deducted from wallet
- No liquid staking tokens received

**Solutions:**
1. **Wait for processing**:
   - LSTs can take 5-10 minutes to appear
   - Check transaction on block explorer
   - Refresh wallet and Stride app

2. **Check correct network**:
   - LSTs appear on Stride network
   - Switch to Stride network in wallet
   - Add LST token to wallet if needed

3. **Verify transaction details**:
   - Check transaction hash on explorer
   - Confirm transaction was successful
   - Look for LST minting events

### Problem: Staking Rewards Not Accruing

**Symptoms:**
- LST balance not increasing
- No rewards visible
- Rewards lower than expected

**Solutions:**
1. **Understand reward mechanics**:
   - Rewards accrue to LST exchange rate
   - Not visible as separate balance
   - Check LST value vs. underlying token

2. **Check reward rates**:
   - Rewards compound automatically
   - Rates vary by network and time
   - Compare on Stride app dashboard

3. **Verify staking is active**:
   - Check on Stride app
   - Confirm LSTs are in your wallet
   - Ensure you haven't unstaked accidentally

---

## Unstaking Problems

### Problem: Cannot Unstake LSTs

**Symptoms:**
- Unstaking button doesn't work
- Transaction fails during unstaking
- LSTs not recognized for unstaking

**Solutions:**
1. **Check LST balance**:
   - Verify you have LSTs to unstake
   - Ensure you're on Stride network
   - Check LST token address is correct

2. **Try different unstaking methods**:
   - **Direct unstaking**: Through Stride app
   - **DEX trading**: Sell LSTs on Osmosis
   - **Arbitrage**: Use price differences

3. **Network issues**:
   - Check Stride network connectivity
   - Verify RPC endpoints working
   - Try during different network conditions

### Problem: Long Unstaking Times

**Symptoms:**
- Unstaking takes longer than expected
- Unbonding period seems extended
- Confused about timeline

**Solutions:**
1. **Understand unbonding periods**:
   - ATOM: 21 days
   - OSMO: 14 days
   - TIA: 21 days
   - These are blockchain-set, not Stride-set

2. **Alternative solutions**:
   - **Sell on DEX**: Immediate liquidity
   - **Use as collateral**: In lending protocols
   - **Provide liquidity**: In LST/token pools

3. **Track unstaking progress**:
   - Check Stride app dashboard
   - Monitor unbonding completion date
   - Set calendar reminders

### Problem: Unstaking Fails to Complete

**Symptoms:**
- Unbonding period ends but tokens not claimable
- "Claim" button doesn't work
- Tokens stuck in unbonding

**Solutions:**
1. **Check if claim is ready**:
   - Verify unbonding period is complete
   - Check exact timing (hours matter)
   - Refresh app and wallet

2. **Try claiming multiple times**:
   - Network issues can cause failures
   - Try different gas settings
   - Wait and retry

3. **Check for network issues**:
   - Verify all networks are functioning
   - Check if there are upgrade/maintenance periods
   - Contact support if persistent

---

## Reward Issues

### Problem: Rewards Not Showing

**Symptoms:**
- LST balance not increasing
- No rewards visible anywhere
- Confused about reward distribution

**Solutions:**
1. **Understand Stride rewards**:
   - Rewards accrue to LST value, not balance
   - Check LST exchange rate vs. underlying token
   - Rewards compound automatically

2. **Check reward tracking**:
   - Use Stride app dashboard
   - Compare LST value over time
   - Track exchange rate changes

3. **Verify staking is active**:
   - Confirm LSTs are in your wallet
   - Check you haven't accidentally unstaked
   - Ensure tokens are properly staked

### Problem: Rewards Lower Than Expected

**Symptoms:**
- Rewards seem too low
- Different from advertised rates
- Confusion about yield calculations

**Solutions:**
1. **Understand rate variables**:
   - Rates change based on network conditions
   - Advertised rates are estimates
   - Actual rates depend on validator performance

2. **Check Stride fee**:
   - Stride takes 10% of rewards
   - You receive 90% of staking rewards
   - Fee only applies to rewards, not principal

3. **Compare timeframes**:
   - Daily rewards can vary significantly
   - Look at longer-term averages
   - Consider compounding effects

### Problem: Missing Reward Tokens

**Symptoms:**
- Expected reward tokens not appearing
- STRD rewards not visible
- Confusion about reward distribution

**Solutions:**
1. **Check reward token distribution**:
   - Some rewards are in STRD tokens
   - Others accrue to LST value
   - Check both reward mechanisms

2. **Verify token addresses**:
   - Add STRD token to wallet
   - Check correct network (Stride)
   - Ensure proper token display

3. **Claim rewards if needed**:
   - Some rewards need manual claiming
   - Check Stride app for claim buttons
   - Follow reward claiming process

---

## Wallet Problems

### Problem: Wallet Showing Wrong Balance

**Symptoms:**
- Balance shows as zero despite having tokens
- Incorrect token amounts
- Balances not updating

**Solutions:**
1. **Refresh wallet**:
   - Close and reopen wallet
   - Refresh browser page
   - Switch networks and back

2. **Check network settings**:
   - Verify you're on correct network
   - Check RPC endpoints are working
   - Try different RPC if available

3. **Sync issues**:
   - Wait for wallet to sync
   - Check internet connection
   - Try different device

### Problem: Wallet Won't Open or Load

**Symptoms:**
- Wallet extension doesn't open
- Wallet loads but shows errors
- Wallet freezes or crashes

**Solutions:**
1. **Browser issues**:
   - Restart browser
   - Clear browser cache
   - Update browser to latest version

2. **Extension issues**:
   - Disable and re-enable extension
   - Update extension
   - Reinstall if necessary

3. **System issues**:
   - Restart computer
   - Check available memory
   - Try different browser

### Problem: Lost Access to Wallet

**Symptoms:**
- Forgot wallet password
- Lost seed phrase
- Wallet won't unlock

**Solutions:**
1. **Password recovery**:
   - Use seed phrase to restore
   - Create new wallet instance
   - Import with seed phrase

2. **Seed phrase recovery**:
   - Check secure backup locations
   - Look for written copies
   - Check password managers

3. **If seed phrase is lost**:
   - **Without seed phrase, funds cannot be recovered**
   - This is a security feature
   - Contact wallet support for verification

---

## Network Issues

### Problem: Network Connectivity Issues

**Symptoms:**
- Can't connect to Stride network
- Transactions timing out
- Network appears offline

**Solutions:**
1. **Check network status**:
   - Visit Stride status pages
   - Check community channels
   - Verify network is operational

2. **RPC endpoint issues**:
   - Try different RPC endpoints
   - Check if default RPC is working
   - Manually configure RPC

3. **Internet connectivity**:
   - Test internet connection
   - Try different network
   - Check firewall settings

### Problem: Slow Transaction Processing

**Symptoms:**
- Transactions take very long time
- Network appears congested
- High gas fees

**Solutions:**
1. **Network congestion**:
   - Wait for congestion to clear
   - Try during off-peak hours
   - Increase gas fees for priority

2. **Optimize transaction settings**:
   - Set gas to "High" or "Fast"
   - Manually increase gas limit
   - Batch transactions if possible

3. **Alternative timing**:
   - Try different times of day
   - Monitor network activity
   - Plan transactions during low usage

---

## Token Display Issues

### Problem: LSTs Not Showing in Wallet

**Symptoms:**
- Liquid staking tokens not visible
- Zero balance despite successful staking
- Wallet doesn't recognize LSTs

**Solutions:**
1. **Add token manually**:
   - Get LST contract address from Stride
   - Add custom token in wallet
   - Verify token details

2. **Check correct network**:
   - LSTs exist on Stride network
   - Switch to Stride network
   - Refresh wallet

3. **Wallet compatibility**:
   - Ensure wallet supports custom tokens
   - Update wallet to latest version
   - Try different wallet

### Problem: Token Values Incorrect

**Symptoms:**
- LST shows wrong USD value
- Token prices not updating
- Inconsistent pricing

**Solutions:**
1. **Price feed issues**:
   - Wallets use different price feeds
   - LST pricing can be inconsistent
   - Check actual exchange rates

2. **Manual price verification**:
   - Check LST value on Stride app
   - Compare with DEX prices
   - Use block explorer for exact values

3. **Wallet settings**:
   - Refresh price data
   - Check price feed sources
   - Update wallet settings

---

## DeFi Integration Issues

### Problem: Cannot Use LSTs in Other Protocols

**Symptoms:**
- DEX doesn't recognize LSTs
- Cannot provide liquidity
- LSTs not tradeable

**Solutions:**
1. **Check protocol support**:
   - Verify protocol supports your LST
   - Check if LST is whitelisted
   - Confirm token integration

2. **Network compatibility**:
   - Ensure you're on correct network
   - Check if cross-chain bridge needed
   - Verify token addresses

3. **Liquidity issues**:
   - Check if trading pairs exist
   - Verify sufficient liquidity
   - Consider alternative protocols

### Problem: High Slippage When Trading LSTs

**Symptoms:**
- Large price impact when trading
- Excessive slippage warnings
- Poor trade execution

**Solutions:**
1. **Increase slippage tolerance**:
   - Set slippage to 2-5%
   - Adjust based on market conditions
   - Split large trades

2. **Use better liquidity sources**:
   - Check multiple DEXs
   - Use aggregators
   - Look for deeper liquidity pools

3. **Timing and size**:
   - Trade smaller amounts
   - Try different times
   - Wait for better liquidity

---

## Emergency Procedures

### If You Think You've Been Hacked

**Immediate Actions:**
1. **Disconnect wallet** from all DApps
2. **Do not make any transactions**
3. **Move funds to new wallet** if possible
4. **Change all passwords**
5. **Contact Stride support immediately**

### If Funds Are Missing

**Investigation Steps:**
1. **Check transaction history** on block explorer
2. **Verify wallet addresses** are correct
3. **Check all networks** for your tokens
4. **Look for unstaking/unbonding** transactions
5. **Review all signed transactions**

### If Smart Contract Issues

**Response Protocol:**
1. **Stop all interactions** with affected contracts
2. **Document the issue** with screenshots
3. **Contact Stride team** via Discord
4. **Wait for official response** before proceeding
5. **Follow official guidance** for resolution

### Emergency Contacts

**Stride Team:**
- **Discord**: [discord.gg/stride](https://discord.gg/stride)
- **Twitter**: [@stride_zone](https://twitter.com/stride_zone)
- **Email**: Use official channels only

**Security Issues:**
- **Report immediately** to security team
- **Do not post publicly** until resolved
- **Follow responsible disclosure** practices

---

## Prevention Tips

### Best Practices
1. **Start small** with test transactions
2. **Keep backups** of all important information
3. **Stay informed** about protocol updates
4. **Monitor your positions** regularly
5. **Use secure networks** and devices

### Regular Maintenance
1. **Update wallets** and browsers regularly
2. **Check transaction history** monthly
3. **Verify balances** across all networks
4. **Backup seed phrases** securely
5. **Monitor for suspicious activity**

### Education
1. **Read documentation** thoroughly
2. **Join community channels** for updates
3. **Learn from others' experiences**
4. **Practice with small amounts** first
5. **Stay current** with protocol changes

---

## Getting Additional Help

### When to Contact Support
- **Multiple solutions attempted** without success
- **Funds at risk** or missing
- **Unusual behavior** not covered in guides
- **Security concerns** or suspected attacks

### How to Contact Support
1. **Join Stride Discord**: [discord.gg/stride](https://discord.gg/stride)
2. **Use #support channel**
3. **Provide detailed information**:
   - What you were trying to do
   - Error messages (screenshots)
   - Transaction hashes
   - Wallet and browser versions
   - Steps already attempted

### What NOT to Share
- **Seed phrases** or private keys
- **Wallet passwords**
- **Personal information** unnecessarily
- **Screenshots** of sensitive data

### Response Times
- **Community support**: Usually within hours
- **Official team**: 24-48 hours typically
- **Emergency issues**: Prioritized response
- **Complex issues**: May require investigation

---

*Last updated: July 2024*

*Remember: Most issues have simple solutions. Stay calm, follow the steps systematically, and don't hesitate to ask for help when needed. The Stride community is here to support you.*