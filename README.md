
## Installation

### Prerequisites

- Node.js (>= 14.x)
- npm or yarn

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AswinKumar1/flashcard-ai-saas.git
   cd flashcard-ai-saas
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

   or

   ```bash
   yarn install
   ```

3. **Configure Environment Variables**

   Create a `.env` file in the root directory and add the following environment variables:

   ```bash
   NEXT_PUBLIC_STRIPE_PUBLIC_KEY=your_public_key
   OPENAI_API_KEY=your_openai_api_key
   STRIPE_SECRET_KEY=your_secret
   ```

4. **Run the Application**

   ```bash
   npm run dev
   ```

   or

   ```bash
   yarn dev
   ```

   The application will be accessible at `http://localhost:3000`.

## Deployment

To deploy the application, follow these steps:

1. **Build the Application**

   ```bash
   npm run build
   ```

   or

   ```bash
   yarn build
   ```

2. **Deploy to Vercel**

   For Vercel, you can directly connect your GitHub repository and configure deployment settings in the Vercel dashboard.




