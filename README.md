# Soapblock

A list of Soapbox instances and (eventually) tools for detecting them.

## Files

### [`soapbox.csv`](soapbox.csv)

Blocklist of Soapbox instances in Mastodon import format.

### [`removed.csv`](removed.csv)

List of instances that have been removed from the blocklist, with reasons for removal. Not importable into Mastodon.

## Policy

The sole criteria for inclusion on this list is use of the Soapbox backend or frontend. Instances that migrate to a hard fork of Soapbox which no longer cooperates with the original developer will eventually be removed. Known hard forks:

- [Mangane](https://github.com/BDX-town/Mangane)

## Verifying the list

The comment for each entry on the list contains the domain on which Soapbox was detected. You can visit that domain in a browser or check its [NodeInfo](https://github.com/jhass/nodeinfo) to verify that it is, in fact, running Soapbox. Note that it may be a subdomain of the blocked domain; this is common for instances running Soapbox as an alternate frontend to another Fediverse server.
