# personal-finance
My Finance Tracker

One file: `index.html`. Upload it to the repo to deploy.

## v25 (24 Nov 2026), the red pen look
- The whole app now follows my brand guidelines. White page, charcoal type, hairline rules, one 4px corner.
- Eleven colours only. Red is kept for the Add button, what is late or over, and three pen marks (the underline under the main figure, the highlighter, the handwritten note).
- Newsreader for titles and big figures, Google Sans Flex for the rest, Caveat for the note.
- The tax pack and the monthly report export in the same style.
- Menu items, page titles, sheet titles, form labels and buttons are in sentence case.
- New icon. Upload `index.html` and the four `FAV` files together.
- No change to data, storage keys, sync, sums or what any button does. Same 92 self tests.

## v21 (30 Oct 2026)
- Sums typed straight into any amount field (150+30, 3x450, 899-10%), with calculator keys on the phone.
- Income can be marked as being for a later month ("Paid early" on Agency, or the chips on the logbook), so an invoice cleared ahead of time ticks off the right month.
- The SIP corpus is a pot of its own on Investments, with a goal that shows on the Goals page.
- Tax: FIRA status per remittance, advance tax instalments, and a one-file year pack for the CA.
- Security: the cloud copy can be sealed with a passphrase (AES-GCM, key derived on the device), plus an optional PIN lock with auto-lock and background blur.
- Sign in to sync (email magic link or 6-digit code) so Supabase row-level security can be turned on; see SUPABASE-AUTH-PLAN.md for the dashboard steps and order.
- Performance page rebuilt to read at a glance; heroes shaped per page; three fonts; flat ink panels; one date style; one notice at a time; settings sheet; phone logging flow.

Test locally with `?nosync=1` so no load touches the cloud.
