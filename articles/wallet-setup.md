---
title: "Wallet Setup Guide for Stride"
description: "Complete guide to setting up and connecting wallets for Stride liquid staking. Supports Keplr, Leap, Cosmostation, and more."
category: "Getting Started"
readTime: "12 min read"
featured: "no"
tags: ["wallet", "setup", "keplr", "leap", "cosmostation", "trust-wallet", "connection", "getting-started", "installation", "configuration"]
---

# Wallet Setup Guide for Stride

## Table of Contents
1. [Supported Wallets](#supported-wallets)
2. [Keplr Wallet Setup (Recommended)](#keplr-wallet-setup-recommended)
3. [Alternative Wallet Options](#alternative-wallet-options)
4. [Connecting to Stride](#connecting-to-stride)
5. [Network Configuration](#network-configuration)
6. [Troubleshooting Connection Issues](#troubleshooting-connection-issues)
7. [Security Best Practices](#security-best-practices)
8. [Managing Multiple Wallets](#managing-multiple-wallets)

---

## Supported Wallets

Stride supports multiple Cosmos ecosystem wallets. Here's our recommendation order:

### 1. **Keplr Wallet** (Recommended)
- **Best for**: Most users, especially beginners
- **Features**: Full Cosmos ecosystem support, built-in staking, mobile + desktop
- **Platforms**: Chrome/Firefox extension, iOS/Android apps
- **Download**: [keplr.app](https://keplr.app)

### 2. **Leap Wallet**
- **Best for**: Users wanting a modern, streamlined experience
- **Features**: Clean interface, fast transactions, mobile-first
- **Platforms**: Chrome extension, iOS/Android apps
- **Download**: [leapwallet.io](https://leapwallet.io)

### 3. **Cosmostation**
- **Best for**: Mobile users, advanced staking features
- **Features**: Comprehensive mobile support, portfolio tracking
- **Platforms**: iOS/Android apps, Chrome extension
- **Download**: [cosmostation.io](https://cosmostation.io)

### 4. **Trust Wallet**
- **Best for**: Multi-chain users already using Trust Wallet
- **Features**: Simple interface, broad token support
- **Platforms**: Mobile apps
- **Download**: [trustwallet.com](https://trustwallet.com)

---

## Keplr Wallet Setup (Recommended)

### Step 1: Install Keplr

**For Browser (Chrome/Firefox):**
1. Visit [keplr.app](https://keplr.app)
2. Click "Install Keplr for Chrome" or "Install Keplr for Firefox"
3. Click "Add to Chrome/Firefox" in the extension store
4. Pin the extension to your browser toolbar

**For Mobile:**
1. Download from App Store (iOS) or Google Play (Android)
2. Search for "Keplr Wallet"
3. Install the official app by Chainapsis

### Step 2: Create or Import Wallet

#### Creating a New Wallet:

1. **Open Keplr** and click "Create new wallet"
2. **Choose account type**:
   - **Google**: Sign in with Google (easiest)
   - **Mnemonic**: Traditional seed phrase (most secure)
   - **Ledger**: Hardware wallet (most secure)

3. **For Mnemonic option**:
   - Click "Create new mnemonic seed"
   - **Write down your 12 or 24-word seed phrase**
   - Store it securely offline (never digital)
   - Confirm the seed phrase by entering words in order

4. **Create account name and password**
   - Choose a memorable account name
   - Create a strong password
   - Confirm your password

5. **Backup confirmation**
   - Keplr will ask you to confirm your seed phrase
   - Enter the requested words in correct order
   - Complete the verification

#### Importing an Existing Wallet:

1. **Open Keplr** and click "Import existing wallet"
2. **Choose import method**:
   - **Mnemonic**: Enter your seed phrase
   - **Private key**: Enter your private key
   - **Ledger**: Connect your hardware wallet

3. **Enter your information**:
   - Type your seed phrase or private key
   - Create account name and password
   - Confirm the import

### Step 3: Add Networks

Keplr will automatically detect and add supported networks when you visit DApps. To manually add networks:

1. **Visit Stride App** at [app.stride.zone](https://app.stride.zone)
2. **Click "Connect Wallet"** and select Keplr
3. **Approve network additions** when prompted
4. **Common networks to add**:
   - Stride
   - Cosmos Hub (ATOM)
   - Osmosis (OSMO)
   - Celestia (TIA)
   - Dymension (DYM)

### Step 4: Fund Your Wallet

**Getting Your Address:**
1. Open Keplr
2. Select the network (e.g., Cosmos Hub for ATOM)
3. Click "Copy Address"
4. Use this address to receive tokens

**Funding Options:**
- **Centralized exchanges**: Withdraw to your wallet address
- **Other wallets**: Transfer from existing wallets
- **Fiat on-ramps**: Some supported in Keplr directly
- **Cross-chain bridges**: Move tokens between chains

---

## Alternative Wallet Options

### Leap Wallet Setup

1. **Install**: Visit [leapwallet.io](https://leapwallet.io)
2. **Create/Import**: Similar process to Keplr
3. **Connect**: Use WalletConnect or direct connection
4. **Features**: Built-in NFT support, portfolio tracking

### Cosmostation Setup

1. **Install**: Download from [cosmostation.io](https://cosmostation.io)
2. **Create/Import**: Follow wallet creation wizard
3. **Network Selection**: Choose networks to enable
4. **Connect**: Strong mobile support, desktop extension

### Trust Wallet Setup

1. **Install**: Download from [trustwallet.com](https://trustwallet.com)
2. **Enable Cosmos**: Add Cosmos networks in settings
3. **Import/Create**: Standard wallet creation process
4. **Connect**: May require WalletConnect for some DApps

---

## Connecting to Stride

### Step 1: Visit Stride App

1. Go to **[app.stride.zone](https://app.stride.zone)**
2. Ensure you're on the correct website (check URL carefully)
3. The page should load with a "Connect Wallet" button

### Step 2: Connect Your Wallet

1. **Click "Connect Wallet"**
2. **Select your wallet** from the list:
   - Keplr
   - Leap
   - Cosmostation
   - Trust Wallet (via WalletConnect)

3. **Approve the connection**:
   - Your wallet will open
   - Review the connection request
   - Click "Approve" or "Connect"

### Step 3: Approve Network Additions

When connecting for the first time:

1. **Stride Network**: Approve adding Stride network
2. **Other Networks**: Approve networks for tokens you want to stake
3. **Check your wallet**: Verify networks appear in your wallet

### Step 4: Verify Connection

1. **Check wallet icon**: Should show "Connected" in the app
2. **See your address**: Your wallet address should be visible
3. **View balances**: Your token balances should load

---

## Network Configuration

### Required Networks

For full Stride functionality, ensure these networks are added:

| Network | Purpose | RPC Endpoint |
|---------|---------|--------------|
| Stride | Main protocol | Auto-configured |
| Cosmos Hub | ATOM staking | Auto-configured |
| Osmosis | OSMO staking, DEX | Auto-configured |
| Celestia | TIA staking | Auto-configured |
| Dymension | DYM staking | Auto-configured |

### Manual Network Addition

If networks don't auto-configure:

1. **Open wallet settings**
2. **Go to "Manage Networks"**
3. **Add network** with these details:
   - Network name
   - RPC endpoint
   - Chain ID
   - Currency symbol

*Note: Visit [docs.stride.zone](https://docs.stride.zone) for specific network details*

### Network Switching

To switch networks in Keplr:

1. **Click the network name** at the top of Keplr
2. **Select desired network** from dropdown
3. **Wait for network to load**
4. **Verify correct network** is selected

---

## Troubleshooting Connection Issues

### Common Issues and Solutions

#### 1. **Wallet Won't Connect**

**Symptoms:**
- Connection button doesn't work
- Wallet doesn't open
- Connection fails silently

**Solutions:**
- Refresh the page and try again
- Disable other wallet extensions temporarily
- Clear browser cache and cookies
- Ensure wallet extension is enabled and updated
- Try incognito/private browsing mode

#### 2. **Network Not Appearing**

**Symptoms:**
- Can't see Stride or other networks
- Network dropdown is empty
- Balances not loading

**Solutions:**
- Visit [app.stride.zone](https://app.stride.zone) to auto-add networks
- Manually add networks in wallet settings
- Check if networks are enabled in wallet
- Refresh wallet and wait for sync

#### 3. **Transaction Failures**

**Symptoms:**
- Transactions fail to sign
- "Insufficient funds" errors
- Network errors

**Solutions:**
- Ensure you have tokens for gas fees
- Check if you're on the correct network
- Verify RPC endpoints are working
- Try reducing transaction amount
- Wait and retry (network may be congested)

#### 4. **Balance Not Showing**

**Symptoms:**
- Zero balance despite having tokens
- Balances not updating
- Wrong token amounts

**Solutions:**
- Refresh the page
- Switch networks and switch back
- Check if you're viewing the correct network
- Wait for network synchronization
- Verify token addresses are correct

### Advanced Troubleshooting

#### Browser Extension Issues:

1. **Disable other extensions**: Other crypto extensions can conflict
2. **Clear extension data**: Remove and reinstall if necessary
3. **Check browser settings**: Ensure JavaScript is enabled
4. **Update browser**: Use latest version for best compatibility

#### Mobile App Issues:

1. **Update app**: Ensure you have the latest version
2. **Clear app cache**: In phone settings
3. **Restart app**: Force close and reopen
4. **Check internet**: Ensure stable connection

#### Network/RPC Issues:

1. **Try different RPC**: Switch to alternative endpoints
2. **Check network status**: Visit status pages
3. **Wait for maintenance**: Networks may be upgrading
4. **Use different device**: Test on another device

---

## Security Best Practices

### Seed Phrase Security

**Critical Rules:**
- **Never share** your seed phrase with anyone
- **Never store digitally** (no photos, cloud storage, etc.)
- **Write on paper** and store in secure locations
- **Make multiple copies** stored separately
- **Test recovery** before storing large amounts

### Password Security

**Best Practices:**
- Use unique, strong passwords
- Enable biometric authentication if available
- Don't reuse passwords from other services
- Consider password managers
- Log out when not using

### Browser Security

**Recommendations:**
- Only use official wallet extensions
- Verify URLs before entering sensitive info
- Keep browser updated
- Use reputable browsers (Chrome, Firefox, Edge)
- Be cautious with public WiFi

### Transaction Security

**Before Signing:**
- Always verify transaction details
- Check recipient addresses carefully
- Ensure you're on the correct network
- Verify amounts and fees
- Don't rush transactions

### Phishing Protection

**Red Flags:**
- Unsolicited messages asking for seed phrases
- Fake websites with similar URLs
- Urgent requests for wallet information
- Offers that seem too good to be true

**Protection:**
- Bookmark official websites
- Type URLs manually
- Verify links before clicking
- Never enter seed phrases into websites
- Use official support channels only

---

## Managing Multiple Wallets

### Why Use Multiple Wallets?

- **Security**: Separate small amounts from large holdings
- **Testing**: Use test wallet for new protocols
- **Organization**: Different wallets for different purposes
- **Risk Management**: Diversify across wallet types

### Wallet Organization

**Strategy 1: By Amount**
- **Hot wallet**: Small amounts for daily use
- **Cold wallet**: Large amounts for long-term storage
- **Hardware wallet**: Maximum security for significant holdings

**Strategy 2: By Purpose**
- **Trading wallet**: Active trading and DeFi
- **Staking wallet**: Long-term staking positions
- **Governance wallet**: Voting and participation

**Strategy 3: By Network**
- **Cosmos wallet**: Cosmos ecosystem tokens
- **Ethereum wallet**: Ethereum and ERC-20 tokens
- **Multi-chain wallet**: Cross-chain activities

### Best Practices

1. **Clear naming**: Use descriptive names for each wallet
2. **Regular backups**: Keep seed phrases secure for all wallets
3. **Balance monitoring**: Track balances across all wallets
4. **Transaction history**: Keep records of movements between wallets
5. **Security levels**: Match security to wallet value

---

## Getting Help

### Official Support Channels

**Stride Support:**
- **Discord**: [discord.gg/stride](https://discord.gg/stride)
- **Documentation**: [docs.stride.zone](https://docs.stride.zone)
- **Support**: Contact through official channels

**Wallet Support:**
- **Keplr**: [help.keplr.app](https://help.keplr.app)
- **Leap**: Support through their Discord
- **Cosmostation**: [cosmostation.io/support](https://cosmostation.io/support)
- **Trust Wallet**: [trustwallet.com/support](https://trustwallet.com/support)

### Community Resources

**General Help:**
- Cosmos Discord communities
- Reddit: r/CosmosNetwork, r/Stride_Zone
- Twitter: Follow official accounts
- YouTube: Tutorial videos

**Before Asking for Help:**
- Read this guide thoroughly
- Check FAQ sections
- Try basic troubleshooting
- Have specific error messages ready
- Note what you were trying to do

### Security Warnings

**Never Share:**
- Seed phrases or private keys
- Wallet passwords
- Screenshots of sensitive information
- Personal information unnecessarily

**Official Support Will Never:**
- Ask for your seed phrase
- Request remote access to your device
- Ask for wallet passwords
- Demand immediate action

---

## Next Steps

Once your wallet is set up and connected:

1. **Start small**: Test with small amounts first
2. **Learn the interface**: Explore wallet features
3. **Secure your setup**: Double-check security measures
4. **Begin staking**: Start with liquid staking on Stride
5. **Explore DeFi**: Use your LSTs in other protocols
6. **Stay informed**: Join community channels for updates

Remember: Wallet security is your responsibility. Take time to understand and secure your setup properly before handling significant amounts.

---

*Last updated: July 2024*
*Always verify information from official sources and never share sensitive wallet information.*