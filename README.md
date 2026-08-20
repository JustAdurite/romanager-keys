# romanager-keys

Signed key list for [RoManager](https://github.com/JustAdurite/RoManager).

`keys.json` is published by the app and signed with an Ed25519 key that never
leaves the owner's machine. It contains **SHA-256 hashes, not keys**, so nothing
here is usable on its own — and it cannot be forged, because RoManager verifies
the signature before trusting it.

Editing this file by hand will only break the signature and cause every key to
be rejected.
