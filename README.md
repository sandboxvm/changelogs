# Changelog
## BETA ``#65792``
2021/12/19 (deployable)
## Fixed
* [DNS] Some website DNS were was unavailable.
* [DNS] Users (inside VM networking) are no longer can connect to the physical routers.
* [DNS] Improved our worm attack prevention.
* [DNS] Improved our botnet attack prevention.
* [DNS] (inside VM networking): Users are no longer can attack the local IP addresses.
* [DNS] Improved our DDoS mitigation.
* [DNS] If you cannot reach our servers, that issue has been fixed for now (host-unreach-fix).
* [DNS] Our network has been upgraded. 500MBPS-->1GBPS
* [Soon] The server will have a 1TB storage soon.
* [Sandbox Cloud] Users are no longer be able to connect and edit user permissions of `AD1/share`
* [Sandbox Cloud] Users are no longer be able to delete their files on the share, it will remain unless if asked.
* [Sandbox Cloud] Websocket ratelimits has been implemented. If you exced the websocket_quota than the websocket will respond with a 403.
* [Sandbox Cloud] VMs will use their correct certificates.

## Statistics
As of today we have banned over **40** IP addresses from reaching our networks, `5` of them are botnet connections.

## BETA ``#65791``
2021/12/16 (deployable)
## Fixed
* [DNS] Users where able to connect to the phyiscial router.
