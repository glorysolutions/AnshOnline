# Ansh Studio & CSC Centre — Complete Website

A responsive Hindi-first customer website for:
- PAN card assistance
- Voter ID assistance
- Income, caste and residence certificate information
- PVC card/printing service information
- Resume Maker with preview and Print / Save as PDF
- Online forms, scheme information, e-KYC assistance where authorized
- WhatsApp contact links

## Publish on GitHub Pages
1. Extract the ZIP.
2. Create a repository at https://github.com/new (e.g. `ansh-csc-website`).
3. Upload `index.html` and `README.md` to the repository root.
4. Open **Settings → Pages**.
5. Under Build and deployment, select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
6. The live URL appears in Settings → Pages.

## Contact details in this project
- WhatsApp: `9644892123` (WhatsApp URL uses India country code 91)
- Address: अंबेडकर चौक, बस स्टैंड, ओड़ेकेरा

## Privacy and production requirements
- GitHub Pages is public static hosting. Never commit customer records, Aadhaar images, signatures, passwords, OTPs, API keys, or other sensitive files.
- The PAN form's WhatsApp option opens a generic inquiry only. It does not put personal form data in the URL and does not automatically attach files; the customer must manually decide what to send.
- Secure upload is intentionally disabled (`SECURE_UPLOAD_ENDPOINT` is blank). GitHub Pages cannot securely receive or store uploaded documents by itself.
- Before enabling document uploads, deploy a private backend and private storage with authentication/authorization, TLS, server-side validation, malware scanning, encryption, audit logging, rate limiting, retention/deletion rules, and appropriate legal/privacy review.
- Do not collect Aadhaar images unless genuinely necessary and permitted for the service. Consider using an authorized PAN application provider's approved workflow instead.
- This is not an official government website and does not guarantee approval or issuance of certificates/cards. Only offer services you are authorized to provide.
