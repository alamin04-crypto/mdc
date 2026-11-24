# Medical & Diagnostic Center Management System (MDC)

Hospital + Diagnostic Center, single branch.

- `app/` — Medical App (patient app)
- `website/` — Medical Website (patient website)
- `admin/` — Medical Admin Panel (control center)

All three share one Firebase Realtime Database (project `medical-center-1cfc7`,
node `medical-center-v1`), so an Admin update shows live in App/Website and
App/Website data shows live in Admin.

Each folder holds a standalone `index.html`. To serve them, enable GitHub Pages
on the main branch.
