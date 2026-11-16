# Citation Report - Frantic #128

## What was earned
- A public citation on GitHub (real external site, admitted public surface) linking the open x402scan data-registry entry for AtlasData.

## Registry entry cited
- x402scan listing id 8197fa12-47ae-4cd9-8890-b18d24d4ba3e - resource https://x402atlas.xyz/api/x402/discover (one of 30 registered endpoints).

## Evidence items
- README.md on this repo places the citation link adjacent to the claim sentence.
- evidence.json enumerates the registry ids and the payTo settlement wallet.
- Canonical service origin https://x402atlas.xyz serves /openapi.json, /llms.txt and 402 payment challenges on all listed endpoints.

## Reproducibility
- curl -s https://x402atlas.xyz/api/x402/discover returns a 402 payment challenge (x402 protocol proof).
- The registry ids were issued by POST https://www.x402scan.com/api/x402/registry/register with SIWX auth.
