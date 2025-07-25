# SaaS Landing Page

A modern, responsive SaaS landing page built with Next.js 14, TypeScript, Tailwind CSS, and Framer Motion. Features a beautiful design with dark/light theme support, smooth animations, and mobile-responsive layout.

## 🚀 Features

- **Modern Design**: Clean, professional SaaS landing page design
- **Responsive**: Fully responsive across all devices
- **Dark/Light Theme**: Toggle between dark and light themes
- **Smooth Animations**: Framer Motion powered animations
- **TypeScript**: Full TypeScript support for better development experience
- **Tailwind CSS**: Utility-first CSS framework for styling
- **Radix UI**: Accessible UI components
- **Next.js 14**: Latest Next.js with App Router

## 📋 Prerequisites

Before running this project, make sure you have the following installed on your Windows system:

### Required Software

1. **Node.js** (v18 or higher)
   - Download from [nodejs.org](https://nodejs.org/)
   - Verify installation: `node --version`

2. **pnpm** (Package Manager)
   - Install via PowerShell: `npm install -g pnpm`
   - Verify installation: `pnpm --version`

3. **Git** (Optional but recommended)
   - Download from [git-scm.com](https://git-scm.com/)
   - Verify installation: `git --version`

## 🛠️ Installation & Setup

### Step 1: Clone the Repository

Open PowerShell or Command Prompt and run:

```powershell
# Navigate to your desired directory
cd C:\Users\YourUsername\Documents\GitHub

# Clone the repository
git clone https://github.com/yourusername/saas-landing-page.git

# Navigate into the project directory
cd saas-landing-page
```

### Step 2: Install Dependencies

```powershell
# Install all dependencies using pnpm
pnpm install
```

### Step 3: Run the Development Server

```powershell
# Start the development server
pnpm dev
```

The application will be available at `http://localhost:3000`

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| `pnpm dev` | Start development server |
| `pnpm build` | Build for production |
| `pnpm start` | Start production server |
| `pnpm lint` | Run ESLint |

## 🏗️ Project Structure

```
saas-landing-page/
├── app/                    # Next.js App Router
│   ├── globals.css        # Global styles
│   ├── layout.tsx         # Root layout
│   └── page.tsx           # Home page
├── components/            # React components
│   ├── ui/               # UI components (Radix UI)
│   └── theme-provider.tsx # Theme provider
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static assets
└── styles/               # Additional styles
```

## 🎨 Customization

### Styling
- Modify `app/globals.css` for global styles
- Update `tailwind.config.js` for Tailwind configuration
- Edit component styles in individual component files

### Content
- Update the main content in `app/page.tsx`
- Modify features, pricing, and other sections as needed
- Replace placeholder images in the `public/` directory

### Theme
- Customize theme colors in `tailwind.config.js`
- Modify theme provider in `components/theme-provider.tsx`

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy automatically

### Other Platforms

```powershell
# Build the project
pnpm build

# Start production server
pnpm start
```

## 🐛 Troubleshooting

### Common Issues

**Port 3000 already in use:**
```powershell
# Find process using port 3000
netstat -ano | findstr :3000

# Kill the process (replace PID with actual process ID)
taskkill /PID <PID> /F
```

**pnpm not found:**
```powershell
# Install pnpm globally
npm install -g pnpm
```

**Node modules issues:**
```powershell
# Clear cache and reinstall
pnpm store prune
pnpm install
```

**TypeScript errors:**
```powershell
# Check TypeScript configuration
npx tsc --noEmit
```

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

If you encounter any issues or have questions:

1. Check the troubleshooting section above
2. Search existing issues in the repository
3. Create a new issue with detailed information

## 🔗 Links

- [Next.js Documentation](https://nextjs.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Radix UI Documentation](https://www.radix-ui.com/)
- [Framer Motion Documentation](https://www.framer.com/motion/)

---

Made with ❤️ using Next.js, TypeScript, and Tailwind CSS 