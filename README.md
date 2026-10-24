# Nulucre Validation Data

Public cohort snapshots and cryptographic attestations for the [Nulucre Reputation Oracle](https://nulucre.com).

## Cohort: jan2027-v1

| Snapshot | Date | Records | Attested |
|----------|------|---------|----------|
| Baseline | Oct 23, 2026 | 96 | ✅ Stellar pubnet |
| Snapshot 2 | Nov 23, 2026 | — | Scheduled |
| Snapshot 3 | Dec 23, 2026 | — | Scheduled |
| Final | Jan 23, 2027 | — | Scheduled |

Stellar TX: 42549703a5a7109faf89dfce55a2ed3bc90fe3d1cf16897de58ab408f7dbcf1a  
Explorer: https://stellar.expert/explorer/public/tx/42549703a5a7109faf89dfce55a2ed3bc90fe3d1cf16897de58ab408f7dbcf1a

## How to verify

sha256sum score-snapshots-2026-10-23.ndjson
# Must equal: 111456014ae197486be3f5013fd04e4acbf1f4f251be843a8328db2dd4857746

Then confirm the same hash in the Stellar TX above.

## Free public API

GET https://oracle.nulucre.com/cohort  
GET https://oracle.nulucre.com/cohort/jan2027-v1  
GET https://oracle.nulucre.com/cohort/jan2027-v1/attestation  

No key. No payment. No rate limit.

## License

Dataset: CC BY 4.0. Oracle software: proprietary — Nulucre Inc.
