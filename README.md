project link - https://varun-sivanesan-code-progress-bar.vercel.app/ 

[![Watch Code Progress Bar](https://img.youtube.com/vi/JX34q_AWvDI/hqdefault.jpg)](https://youtu.be/JX34q_AWvDI)


# Code Progress Bar

Code Progress Analyzer is a sophisticated web application designed to help developers measure their progress in aligning their code with specific goals. It provides real-time feedback and visualizations to help users improve their coding practices and achieve their objectives.

### Key Features

- **Progress Visualization**: An animated progress bar that shows how well your code aligns with your goals
- **Score Calculation**: Dynamic scoring system that evaluates code quality and alignment
- **Interactive UI**: Smooth animations and transitions for a better user experience
- **Responsive Design**: Works perfectly on all devices
- **User Authentication**: Secure login and user management using Clerk
- **Real-time Feedback**: Instant advice and recommendations based on your code

### Technology Stack

- **Next.js 14**: Modern React framework for server-side rendering
- **TypeScript**: For type-safe development
- **React**: Core UI library
- **Clerk Authentication**: For secure user management
- **Tailwind CSS**: For styling and responsive design
- **Custom UI Components**: Built with React and Tailwind

### Getting Started

1. First, clone the repository to your local machine:
```bash
git clone https://github.com/yourusername/code-progress-analyzer.git
```

2. Install all necessary dependencies:
```bash
npm install
# or
yarn install
```

3. Set up your environment variables by creating a `.env` file:
```
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key_here
CLERK_SECRET_KEY=your_clerk_secret_here
GEMINI_API_KEY=your_gemini_api_key_here
SUPABASE_URL=your_supabase_url_here
SUPABASE_ANON_KEY=your_supabase_anon_key_here
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

5. Open your browser and navigate to [http://localhost:3000](http://localhost:3000)

### Project Structure

The project follows a clean and organized structure:

```
src/
├── app/              # Main application routes and pages
├── components/       # Reusable React components
├── lib/             # Utility functions and configurations
├── public/          # Static assets like images and fonts
└── data/            # Application data and configurations
```

### Key Components

- **NumberTicker**: A custom component that animates number changes smoothly
- **Confetti**: Adds celebratory visual effects for milestone achievements
- **HyperText**: Interactive text component with dynamic styling
- **ResultPage**: The main visualization page that shows progress
- **AppPage**: User interface for code input and goal setting

### API Endpoints

The application uses several API endpoints to handle data:

- **/api/get-score**: Calculates the alignment score based on user's code
- **/api/get-user-data**: Retrieves user's goals and code data
- **/api/save-data**: Saves user's progress and code submissions
- **/api/update-profile**: Updates user's profile information

### Contributing

We welcome contributions from the community! Here's how to get started:

1. Fork the repository on GitHub
2. Create a new feature branch:
```bash
git checkout -b feature/your-feature-name
```
3. Make your changes and commit them:
```bash
git commit -m 'Add your feature description'
```
4. Push your changes to your fork:
```bash
git push origin feature/your-feature-name
```
5. Create a Pull Request on the main repository

### License

This project is licensed under the MIT License - see the LICENSE file for details

### Support

For support, please open an issue in the GitHub repository or contact the maintainers directly
