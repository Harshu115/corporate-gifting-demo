# Giftora — Corporate Gifting Demo

Client-ready static demo for a corporate gifting website.

## Included
- Responsive corporate gifting storefront
- Product catalogue cards
- Bulk enquiry form
- Supabase database submission
- Live admin enquiry dashboard
- WhatsApp CTA
- Vercel-ready static deployment

## Supabase
The frontend uses the Supabase project configured for the demo and the `corporate_enquiries` table.

For a production release:
- Enable Supabase Auth for admin users.
- Remove anonymous SELECT access to all enquiries.
- Keep only the publishable/anon key in the browser; never expose service_role.
- Add spam protection, server-side validation and notification automation.

## Deploy on Vercel
Import this GitHub repository into Vercel:
`https://github.com/Harshu115/corporate-gifting-demo`

Framework preset: Other / static.
Build command: none.
Output directory: root.

## Client demo flow
1. Open the website.
2. Select a product and submit a bulk enquiry.
3. The enquiry is inserted into Supabase.
4. Scroll to Admin.
5. Click Refresh to see the enquiry.

Repository: https://github.com/Harshu115/corporate-gifting-demo
