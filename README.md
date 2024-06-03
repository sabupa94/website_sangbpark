# [My Personal Website](https://www.sangbpark.com)

This is the source code for my personal website built using Next.js. The website uses Next.js' file-based page routing system for navigation.

## Prerequisites

Ensure you have the following installed on your machine:

- Node.js (LTS version recommended)
- npm or yarn

## Getting Started

Follow these steps to set up and run the project locally.

### 1. Clone the Repository

First, clone the repository to your local machine:

```bash
git clone https://github.com/sabupa94/website_sangbpark.git
cd website_sangbpark
```

### 2. Install Dependencies

Navigate to the project directory and install the necessary dependencies:

```bash
npm install
```

Or, if you prefer using yarn:

```bash
yarn install
```

### 3. Run the Development Server

Start the development server to see the website in action:

```bash
npm run dev
```

Or, with yarn:

```bash
yarn dev
```

Open [http://localhost:3000](https://localhost:3000) in your browser to view the website.

### 4. Build for Production

To create an optimized production build, run:

```bash
npm run build
```

Or, with yarn:

```bash
yarn build
```

### 5. Start the Production Server

After building the project, you can start the production server with:

```bash
npm start
```

Or, with yarn:

```bash
yarn start
```

### 6. Project Structure

Here is a brief overview of the project structure:

```
my-personal-website/
├── src/                    # Contains the main files for the site
├────── pages/              # Contains the page components
│       ├── index.tsx       # Home page
├────── styles/             # CSS styles
├── public/                 # Static assets
├── package.json            # Project metadata and scripts
```

### 7. Customizing the Website

You can customize the content and styles of the website by editing the files in the src/pages and src/styles directories. Each file in the pages directory corresponds to a route in your application.

### 8. Deployment

To deploy the website, you can use platforms like Vercel, Netlify, or any other static site hosting service. Here is a basic example of deploying to Vercel:

Install the Vercel CLI:

```bash
npm install -g vercel
```

Deploy the site:

```bash
vercel
```

Follow the prompts to deploy the website (although it's my site...)

## Contributing

If you would like to contribute to the project (though I don't understand why you would), please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/sabupa94/website_sangbpark/blob/main/LICENSE) file for details.
