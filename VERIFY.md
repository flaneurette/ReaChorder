## Commit Verification
All commits are GPG-signed with Key ID: : `E73A4164C4E8BACA` or `BFCDF1CC0C66D829`
- First:  Full fingerprint: `FC45 1E17 BBF7 BD92 C215 CEA5 E73A 4164 C4E8 BACA`
- Second: Full fingerprint: `E697 A668 A8D4 0A1C A6AC 4F34 BFCD F1CC 0C66 D829`
- Web commits use GitHub's flow key.
### Verify commits:
```bash
gpg --keyserver keys.openpgp.org --recv-keys BFCDF1CC0C66D829
git log --show-signature
```
Alternative check:
```bash
gpg --keyserver https://flaneurette.com/.well-known/flaneurette.pub --recv-keys BFCDF1CC0C66D829
git log --show-signature
```
Note: GPG may show a trust warning - this is normal until you explicitly trust the key.
### Security
- The Web (flow) interface commits may be less secure if GitHub was compromised at that moment of committing.
- Older packages may have old GitHub signing key, this is expected. GitHub keys rotate often.
- To be certain use this permalink for webcommits: https://github.com/web-flow.gpg
- VERIFY.md GPG key verification files have been added to all packages since 11 January 2026.
- Last update: 2:26PM, GMT-1. 23/02/2026.
