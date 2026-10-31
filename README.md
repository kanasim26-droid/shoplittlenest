# LittleNest — Modern Organic storefront

A Next.js storefront styled in sage, ivory, sand and forest tones. It displays a preview catalog until the Shopify Storefront API is configured.

## Setup
1. Install dependencies with npm install.
2. Copy .env.example to .env.local.
3. Set NEXT_PUBLIC_SHOPIFY_STORE_DOMAIN to your myshopify.com domain and add a Storefront API access token.
4. Run npm run dev.

Add the same environment variables in Vercel Project Settings → Environment Variables.

## Integration status
- Shopify Storefront API product listing and product detail lookup are implemented.
- Local cart UI is implemented.
- Cart creates a Shopify Storefront API cart and redirects to Shopify secure checkout when configured with real Shopify products.
- Demo catalog is preview-only and cannot be purchased.
- COD, Easypaisa and JazzCash must be configured only if supported by the merchant's Shopify payment setup in Pakistan.
- Blog content syncing, offer countdown administration, sender email, WhatsApp number and custom domain remain to be configured/implemented.

Do not commit .env.local or expose private credentials in chat.