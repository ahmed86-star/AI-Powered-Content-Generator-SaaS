# AI Content Generator

A powerful SaaS platform that allows users to generate high-quality marketing content using AI.

## Features

- 🤖 AI-powered content generation
- 📝 Multiple content templates (Blog Post, Ad Copy, Product Description)
- 🔐 User authentication with Supabase
- 💳 Stripe integration for billing
- 📤 Export to Markdown/Copy
- 💾 Save and view past generations

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS, shadcn/ui
- **Backend**: Next.js API Routes
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **AI**: OpenAI API
- **Payments**: Stripe
- **Hosting**: Vercel

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Copy `.env.local.example` to `.env.local` and fill in your environment variables
4. Run the development server:
   ```bash
   npm run dev
   ```

## Environment Variables

Create a `.env.local` file with the following variables:

```env
# Supabase
NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key

# OpenAI
OPENAI_API_KEY=your-openai-api-key

# Stripe
NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your-stripe-publishable-key
STRIPE_SECRET_KEY=your-stripe-secret-key
STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret
```

## Project Structure

```
/app
  /dashboard    # Dashboard page
  /auth        # Authentication pages
  /account     # Account management
/components    # Reusable components
/lib          # Utility functions and configurations
/utils        # Helper functions
```

## License

MIT
