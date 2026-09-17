# IGH-RMS V1.3.1 — Production Launch Plan

## Confirmed target
- Primary domain: `igh-rms.com`
- Primary public mailbox: `ighconsulting@igh-rms.com`
- Website hosting target: Cloudflare Pages
- Analytics target: Cloudflare Web Analytics
- Site status: launch-ready package; live activation still requires account/domain/email ownership actions.

## Launch sequence
1. Register `igh-rms.com` and enable auto-renew.
2. Create/verify Cloudflare account.
3. Add the domain to Cloudflare and configure the Pages project.
4. Deploy this package to Pages.
5. Add `igh-rms.com` as the custom domain.
6. Confirm HTTPS and apex/www canonical routing.
7. Create Google Workspace and mailbox `ighconsulting@igh-rms.com`.
8. Verify the domain and activate Gmail; configure SPF, DKIM and DMARC.
9. Enable Cloudflare Web Analytics.
10. Test the enquiry email link and mailbox receipt.
11. Perform final desktop/mobile browser QA.
12. Record the final live URL, date and QA result.

## Important
This package does not contain credentials, API keys, passwords or third-party secrets. Those must be created in the owner's accounts.
