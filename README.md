# Soapblock

A list of Soapbox instances and (eventually) tools for detecting them.

## Files

### [`soapbox.csv`](soapbox.csv)

Blocklist of Soapbox instances in Mastodon import format.

### [`removed.csv`](removed.csv)

List of instances that have been removed from the blocklist, with reasons for removal. Not importable into Mastodon.

## Verifying the list

The comment for each entry on the list contains the domain on which Soapbox was detected. You can visit that domain in a browser or check its [NodeInfo](https://github.com/jhass/nodeinfo) to verify that it is, in fact, running Soapbox. Note that it may be a subdomain of the blocked domain; this is common for instances running Soapbox as an alternate frontend to another Fediverse server.
