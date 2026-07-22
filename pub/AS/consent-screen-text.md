# NUUC-Dispatch — OAuth Consent Screen Text

Fields for the GCP Console OAuth consent screen configuration (see
`../../GActionSheet/../NUUC-Dispatch/SETUP.md` for the full provisioning checklist this
belongs to).

## App information
- **App name:** NUUC-Dispatch
- **User support email:** stuart.donaldson@gmail.com
- **App logo:** `icon-128.png` (this folder)

## App domain
- **Application home page:** https://sdonaldson-nl.github.io/NUUC-Static/pub/AS/
- **Application privacy policy link:** https://sdonaldson-nl.github.io/NUUC-Static/pub/AS/privacy/
- **Application terms of service link:** https://sdonaldson-nl.github.io/NUUC-Static/pub/AS/terms/

## Authorized domains
- `github.io`

## Developer contact information
- stuart.donaldson@gmail.com

## Scopes
- `openid`
- `.../auth/userinfo.email`

Both non-sensitive — no Google verification/security review required, even with
publishing status **In production**.

## OAuth 2.0 Client (Web application)
- **Name:** NUUC-Dispatch Web (Spike S1)
- **Authorized JavaScript origins:** `https://sdonaldson-nl.github.io`
- **Authorized redirect URIs:** none (GIS ID-token sign-in, not an auth-code redirect)
