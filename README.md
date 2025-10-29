# KaranShah-git / PRODIGY_WD__0.4
🌐 Responsive Portfolio Website with React & Supabase Authentication
Project Overview
A modern, responsive single-page portfolio website built with React, TypeScript, and Supabase for authentication. 
Features smooth scroll navigation, real-time authentication state management, and a sleek, animated UI optimized for desktop and mobile.

🛠 Technology Stack
Frontend: React 18.3.1, TypeScript 5.5.3, Vite 5.4.2, Tailwind CSS 3.4.1, Lucide React icons
Backend & Auth: Supabase (@supabase/supabase-js 2.57.4), PostgreSQL
Development Tools: ESLint, TypeScript ESLint, PostCSS, Autoprefixer

📁 Project Structure
text
src/
├── components/       # UI components (About, Contact, Hero, Navigation, Projects, Skills, AuthModal)
├── contexts/         # Authentication state (AuthContext)
├── lib/              # Supabase client config
├── App.tsx           # Main app component
├── main.tsx          # Entry point
└── index.css         # Global styles
supabase/
└── migrations/       # Database schema migrations.

🔑 Key Features.
Fixed, responsive navigation with scroll-based background changes and active section highlighting
Smooth scrolling with scroll indicators
Supabase-powered authentication: sign up, sign in, sign out, session management
Hero section with gradient背景 and social links
About section with personal intro and highlight cards (Clean Code, Design Focus, Performance)
Projects showcase grid with images, descriptions, tech tags, GitHub and demo links
Skills section with animated proficiency bars and "Always Learning" emphasis
Contact form with validation and success feedback
Responsive design with mobile-first approach and smooth animations

🛡 Security & Database
Supabase user_profiles table for storing user info
Row Level Security (RLS) policies ensuring users can only manage their profiles
Automatic profile creation trigger on user sign up

⚙️ Available Scripts
text
npm run dev        # Start development server  
npm run build      # Production build  
npm run preview    # Preview production build  
npm run lint       # Run linter  
npm run typecheck  # TypeScript type checking.

🎨 Design & Styling
Tailwind CSS utility classes for fast styling<img width="1342" height="847" alt="Screenshot 2025-10-27 214851" src="https://github.com/user-attachments/assets/a47c821d-d04e-4865-a827-86831b5f2a8f" />
<img width="1556" height="812" alt="Screenshot 2025-10-27 214753" src="https://github.com/user-attachments/assets/ba6a3a58-612e-4b14-8f79-f8f2e746bc49" />
<img width="1780" height="814" alt="Screenshot 2025-10-27 214723" src="https://github.com/user-attachments/assets/ce1dcd03-170d-4fa4-84e7-9516c1368b2e" />


https://github.com/user-attachments/assets/67eca1d4-c9bf-4533-b2e6-a7d96aac5a1b


Color scheme combining blue and slate hues for a modern look

Animations: fade-ins, hover effects, progress bars, gradient accents

Mobile-first responsive layout
