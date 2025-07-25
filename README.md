# Personal Portfolio - Sai Panindra Pechetti

A VS Code-inspired personal portfolio website built with React, TypeScript, and Tailwind CSS. This portfolio showcases professional experience, projects, and skills in a modern, interactive interface.

## 🚀 Features

- **VS Code-inspired Design**: Dark theme with authentic VS Code aesthetics
- **Interactive Navigation**: Fixed sidebar with breadcrumb navigation
- **Responsive Layout**: Works seamlessly on desktop and mobile devices
- **Hover Interactions**: Download CV and portfolio site buttons on hover
- **Collapsible Experience**: Expandable experience cards with detailed information
- **Modern Tech Stack**: Built with React, TypeScript, Tailwind CSS, and Shadcn/UI

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 18 or higher)
- **npm** (comes with Node.js)
- **Git** (for version control)

## 🛠️ Installation & Setup

### 1. Clone or Extract the Project

If you have the zip file:
```bash
# Extract the zip file to your desired location
unzip PersonalPortfolio.zip
cd PersonalPortfolio
```

If cloning from a repository:
```bash
git clone <repository-url>
cd PersonalPortfolio
```

### 2. Install Dependencies

```bash
npm install
```

This will install all required dependencies including:
- React & React DOM
- TypeScript
- Tailwind CSS
- Shadcn/UI components
- Express.js (for backend)
- And many more...

### 3. Environment Setup

The project is configured to work out of the box. No additional environment variables are required for basic functionality.

## 🚀 Running the Application

### Development Mode

To start the development server:

```bash
npm run dev
```

This will:
- Start the Express.js backend server on port 5000
- Launch the React development server
- Enable hot reloading for development
- Open the application in your default browser

The application will be available at: `http://localhost:5000`

### Production Build

To create a production build:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## 📁 Project Structure

```
PersonalPortfolio/
├── client/                 # Frontend React application
│   ├── src/
│   │   ├── components/     # Reusable UI components
│   │   │   ├── layout/     # Layout components (header, sidebar, etc.)
│   │   │   └── ui/         # Shadcn/UI components
│   │   ├── pages/          # Page components
│   │   │   ├── home.tsx    # Homepage with terminal interface
│   │   │   ├── about.tsx   # About page
│   │   │   ├── experience.tsx # Experience timeline
│   │   │   ├── projects.tsx   # Projects showcase
│   │   │   ├── contact.tsx    # Contact information
│   │   │   └── blog.tsx       # Blog page
│   │   ├── hooks/          # Custom React hooks
│   │   ├── lib/            # Utility functions
│   │   └── index.css       # Global styles and Tailwind imports
│   └── index.html          # HTML template
├── server/                 # Backend Express.js server
│   ├── index.ts           # Main server file
│   ├── routes.ts          # API routes
│   └── storage.ts         # Data storage utilities
├── shared/                # Shared types and schemas
├── package.json           # Dependencies and scripts
├── tailwind.config.ts     # Tailwind CSS configuration
├── tsconfig.json          # TypeScript configuration
└── vite.config.ts         # Vite build configuration
```

## 🎨 Customization

### Personal Information

To customize the portfolio with your own information:

1. **Home Page** (`client/src/pages/home.tsx`):
   - Update name and title
   - Modify CV download content
   - Change portfolio site URL

2. **About Page** (`client/src/pages/about.tsx`):
   - Update personal bio and background
   - Modify skills and technologies

3. **Experience Page** (`client/src/pages/experience.tsx`):
   - Add/modify work experiences
   - Update company details and achievements

4. **Projects Page** (`client/src/pages/projects.tsx`):
   - Add your own projects
   - Update project descriptions and technologies

5. **Contact Page** (`client/src/pages/contact.tsx`):
   - Update contact information
   - Modify social media links

### Styling

The project uses Tailwind CSS with custom color variables defined in `client/src/index.css`:

```css
:root {
  --bgBlack: #0a0d12;        /* Main background */
  --bgBlackSec: #0d1117;     /* Secondary background */
  --tWhiteSec: rgb(229, 233, 240); /* Primary text */
  --tBlue: #53b0fd;          /* Accent blue */
}
```

### Adding New Pages

1. Create a new component in `client/src/pages/`
2. Add the route in `client/src/App.tsx`
3. Update the sidebar navigation in `client/src/components/layout/sidebar.tsx`

## 🔧 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Create production build
- `npm start` - Start production server
- `npm run check` - Run TypeScript type checking
- `npm run db:push` - Push database schema (if using database features)

## 🌐 Deployment

### Local Deployment

The application is ready for deployment. The production build creates optimized files that can be served by any static file server.

### Cloud Deployment

This project can be deployed to various platforms:

- **Vercel**: Automatic deployment with Git integration
- **Netlify**: Static site hosting with continuous deployment
- **Heroku**: Full-stack application hosting
- **Railway**: Modern application deployment platform

## 🛠️ Technologies Used

### Frontend
- **React 18** - Modern React with hooks
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Shadcn/UI** - High-quality UI components
- **Wouter** - Lightweight routing
- **Framer Motion** - Smooth animations
- **Lucide React** - Beautiful icons

### Backend
- **Express.js** - Web application framework
- **TypeScript** - Type-safe server code
- **Drizzle ORM** - Type-safe database operations

### Development Tools
- **Vite** - Fast build tool and dev server
- **ESBuild** - Fast JavaScript bundler
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 🐛 Troubleshooting

### Common Issues

1. **Port already in use**:
   ```bash
   # Kill process using port 5000
   lsof -ti:5000 | xargs kill -9
   ```

2. **Dependencies not installing**:
   ```bash
   # Clear npm cache and reinstall
   npm cache clean --force
   rm -rf node_modules package-lock.json
   npm install
   ```

3. **TypeScript errors**:
   ```bash
   # Run type checking
   npm run check
   ```

4. **Build failures**:
   ```bash
   # Clean build and rebuild
   rm -rf dist
   npm run build
   ```

## 📝 License

This project is licensed under the MIT License. Feel free to use it as a template for your own portfolio.

## 🤝 Contributing

If you'd like to contribute to this project:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

If you encounter any issues or have questions:

1. Check the troubleshooting section above
2. Review the project structure and documentation
3. Create an issue in the repository (if applicable)

---

**Happy coding! 🚀**

#   p e r s o n a l p o r t f o l i o  
 #   P e r s o n a l P o r t f o l i o  
 