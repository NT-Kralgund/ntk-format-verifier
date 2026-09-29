NTK V13 verifier deployment

Run INSTALL_NTK_V13.bat first so github_verifier/config.js receives the V13 public key and retained legacy public keys. Upload index.html, that generated config.js, and emblem.png to the root of the configured GitHub Pages branch. Never upload keys/ed25519_private.pem. The phone verifier checks the QR signature only and states that page content was not checked. Use the desktop app to compare a V13 PDF's rendered-page fingerprint.
