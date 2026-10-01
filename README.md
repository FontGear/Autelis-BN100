# Autelis BN100

Unofficial field notes for talking to **Autelis Pool Control for Jandy/Zodiac PDA** (model BN100) over HTTP.

This product emulates a Jandy PDA remote on the RS‑485 bus and exposes a web keypad — not the richer `status.xml` circuit API used by Autelis RS units.

## Read the docs

- [HTML API reference](https://fontgear.github.io/Autelis-BN100/)
- [Source HTML](autelis-bn100-pda-api.html) in this repo

The reference covers `keypad.xml`, `keypad.cgi`, authentication, timing, and how the PDA SKU differs from Autelis RS Pool Control.

On a local network the default hostname is `poolcontrol` (`http://poolcontrol/`).

## Disclaimer

This is independent documentation from observed device behavior. It is not affiliated with Autelis, Jandy, or Zodiac.
