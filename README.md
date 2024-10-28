# IOCs
- LevelBlue (AlienVault) OTX Indicators exported as CSV
- The majority of these IOCs were from second-hand reporting of SMS-based phishing attacks or suspicious emails.
- These will be kept separate from the DNS Blocklist repo.

- See: [LevelBlue OTX for Details](https://otx.alienvault.com/browse/global/pulses?q=tag:%22MalwareMorghulis%22)

# Structure
- Rollup
- 2022
- 2023
- 2024

# Common Filename
- Files will be sorted by yearThe files are CSV exports from OTX. They will follow the format:

**YYYYMMDD-OTX_hash.csv**

- The hash can be used to find the originating pulse: https://otx.alienvault.com/pulse/<OTX_hash>

**Note**: Rollups will contain all the IOCs merged together by year.

# Rollup Filename
- Files in the rollup CSVs will have the following name "**Rollup-YYYY**".
- These have no indication on which pulse report they belong to. It's a simple file merge.

# Disclaimer
1) False-positives are expected in some of the indicator pivots.
2) Report descrption is not available here on Git (see OTX page for reports tagged: "MalwareMorghulis" or search by OTX Pulse Hash indicated in filename)
