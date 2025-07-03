# EasyMed - Healthcare Management Platform

A comprehensive, mobile-first healthcare management platform designed specifically for the Indian healthcare market. EasyMed simplifies medical administration for both patients and healthcare providers.

## 🏥 Features

### Core Functionality
- **Appointment Booking**: Schedule appointments with Indian doctors and specialists
- **Prescription Management**: Track medications with Indian pharmaceutical data
- **Health Records**: Maintain comprehensive medical history and lab results
- **Emergency Services**: Quick access to India's emergency services (108)
- **User Profiles**: Manage personal and emergency contact information

### Technical Features
- **Progressive Web App (PWA)**: Installable on mobile devices
- **Mobile-First Design**: Optimized for Indian smartphone users
- **Offline Capability**: Basic functionality works without internet
- **Real-time Updates**: Live data synchronization
- **Responsive UI**: Works across all device sizes

## 🇮🇳 Indian Localization

- **Emergency Numbers**: Integrated with India's 108 emergency service
- **Healthcare Providers**: Sample data from renowned Indian hospitals (AIIMS, Max, Apollo)
- **Medical Specialists**: Including traditional medicine (Ayurveda) practitioners
- **Contact Format**: Indian phone number format (+91)
- **Locations**: Delhi, Noida, and other major Indian cities
- **Medications**: Common Indian pharmaceutical brands (Paracetamol, Crocin)

## 🚀 Tech Stack

### Frontend
- **React 18** with TypeScript
- **Vite** for build tooling and development
- **Tailwind CSS** for styling
- **shadcn/ui** component library
- **TanStack React Query** for state management
- **Wouter** for routing
- **React Hook Form** with Zod validation

### Backend
- **Node.js** with Express.js
- **PostgreSQL** with Drizzle ORM
- **Neon** serverless database
- **TypeScript** throughout

### PWA Features
- **Service Worker** for offline functionality
- **Web App Manifest** for installation
- **Custom icons** and branding
- **Install prompts** for better user experience

## 📱 Installation

### For Users
1. Visit the website on your mobile device
2. Tap "Install EasyMed" when prompted
3. The app will be added to your home screen
4. Use like a native app

### For Developers

```bash
# Clone the repository
git clone https://github.com/yourusername/easymed-healthcare-app.git
cd easymed-healthcare-app

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Add your database URL and other secrets

# Run database migrations
npm run db:push

# Start development server
npm run dev
```

## 🏪 App Store Deployment

The app is PWA-ready and can be deployed to app stores using:

- **Google Play Store**: Using TWA (Trusted Web Activities) or Capacitor
- **Apple App Store**: Using Capacitor for iOS wrapper
- **Direct Installation**: Users can install as PWA without app stores

See `APP_STORE_DEPLOYMENT.md` for detailed instructions.

## 🔧 Environment Variables

```env
DATABASE_URL=your_postgresql_connection_string
PGHOST=your_database_host
PGPORT=5432
PGUSER=your_database_user
PGPASSWORD=your_database_password
PGDATABASE=your_database_name
```

## 🚀 Deployment

### Development
```bash
npm run dev
```

### Production
```bash
npm run build
npm start
```

### Database
```bash
# Push schema changes
npm run db:push

# Generate migrations
npm run db:generate

# Run migrations
npm run db:migrate
```

## 📊 Project Structure

```
easymed-healthcare-app/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/    # Reusable UI components
│   │   ├── pages/         # Application pages
│   │   ├── hooks/         # Custom React hooks
│   │   └── lib/           # Utility functions
│   └── public/            # Static assets and PWA files
├── server/                # Backend Express application
│   ├── routes.ts          # API routes
│   ├── storage.ts         # Database operations
│   └── index.ts           # Server entry point
├── shared/                # Shared types and schemas
│   └── schema.ts          # Database schema definitions
└── docs/                  # Documentation
```

## 🔒 Security & Compliance

- **Data Protection**: Follows data localization requirements for Indian healthcare
- **Privacy**: Comprehensive privacy policy for medical data
- **Security**: Secure database connections and API endpoints
- **Compliance**: Designed with Indian healthcare regulations in mind

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

For support, email support@easymed.com or create an issue in this repository.

## 🏥 Healthcare Disclaimer

This application is for informational purposes only and does not replace professional medical advice. Always consult with qualified healthcare providers for medical decisions.

---

Made with ❤️ for Indian healthcare by [Praveen Kumar J]