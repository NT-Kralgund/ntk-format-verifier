NTK V12 verifier deployment

Run INSTALL_NTK_V12.bat first so github_verifier/config.js receives the public key from this installation. Upload index.html, that generated config.js, and emblem.png to the root of the configured GitHub Pages branch. Never upload keys/ed25519_private.pem. The signed watermark is shown on valid V12 QR scans. The verifier checks signed QR metadata and source-template fingerprint, not subsequent changes to final page images.
