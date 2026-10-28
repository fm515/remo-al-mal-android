Remo Al-Mal

A digital marketplace for buying and selling digital products.

Project Goals

- Arabic and English language support.
- Light and dark themes.
- User registration and login.
- Browse and search digital products.
- Seller product management.
- Secure digital product downloads.
- Order and payment status tracking.
- Responsive, mobile-friendly design.

Backend

The project uses an existing Supabase backend.

- Authentication: Supabase Auth.
- Database: Existing Supabase tables.
- Storage: Private digital-product-files bucket.
- Security: Row Level Security (RLS).

Android Build

The goal is to produce a testable Android APK using a verified Android build workflow.

The APK is not considered ready until the build succeeds and the app is tested on a real device.

Security Notes

- Never commit service_role or sb_secret keys.
- Never store private credentials in the Android app.
- Keep digital product files private.
- Verify payments on the server before granting downloads.

Project Status

Development in progress.
