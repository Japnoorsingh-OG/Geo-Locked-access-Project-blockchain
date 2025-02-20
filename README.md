# Geo-Locked-access-Project-blockchain
# Geo Locked Access

## Description
Geo Locked Access is a smart contract that allows content access based on a user's geographic location. Only users from approved regions can unlock the content.

## Smart Contract Address
`0x6bc734b18f9DaAD7a8eB44b9550a1c5735fe6Ef3`

## Features
- Owner can define allowed regions.
- Users must provide a region hash to request access.
- Access is granted only if the region is allowed.
- Simple verification mechanism to ensure privacy.

## How to Use
1. Add allowed region hashes using `addAllowedRegion(bytes32 regionHash)`.
2. Users request access using `requestAccess(bytes32 regionHash)`.
3. Check access status with `hasAccess(address user)`.

## License
MIT

