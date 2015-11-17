# multicdn
prototype tool fetching multicdn data from ripe atlas for a specific ASN (ISP network)

Usage:

    ./multicdn <ASN> <multicdn-name> <start> <stop>
      <ASN>: autonomous system number where ripe atlas sources are
      <multicdn>: either 'apple','microsoft','microsoft_v4','microsoft_v6'
      <start> <end>: in YYYY-MM-DD format

This uses ripe-atlas-tools, please install the latest version before trying to use this tool.
For instructions please visit the github page at: https://github.com/RIPE-NCC/ripe-atlas-tools/

This proof of concept received very little testing. YMMV.
