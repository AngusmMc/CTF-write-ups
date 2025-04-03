# Challenge 1: Hidden Treasure
**Category**: Forensics  
**Difficulty**: Easy  

## Overview
Given a PNG file called `treasure.png`.

## Solution
1. Ran `exiftool treasure.png` and found a comment: `key=abc123`.
2. Decoded the key with `echo abc123 | base64 -d`.
3. Got the flag: `flag{hidden_in_plain_sight}`.

## Learned
Metadata is sneaky!

**Flag**: `flag{hidden_in_plain_sight}`
