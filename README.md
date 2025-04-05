# 🚀 AI Content Generator SaaS

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-13-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-5.0-blue?style=for-the-badge&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-181818?style=for-the-badge&logo=supabase&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-008CDD?style=for-the-badge&logo=stripe&logoColor=white)

</div>

## 📝 Overview

AI Content Generator is a powerful SaaS platform that enables users to generate high-quality marketing content using advanced AI technology. Perfect for freelancers, small businesses, and marketers who need to create engaging content quickly and efficiently.

## ✨ Key Features

- 🤖 **AI-Powered Generation**
  - Blog posts
  - Ad copy
  - Product descriptions
  - Social media content

- 🎨 **Content Templates**
  - Pre-built templates for common content types
  - Customizable output formats
  - Tone and style adjustments

- 🔐 **User Authentication**
  - Secure login/signup
  - OAuth integration (GitHub, Google)
  - Protected routes

- 💳 **Subscription Tiers**
  - Free tier with basic features
  - Pro tier with unlimited generations
  - Secure payment processing

- 📤 **Export Options**
  - Copy to clipboard
  - Export as Markdown
  - Export as plain text

## 🛠️ Tech Stack

### Frontend
- **Framework**: Next.js 13+ (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **State Management**: React Context

### Backend
- **API Routes**: Next.js API
- **Database**: Supabase (PostgreSQL)
- **Authentication**: Supabase Auth
- **AI Integration**: OpenAI API
- **Payments**: Stripe

### Development
- **Package Manager**: npm
- **Code Quality**: ESLint
- **Formatting**: Prettier
- **Version Control**: Git

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn
- Supabase account
- OpenAI API key
- Stripe account

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ahmed86-star/AI-Powered-Content-Generator-SaaS.git
   cd ai-content-generator
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.local.example .env.local
   ```
   Fill in your environment variables:
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

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:3000`

## 📁 Project Structure

```
ai-content-generator/
├── src/
│   ├── app/                 # Next.js 13+ app directory
│   │   ├── dashboard/      # Dashboard pages
│   │   ├── auth/          # Authentication pages
│   │   └── account/       # Account management
│   ├── components/         # Reusable components
│   ├── lib/               # Utility functions
│   │   ├── supabase.ts    # Supabase client
│   │   ├── stripe.ts      # Stripe configuration
│   │   └── openai.ts      # OpenAI setup
│   └── utils/             # Helper functions
├── public/                # Static assets
└── package.json          # Dependencies
```

## 🔒 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| `NEXT_PUBLIC_SUPABASE_URL` | Supabase project URL | Yes |
| `NEXT_PUBLIC_SUPABASE_ANON_KEY` | Supabase anonymous key | Yes |
| `OPENAI_API_KEY` | OpenAI API key | Yes |
| `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY` | Stripe publishable key | Yes |
| `STRIPE_SECRET_KEY` | Stripe secret key | Yes |
| `STRIPE_WEBHOOK_SECRET` | Stripe webhook secret | Yes |

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Supabase](https://supabase.io/)
- [OpenAI](https://openai.com/)
- [Stripe](https://stripe.com/)

## 📞 Support
open an issue in the GitHub repository.

---

<div align="center">
Made with ❤️ by https://ahmed-dev1.com/ (https://github.com/ahmed86-star)
</div>
