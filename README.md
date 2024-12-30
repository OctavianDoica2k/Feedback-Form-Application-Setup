# Feedback Form Management System

A comprehensive feedback form management system built with React, TypeScript, and Supabase.

## Features

- 📝 Create custom feedback forms with multiple field types
- 📊 Real-time analytics dashboard
- 🎯 Sentiment analysis for responses
- 📱 Responsive design
- 🔒 Secure data handling

## Tech Stack

- React 18
- TypeScript
- Supabase
- Tailwind CSS
- Chart.js
- Zustand
- Lucide Icons

## Getting Started

1. Clone the repository
```bash
git clone [your-repo-url]
cd feedback-form-app
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Create a `.env` file in the root directory:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server
```bash
npm run dev
```

## Environment Setup

1. Create a Supabase project
2. Run the migrations in the `supabase/migrations` folder
3. Set up the environment variables

## Security Considerations

- Never commit `.env` files
- Use Row Level Security (RLS) policies
- Implement proper authentication
- Regularly update dependencies

## License

MIT

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request
