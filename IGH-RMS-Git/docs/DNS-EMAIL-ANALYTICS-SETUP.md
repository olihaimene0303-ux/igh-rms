# DNS, Email & Analytics Setup — IGH-RMS

## Domain
Use `igh-rms.com` as the production apex domain. Cloudflare Registrar can register domains at registry/ICANN cost and automatically uses Cloudflare nameservers. If the domain is purchased elsewhere, it can still be onboarded to Cloudflare.

## Website
Cloudflare Pages supports apex custom domains after the domain is added as a Cloudflare zone and its nameservers are configured. The Pages dashboard should be used to add the custom domain; do not rely on a manually-created CNAME alone for an apex domain.

## Email
Primary mailbox: `ighconsulting@igh-rms.com`

For Google Workspace, verify domain ownership, activate Gmail, then publish the MX records supplied by Google's current setup wizard. Configure SPF, DKIM and DMARC before public launch. Do not copy old MX records from examples; use the current values supplied by the Workspace Admin console.

## Analytics
Preferred V1.3 analytics: Cloudflare Web Analytics. It is described by Cloudflare as privacy-first and does not collect or use visitors' personal data. For a Pages project, Web Analytics can be enabled from Workers & Pages > Metrics.

## Privacy
Keep the included Privacy Notice current. If a different analytics service is introduced later, update the notice and implement the relevant consent controls before enabling it.
