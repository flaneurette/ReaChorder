## Commit Verification
All commits are GPG-signed with Key ID: `E73A4164C4E8BACA`
- Full fingerprint: `FC45 1E17 BBF7 BD92 C215 CEA5 E73A 4164 C4E8 BACA`
- Web commits use GitHub's key: `B5690EEEBB952194`

### Verify commits:
```bash
gpg --keyserver keys.openpgp.org --recv-keys E73A4164C4E8BACA
git log --show-signature
```

Alternative check:
```bash
gpg --keyserver https://flaneurette.com/.well-known/flaneurette.pub --recv-keys E73A4164C4E8BACA
git log --show-signature
```

Note: GPG may show a trust warning - this is normal until you explicitly trust the key.

### Security
- Web interface commits may be less secure if GitHub was compromised at that moment of comitting.
- Older packages may have old Github signing key, this is expected. Github keys rotate often.
- To be certain use this permalink for webcommits: https://github.com/web-flow.gpg
- VERIFY.md GPG key verification files have been added to all packages since 11 January 2026.

