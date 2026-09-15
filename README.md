# FreshPress Dry Clean & Iron

Mobile-first React + Vite business website for FreshPress.

## Run
1. Install Node.js LTS.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. For deployment run `npm run build` and deploy the `dist` folder.

## Included
- Responsive customer website
- Services and editable demo pricing
- Booking form + live price calculation
- Unique order IDs and browser demo tracking
- WhatsApp pre-filled booking
- Offers/coupon presentation
- Contact section
- Order tracking UI
- Basic owner admin price editor
- SEO metadata
- Production integration placeholders

## Production checklist
Connect a real database/backend (Supabase/Firebase/etc.), secure admin authentication, server-side order creation, Razorpay/other gateway checkout + webhook verification, real WhatsApp Business API, server-side coupon validation, and a real Google Maps embed. Never store card numbers, CVV or UPI PINs.

## Easy configuration
The demo WhatsApp and phone values are at the top of `src/main.jsx`. For production, move them to environment variables/backend settings.
