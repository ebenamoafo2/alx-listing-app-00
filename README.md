# ALX Listing App

A modern Airbnb clone listing page built with Next.js, TypeScript, and Tailwind CSS. This application helps users easily find and book short-stay accommodations while traveling, on tours, business trips, or other visits away from home.

## 🎯 Project Goals

- Create a responsive and user-friendly property listing interface
- Implement a complete booking system from listing to checkout
- Support for property agents and third-party services
- Secure payment integration
- Build a scalable and maintainable codebase with modern web technologies

## 🚀 Features

- **Property Listing Page**: Browse available properties with detailed information
- **Property Details**: View comprehensive property information, amenities, and photos
- **User Authentication**: Secure login and registration system
- **Booking System**: Complete booking workflow with date selection
- **Reviews & Comments**: User feedback and rating system
- **Responsive Design**: Optimized for all device sizes
- **Search & Filters**: Advanced property search and filtering options

## 📁 Project Structure

```
alx-listing-app/
├── components/           # Reusable UI components
│   ├── common/          # Shared components (Card, Button, etc.)
│   └── layout/          # Layout components (Header, Footer)
├── interfaces/          # TypeScript type definitions
│   └── index.ts         # All interface exports
├── constants/           # Application constants and configuration
│   └── index.ts         # API endpoints, UI constants, validation rules
├── public/              # Static assets
│   └── assets/          # Organized asset structure
│       ├── images/      # Property photos, avatars, locations
│       ├── icons/       # SVG icons and UI elements
│       └── illustrations/ # Empty states and error pages
├── pages/               # Next.js routes
│   ├── api/            # API endpoints
│   ├── index.tsx       # Homepage
│   ├── _app.tsx        # App configuration
│   └── _document.tsx   # Document configuration
├── styles/              # Global styles and Tailwind CSS
│   └── globals.css     # Main stylesheet
├── utils/               # Utility functions
└── README.md           # Project documentation
```

### Directory Purposes

- **`components/`**: Contains all reusable React components organized by feature and common usage patterns. The `common/` subdirectory includes shared components like Card, Button, and OptimizedImage that are used throughout the application.

- **`interfaces/`**: Houses all TypeScript type definitions and interfaces. This ensures type safety across the application and provides clear contracts for data structures like Property, User, Booking, and component props.

- **`constants/`**: Stores application-wide constants including API endpoints, configuration settings, property types, amenities lists, validation rules, and design tokens. This centralization makes the app easier to maintain and configure.

- **`public/assets/`**: Contains all static assets organized by type:
  - `images/`: Property photos, user avatars, location images
  - `icons/`: SVG icons for UI elements and amenities
  - `illustrations/`: Graphics for empty states and error pages

## 🛠️ Technologies Used

- **Frontend Framework**: [Next.js 13+](https://nextjs.org/) with App Router
- **Language**: [TypeScript](https://www.typescriptlang.org/) for type safety
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) for responsive design
- **State Management**: React Hooks (useState, useEffect, useContext)
- **Image Optimization**: Next.js Image component with custom optimization
- **Development Tools**: ESLint, Prettier, Husky for code quality

## 📋 Prerequisites

Before running this project, make sure you have the following installed:

- **Node.js** (version 18.0 or higher)
- **npm** (version 8.0 or higher) or **yarn** (version 1.22 or higher)
- **Git** for version control

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/alx-listing-app.git
cd alx-listing-app
```

### 2. Install Dependencies

Using npm:
```bash
npm install
```

Or using yarn:
```bash
yarn install
```

### 3. Environment Setup

Create a `.env.local` file in the root directory and add your environment variables:

```env
NEXT_PUBLIC_API_URL=http://localhost:3001/api
NEXT_PUBLIC_APP_URL=http://localhost:3000
FIGMA_TOKEN=your_figma_personal_access_token
```

### 4. Run the Development Server

Using npm:
```bash
npm run dev
```

Or using yarn:
```bash
yarn dev
```

### 5. Open Your Browser

Navigate to [http://localhost:3000](http://localhost:3000) to see the application running.

The page will automatically reload when you make changes to the code.

## 📱 Available Scripts

- `npm run dev` - Start the development server
- `npm run build` - Build the application for production
- `npm run start` - Start the production server
- `npm run lint` - Run ESLint for code linting
- `npm run lint:fix` - Fix ESLint errors automatically
- `npm run type-check` - Run TypeScript type checking

## 🎨 Asset Management

### Adding New Assets

1. **Images**: Place in `public/assets/images/` organized by category
2. **Icons**: Add SVG files to `public/assets/icons/`
3. **Update Constants**: Add new asset paths to `constants/index.ts`

### Importing from Figma

Use the provided Figma extraction script or manually export assets:

1. Export assets from your Figma design
2. Organize them in the appropriate `public/assets/` subdirectories
3. Update asset references in your components

## 🏗️ Building for Production

1. **Build the application**:
   ```bash
   npm run build
   ```

2. **Start the production server**:
   ```bash
   npm run start
   ```

## 📝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'feat: add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



## 🤝 Support

If you encounter any issues or have questions:

1. Check the [Issues](https://github.com/your-username/alx-listing-app/issues) page
2. Create a new issue with a detailed description
3. Join our community discussions

## 🙏 Acknowledgments

- Design inspiration from Airbnb
- Built as part of the ALX Software Engineering Program
- Thanks to the Next.js and React communities for excellent documentation

---

**Happy Coding! 🎉**
