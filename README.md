# Next.js Supabase Auth App

This is a Next.js application with Supabase authentication, featuring email/password and Google OAuth sign-in methods.

## Features

- Email/Password authentication
- Google OAuth sign-in
- Protected account page
- Modern UI with Tailwind CSS
- Toast notifications

## Setup

1. Install dependencies:
```bash
npm install
```

2. Create a Supabase project at https://supabase.com

3. Create a `.env.local` file in the root directory with your Supabase credentials:
```
NEXT_PUBLIC_SUPABASE_URL=your_supabase_project_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Set up Google OAuth in your Supabase project:
   - Go to Authentication > Providers
   - Enable Google provider
   - Add your Google OAuth credentials

5. Run the development server:
```bash
npm run dev
```

6. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure

- `/app` - Next.js 13+ app directory
  - `/login` - Login page
  - `/signup` - Sign up page
  - `/account` - Protected account page
  - `page.tsx` - Landing page
- `/lib` - Utility functions and configurations
  - `supabase.ts` - Supabase client configuration

## Technologies Used

- Next.js 14
- Supabase Auth
- TypeScript
- Tailwind CSS
- React Hot Toast
