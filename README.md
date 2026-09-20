# Baniota Workspace notices

Public information and privacy policy for Baniota's personal **gws cli** Google Workspace integration.

This repository is a static notice site only. It must never contain OAuth credentials, Google tokens, email messages, downloaded attachments, private learning notes, lecture content, or application runtime configuration.

## Pages

- `index.html`: integration purpose and user controls
- `privacy/index.html`: access, use, AI inference, storage, retention, deletion, and revocation disclosures
- `styles.css`: local stylesheet, no remote dependencies
- `.nojekyll`: serve plain static content

Planned custom hostname: `hermes.baniota.world`.

The actual integration runs privately. This site has no login, callback handler, form, analytics script or Google API client. Google OAuth consent, permission scopes and automated workflows are configured separately. Publishing this site does not itself complete authentication.

Changes to data processing must be reflected in the privacy notice before they take effect. Preserve existing apex/WWW forwarding and email DNS when attaching the dedicated hostname. Before retiring the site, remove its dedicated DNS record to avoid a dangling custom-domain binding.
