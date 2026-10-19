# MR MONJUR Multi-Retailer Starter

## Included
- `index.html` — starter portal
- `style.css` — responsive styling
- `app.js` — slug validation and explanatory preview only
- `supabase/schema.sql` — initial tenant/security schema for review
- `SETUP-BN.md` — Bengali mobile setup notes

## Important limitations
This is a safe starter package, not a complete production-ready multi-tenant commerce system. The shop slug form does not create a real retailer, user, subdomain, order, or database record. The current GitHub Pages shop is not changed by these files.

Do not add a Supabase `service_role` key to browser files. Retailer account provisioning should be performed by a trusted server-side function. Test RLS with separate accounts before moving any live business data.
