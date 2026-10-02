# Erandly - Local Tasks & Digital Services Marketplace

**Live URL**: https://www.erandly.com/

Erandly is a platform for finding trusted help with local errands and digital services worldwide. Post tasks, hire helpers, and get things done.

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS + shadcn/ui
- Supabase (Auth, Database, Edge Functions, Storage)
- Capacitor (iOS & Android native apps)
- Resend (Email notifications)

## Local Development

```sh
# Clone the repository
git clone https://github.com/talhar30/errandly2

# Navigate to the project directory
cd errandly2

# Install dependencies
npm install

# Start the development server
npm run dev
```

## Building Native Apps (Capacitor)

```sh
# Build web assets
npm run build

# Sync to native platforms
npx cap sync

# Open in Xcode (iOS)
npx cap open ios

# Open in Android Studio (Android)
npx cap open android
```

## Deployment

The app can be deployed to any static hosting provider. Build with `npm run build` and serve the `dist/` folder.

## Custom Domain

The production app is served at https://www.erandly.com/
