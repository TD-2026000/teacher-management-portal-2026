TEACHER MANAGEMENT PORTAL — PWA PACKAGE

Included:
- index.html: the latest Teacher Portal HTML supplied in this conversation
- manifest.json: installable app metadata
- sw.js: app-shell service worker; Supabase/API requests are deliberately not cached
- icons/: 192px and 512px app icons

NEXT DEPLOYMENT STEPS
1. Create a new public GitHub repository (for example: teacher-management-portal).
2. Upload the CONTENTS of this folder to the repository root (index.html must be at the root).
3. In GitHub: Settings > Pages > Deploy from a branch > main > /(root) > Save.
4. Wait for GitHub Pages to publish the HTTPS site.
5. Update SUPABASE_REDIRECT_URL in index.html to the new exact Pages URL.
6. In Supabase > Authentication > URL Configuration, add the new site URL to Site URL / Redirect URLs as appropriate.
7. Test sign-in, sign-up, payment submission, admin verification, and install prompt on devices.

IMPORTANT
- Do not delete or recreate any Supabase tables or records.
- The app still needs internet for Supabase login, payments, schedules, and synced data.
- This package is a PWA for Android, Windows, Mac, and iPad/iPhone browser installation.
- Publishing in Google Play Store is a separate later step and requires a Play developer account.
- The previous GitHub Pages URL is still present in the HTML as the Supabase auth redirect until the new repository URL is chosen. Do not deploy for teacher use until that URL is updated and tested.
