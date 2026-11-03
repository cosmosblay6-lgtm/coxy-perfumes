COXY PERFUMES WEBSITE — COMPLETE STARTER PACKAGE

FILES
- index.html: customer-facing perfume shop
- admin.html: private admin sign-in and product management
- config.js: Supabase project URL, publishable key, and WhatsApp number
- styles.css: turquoise website design
- store.js: public product display and WhatsApp ordering
- admin.js: administrator login and product management

IMPORTANT SETUP NOTES
1. This package is configured with the COXY PERFUMES Supabase project and its publishable key.
2. The publishable key is intended for browser use. Never put a Supabase secret key or service_role key in these files.
3. Your admin login email and password are entered only on admin.html. Do not add them to config.js.
4. The Supabase products table and its Row Level Security policies must be configured correctly. The admin account must be registered in public.admins and the existing admin policy/function must allow that signed-in account to manage products.
5. Test the admin page and product actions before sharing the website publicly. If access is denied, review the Supabase RLS policy and is_store_admin() function; do not disable RLS or create public write access.
6. Product images are added using an image URL. Direct image upload to Supabase Storage is not included.
7. Orders are sent through WhatsApp. This starter does not include a shopping cart, online card/mobile-money payment, delivery tracking, or an order database.
8. This is a static website package. It still needs to be uploaded to a static website host. Opening index.html directly on a phone is not a full hosting/deployment test because browser/CDN and database access may behave differently from a hosted website.

WHATSAPP
The order button is configured for 233542704560.

SUPABASE PROJECT
https://pcarpaipqrfcorfrnetp.supabase.co
