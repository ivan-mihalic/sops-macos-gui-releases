# SOPS GUI — releases

Signed, notarized builds of **SOPS GUI**, a native macOS app for editing
[SOPS](https://github.com/getsops/sops)-encrypted secrets with age keys.

The source repository is private; this repository exists so the Sparkle
update feed (`appcast.xml`) and the release archives can be fetched without
credentials, which Sparkle requires.

Releases are built, signed and notarized on the author's machine — never in
CI — so the Apple Developer ID certificate and the Sparkle signing key never
leave it.
