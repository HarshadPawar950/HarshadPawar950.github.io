# harshadpawar950.github.io

Hosts `/.well-known/assetlinks.json` so the Vastu Prop Android app (`com.vastupropsai.app`) opens
https://harshadpawar950.github.io/vastu-prop-test/ full-screen (Trusted Web Activity).

When the app goes on Google Play, ADD the Play App Signing SHA-256 (Play Console → Setup → App signing)
to `sha256_cert_fingerprints`; keep the upload-key fingerprint that is already there.
