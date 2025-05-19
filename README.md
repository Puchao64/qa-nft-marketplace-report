# QA Report: OpenSea NFT Marketplace

**Manual QA testing report for OpenSea NFT marketplace (UI, flows, and errors)**  
Test type: exploratory  
Platform: https://opensea.io  
Date: May 2025

---

## Step 1: Homepage

**Action:** Opened homepage at opensea.io  
**Result:** Homepage loads correctly, popular collections block is displayed, no visible issues.  
🖼 `screenshots/homepage.png`

---

## Step 2: Search Functionality

**Action:** Searched for "CryptoPunks" in the search bar  
**Result:** Search results display matching collections and items  
🖼 `screenshots/search-bar.png`

---

## Step 3: Collection Filtering

**Action:** Applied filter by category (e.g., Gaming)  
**Result:** Filtered collections loaded correctly  
🖼 `screenshots/filters.png`

---

## Step 4: Collection Page

**Action:** Clicked on a collection (e.g., TGT VIP CARD)  
**Result:** Collection page loads with title, logo, floor price, volume, owners, and other stats  
🖼 `screenshots/collection-page.png`

---

## Step 5: NFT Item Page

**Action:** Clicked on an individual NFT inside the collection  
**Result:** Item page displays image, owner, price, Buy button, and relevant metadata  
🖼 `screenshots/item-details.png`

---

## Step 6: Wallet Connection

**Action:** Clicked “Connect” in the top right corner  
**Result:** Wallet modal opened with multiple connection options (MetaMask, Coinbase, etc.)  
🖼 `screenshots/wallet-connect.png`

---

## Step 7: Language Switcher

**Action:** Checked for language switch options  
**Result:** No switcher found — site available only in English  
ℹ️ _Function not available — no screenshot_

---

### Summary

✅ Core user flows work as expected  
❌ Language switcher not implemented  
🧪 Manual testing confirms stable performance and consistent UI
