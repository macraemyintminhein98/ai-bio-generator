# AI Bio Generator

Instantly create creative and personalized Instagram bios with the power of AI. Just provide a prompt about yourself or your niche, and get multiple bio options to choose from.

## Features
- AI-powered bio generation.
- Simple text input for customization.
- One-click copy to clipboard.
- Credit-based system for usage.

## How to Use
1. Enter a prompt describing yourself, your niche, or keywords into the text area.
2. Click 'Generate Bio'.
3. Select and copy your favorite bio.
4. Purchase more credits as needed.

## Setup (Development)
To run this locally, you'll need:
- Node.js & npm/yarn
- An OpenAI API key (or similar)
- A Stripe account for purchasing credits.

1.  **Clone the repository:**
    bash
    git clone https://github.com/apex-slug/ai-bio-generator.git
    cd ai-bio-generator
    
2.  **Install dependencies (for a full Next.js/backend setup):**
    bash
    npm install
    
3.  **Configure API keys:**
    Set your OpenAI API key and Stripe Public/Secret keys in your environment variables.
4.  **Replace placeholders:**
    Update `pk_test_YOUR_STRIPE_PUBLIC_KEY` and `price_12345` in `index.html` with your actual Stripe keys/IDs.
5.  **Run the application (if using Next.js/backend):**
    bash
    npm run dev
    

This `index.html` is a frontend-only representation. A complete application would require a backend to handle API calls to OpenAI and Stripe for security and billing.
