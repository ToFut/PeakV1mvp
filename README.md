# Peak 1031 Exchange Management System

A comprehensive React-based web application for managing 1031 exchange transactions with multiple user interfaces for different stakeholders.

## Features

### 🏢 Admin Dashboard
- **Exchange Overview**: Monitor all active exchanges with progress tracking
- **System Statistics**: Real-time metrics and performance indicators
- **Audit Logs**: Security monitoring and activity tracking
- **PracticePanther Integration**: Sync with external practice management system
- **Task Management**: Assign and track tasks across exchanges

### 👥 Client Portal
- **Personalized Dashboard**: Client-specific exchange overview
- **Document Management**: Secure upload and access to exchange documents
- **Secure Messaging**: Encrypted communication with staff
- **Progress Tracking**: Real-time updates on exchange status
- **Task Completion**: Client task management and completion

### 🏪 Super Third Party (Real Estate Agency)
- **Agent Performance**: Monitor multiple agents and their exchanges
- **Volume Analytics**: Track total exchange volume and success rates
- **Agent Activity**: Real-time activity monitoring and reporting
- **Multi-Exchange Management**: Oversee multiple client exchanges

### 🤝 Third Party Agent
- **Limited Access Portal**: Secure access to relevant exchange information
- **Client Communication**: Direct messaging with clients and staff
- **Document Sharing**: Upload and share property-related documents
- **Progress Monitoring**: Track exchange progress within role limitations

## Technology Stack

- **Frontend**: React 18 with Vite
- **Styling**: Tailwind CSS with custom design system
- **Icons**: Lucide React for consistent iconography
- **Font**: Inter font family for modern typography
- **Build Tool**: Vite for fast development and optimized builds

## Getting Started

### Prerequisites
- Node.js 16+ 
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd peak-1031-system
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

## Project Structure

```
peak-1031-system/
├── src/
│   ├── components/
│   │   └── Peak1031Preview.jsx    # Main application component
│   ├── main.jsx                    # React entry point
│   └── index.css                   # Global styles and Tailwind
├── public/                         # Static assets
├── index.html                      # HTML template
├── package.json                    # Dependencies and scripts
├── vite.config.js                  # Vite configuration
├── tailwind.config.js             # Tailwind CSS configuration
└── postcss.config.js              # PostCSS configuration
```

## Key Features

### 🔐 Security Features
- **Two-Factor Authentication (2FA)**: Enhanced login security
- **Role-Based Access Control**: Different interfaces for different user types
- **Audit Logging**: Complete activity tracking and monitoring
- **Secure Document Storage**: Protected document access with PIN requirements

### 📊 Real-Time Monitoring
- **Progress Tracking**: Visual progress bars with deadline indicators
- **Deadline Alerts**: 45-day and 180-day deadline monitoring
- **Status Updates**: Real-time exchange status updates
- **Notification System**: Unread message and task notifications

### 📱 Responsive Design
- **Mobile-First**: Optimized for all device sizes
- **Modern UI**: Clean, professional interface design
- **Accessibility**: WCAG compliant design patterns
- **Performance**: Optimized for fast loading and smooth interactions

### 🔄 Integration Ready
- **PracticePanther Sync**: External system integration
- **API-Ready**: Structured for backend API integration
- **Modular Architecture**: Easy to extend and maintain
- **State Management**: Ready for Redux or Context API integration

## Development

### Adding New Features
1. Create new components in `src/components/`
2. Update the main component to include new views
3. Add any new dependencies to `package.json`
4. Update Tailwind config for new design tokens

### Styling Guidelines
- Use Tailwind CSS utility classes
- Follow the established color palette
- Maintain consistent spacing and typography
- Ensure responsive design for all components

### Code Quality
- Use functional components with hooks
- Implement proper error handling
- Add comments for complex logic
- Follow React best practices

## Deployment

### Build for Production
```bash
npm run build
```

### Deploy Options
- **Vercel**: Connect GitHub repository for automatic deployments
- **Netlify**: Drag and drop the `dist` folder
- **AWS S3**: Upload built files to S3 bucket
- **Traditional Hosting**: Upload files to any web server

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## License

This project is proprietary software for Peak 1031 Exchange Services.

## Support

For technical support or questions about the Peak 1031 system, please contact the development team.

---

**Peak 1031 V1** - Professional 1031 Exchange Management System 