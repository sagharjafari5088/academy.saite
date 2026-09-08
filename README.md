
# Academy Site 1.42.0

Modular WordPress Academy backend designed to be presentation-agnostic and consumed by Elementor HTML Widget templates.

## Important
- Do not put business logic or CSS into Elementor templates.
- Do not rename existing `{{markers}}` in the HTML contract.
- Module changes should be additive and isolated.
- Configure SMS.ir under Settings → Academy SMS.
- Configure ZarinPal under Settings → Academy Payment.
- Use Academy Site → Academy Site Modules to inspect module loading status.

See `docs/final-spec.md` and `docs/ELEMENTOR-HTML-MASTER.md`.


## Central Academy Administration
The `Academy Site` admin menu is the single management entry point. Student profiles support personal data, wallet credit/debit with optional expiry, course enrollment grant/revoke, certificates, events and related account activity. Instructors, courses and events can be created and edited from Academy Site without depending on Elementor presentation. CRM, SMS.ir, commerce, certificates and wallet management remain backed by their respective modules.
