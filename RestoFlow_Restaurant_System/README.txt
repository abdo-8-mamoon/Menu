RestoFlow setup:
1. Upload index.html and qr_codes/ to GitHub.
2. Run SUPABASE_SETUP.sql in Supabase SQL Editor.
3. Put SUPABASE_URL and the public anon/publishable key in index.html.
4. Do NOT put service_role/secret keys in the HTML.
5. Replace YOUR-GITHUB-USERNAME/YOUR-REPO in the QR URLs before printing.
6. Real card/wallet/online payment requires a secure backend/Edge Function and merchant credentials.
7. The included RLS is demo-friendly; production should add authentication and table/session authorization.
