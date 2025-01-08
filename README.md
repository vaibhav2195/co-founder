# CoFounder Connect

A platform connecting technical co-founders with startup founders, built with React, TypeScript, and Supabase.

[![Netlify Status](https://api.netlify.com/api/v1/badges/d3db20-frabjous-tanuki/deploy-status)](https://frabjous-tanuki-d3db20.netlify.app)

## 🚀 Features

- **User Authentication**: Secure email/password authentication system
- **Dual User Types**: Support for both founders and developers
- **Startup Ideas**: Post and browse startup opportunities
- **Application System**: Built-in application process with NDA support
- **Real-time Updates**: Instant notifications and status changes
- **Profile Management**: Detailed user profiles with skills and experience

## 🛠️ Tech Stack

- **Frontend**: React 18 with TypeScript
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **Backend**: Supabase (PostgreSQL + Authentication)
- **Routing**: React Router v6
- **Form Validation**: Zod
- **Deployment**: Netlify

## 🏗️ Project Structure

```
src/
├── components/      # Reusable UI components
├── contexts/        # React context providers
├── lib/            # Utility functions and configurations
├── pages/          # Page components
│   ├── Auth/       # Authentication pages
│   └── ...         # Other page components
└── types/          # TypeScript type definitions
```

## 🚦 Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd cofounder-connect
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   - Create a `.env` file in the root directory
   - Add your Supabase credentials:
     ```
     VITE_SUPABASE_URL=your_supabase_url
     VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
     ```

4. **Start the development server**
   ```bash
   npm run dev
   ```

## 🌟 Key Features Explained

### For Founders
- Post startup ideas with detailed descriptions
- Specify compensation (equity/monetary)
- Review developer applications
- Protect intellectual property with NDAs

### For Developers
- Browse startup opportunities
- Filter by skills and requirements
- Apply to interesting projects
- Accept NDAs when required

## 🔐 Security Features

- Row Level Security (RLS) policies
- Secure authentication flow
- Protected API endpoints
- NDA system for sensitive information

## 🚀 Deployment

The application is deployed on Netlify. You can:
1. View the live site: [CoFounder Connect](https://frabjous-tanuki-d3db20.netlify.app)
2. Transfer to your Netlify account using the claim URL provided in deployment

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For any questions or feedback, please reach out through:
- GitHub Issues
- Project Discussion Board
