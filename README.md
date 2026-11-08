# personal-finance
My Finance Tracker

One file: `index.html`. Upload it to the repo to deploy.

## v21 (30 Oct 2026)
- Sums typed straight into any amount field (150+30, 3x450, 899-10%), with calculator keys on the phone.
- Income can be marked as being for a later month ("Paid early" on Agency, or the chips on the logbook), so an invoice cleared ahead of time ticks off the right month.
- The SIP corpus is a pot of its own on Investments, with a goal that shows on the Goals page.
- Tax: FIRA status per remittance, advance tax instalments, and a one-file year pack for the CA.
- Security: the cloud copy can be sealed with a passphrase (AES-GCM, key derived on the device), plus an optional PIN lock with auto-lock and background blur.
- Sign in to sync (email magic link or 6-digit code) so Supabase row-level security can be turned on; see SUPABASE-AUTH-PLAN.md for the dashboard steps and order.
- Performance page rebuilt to read at a glance; heroes shaped per page; three fonts; flat ink panels; one date style; one notice at a time; settings sheet; phone logging flow.

Test locally with `?nosync=1` so no load touches the cloud.
