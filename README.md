# GenerateMyNFT

Browser-based NFT collection generator. Upload layer folders, customize traits and rarity, set conflict rules, generate up to 10,000 unique NFTs, and export as ZIP with ERC-721 metadata.

**Live:** [generatemynft.fun](https://generatemynft.fun)

## Features

- Layer-based generation with drag-and-drop reordering
- Per-trait rarity (auto-redistributes to 100%)
- Conflict rules: traits that cannot or must appear together
- 1/1 art support (PNG and GIF)
- ERC-721 compatible metadata export
- Resizable panels
- 100% client-side — no backend, no data leaves your browser

## Files

- `index.html` — Main generator
- `deploy.html` — Smart contract deploy tool (work in progress)

## Stack

Pure HTML/CSS/JavaScript. CDN dependencies: JSZip, FileSaver.js, ethers.js.
