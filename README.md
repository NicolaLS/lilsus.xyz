# General

Personal website [lilsus.xyz][lilsus.xyz] for:

- Blog
- GPG
- [LUD-16][lud-16]/[LUD-06 payment requests][lud-06] (LNURL)
- [BIP-0353][bip-0353] DNS Payment Instructions for [Silent Payment][silent-payments] Adresses and [BOLT12][bolt-12] offer.

NOTE: lud-06 explicitly says that JSON needs to be returned which implies the mime-type should be application/json, however
on github pages I can't control the mimetype so its application/octet-stream now which seems to work but could technically
break my lnurl setup for clients that actually enforce correct response...(but don't want to setup VPS just for custom lnurl)

[lilsus.xyz]: https://lilsus.xyz
[lud-16]: https://github.com/lnurl/luds/blob/luds/16.md 
[lud-06]: https://github.com/lnurl/luds/blob/luds/06.md
[bip-0353]: https://github.com/bitcoin/bips/blob/master/bip-0353.mediawiki
[silent-payments]: https://github.com/bitcoin/bips/blob/master/bip-0352.mediawiki
[bolt-12]: https://github.com/lightning/bolts/blob/master/12-offer-encoding.md
