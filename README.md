# -dit-spectrum-bot
Repository name: dit-spectrum-bot (or whatever you want) Description: "AI-powered document intelligence SaaS platform"
# Stripe (REQUIRED FOR PAYMENTS)
STRIPE_SECRET_KEY=sk_live_your_key_here
STRIPE_WEBHOOK_SECRET=whsec_your_webhook_secret_here

# Pricing Plans (Get these from Stripe)
STRIPE_PRICE_STARTER=price_1Xxxxxxxxxxxxxx
STRIPE_PRICE_PRO=price_1Xxxxxxxxxxxxxx
STRIPE_PRICE_ENTERPRISE=price_1Xxxxxxxxxxxxxx

# OpenAI (REQUIRED)
OPENAI_API_KEY=sk-proj-your_openai_key_here

# Your Business Info
BUSINESS_NAME=Your Company Name
BUSINESS_EMAIL=support@yourdomain.com
BUSINESS_URL=https://yourdomain.com

# Security (Generate with: node -e "console.log(require('crypto').randomBytes(32).toString('hex'))")
API_KEY=generate_a_random_32_char_string_here
JWT_SECRET=another_random_32_char_string_here
