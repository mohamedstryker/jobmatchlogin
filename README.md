JobMatch Login
A modern authentication system built with Next.js 14 and NextAuth.js, featuring GitHub and Google OAuth integration and MongoDB as the database.

🚀 Features
Next.js for server-side rendering and static site generation.
NextAuth.js for authentication with GitHub and Google OAuth.
MongoDB for secure and scalable data storage.
Responsive and modern UI.
📂 Directory Structure
arduino
Copy code
Project/
├── NextJS14-NextAuth-Login-And-Register/
│   ├── app/
│   │   ├── api/
│   │   │   └── auth/[...nextauth]/route.ts
│   │   ├── layout.tsx
│   │   ├── page.tsx
│   └── public/
│       ├── logo.png
│       ├── favicon.ico
└── ...
🛠️ Technologies Used
Next.js 14
NextAuth.js
MongoDB
TypeScript
📦 Installation
Clone the repository:

bash
Copy code
git clone https://github.com/mohamedstryker/jobmatch-home.git
cd jobmatch-home/NextJS14-NextAuth-Login-And-Register
Install dependencies:

bash
Copy code
npm install
Add environment variables to .env file:

env
Copy code
MONGO_URI=mongodb+srv://your_mongo_uri
GITHUB_ID=your_github_client_id
GITHUB_SECRET=your_github_client_secret
GOOGLE_ID=your_google_client_id
GOOGLE_SECRET=your_google_client_secret
NEXTAUTH_SECRET=your_nextauth_secret
NEXTAUTH_URL=https://your-deployed-url.com
Run the development server:

bash
Copy code
npm run dev

To deploy:

Push your changes to GitHub.
Connect your repository to Netlify or Vercel.
Ensure all environment variables are added in the platform’s settings.
⚙️ Configuration
Make sure to configure the following services:

MongoDB Atlas: For database storage.
GitHub OAuth: Get your credentials from the GitHub Developer Portal.
Google OAuth: Configure your app in the Google Cloud Console.
🐛 Known Issues
Ensure NEXTAUTH_URL matches your deployment URL.
Verify MongoDB connection string and ensure IP whitelisting is configured.
🤝 Contributing
Contributions are welcome! Please fork the repository, make changes, and submit a pull request.

📄 License
This project is licensed under the MIT License.
