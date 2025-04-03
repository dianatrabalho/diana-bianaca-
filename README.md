# Clone your repository
git clone <your-github-repo-url>
cd <your-project-directory>

# Install dependencies (if not already done)
npm install

# Build the project
npm run build

# Initialize Capacitor platforms
npx cap add ios     # For iOS
npx cap add android # For Android

# Sync the build with native projects
npx cap sync
# diana-bianaca-
