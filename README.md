# clone-web
# LinkedIn Clone

A fully functional LinkedIn clone built with HTML, CSS, and JavaScript. Features include:
- Feed with posts and interactions
- Profile section
- Advanced Resume Builder with PDF export
- Profile integration for resumes
- Networking suggestions

## Live Demo

This project can be hosted on GitHub Pages: [View Live Demo](https://yourusername.github.io/linkedin-clone)

## Features

- **Enhanced Resume Builder**:
  - PDF download functionality
  - Profile integration
  - Sharing options

- **Responsive Design**:
  - Works on mobile, tablet, and desktop

## Deployment Instructions

### Deploy to GitHub Pages (Step-by-Step):

1. **Initialize Git in your project folder**:
   ```
   cd linkedin-clone
   git init
   ```

2. **Create a GitHub repository**:
   - Sign up/in to GitHub
   - Create a new repository named "linkedin-clone"
   - Do NOT initialize with a README (we already have one)

3. **Connect your local repository to GitHub**:
   ```
   git remote add origin https://github.com/yourusername/linkedin-clone.git
   ```

4. **Add and commit your files**:
   ```
   git add .
   git commit -m "Initial commit"
   ```

5. **Push to GitHub**:
   ```
   git push -u origin main
   ```
   Note: If your default branch is "master", use `git push -u origin master` instead

6. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click "Save"

7. **Access your live site**:
   - Your site will be available at `https://yourusername.github.io/linkedin-clone`
   - It may take a few minutes for the site to be published

### Important Files for Deployment:

- `index.html`: Entry point for the website (redirects to minimal-viewer.html)
- `minimal-viewer.html`: Contains the LinkedIn clone interface
- Assets are loaded from CDNs, so no additional file upload is needed

### Alternative Deployment Options:

#### Netlify:
1. Sign up for a Netlify account
2. Drag and drop your project folder to the Netlify dashboard
3. Your site will be live with a Netlify subdomain

#### Vercel:
1. Sign up for a Vercel account
2. Install Vercel CLI: `npm i -g vercel`
3. Run `vercel` in your project directory
4. Follow the prompts to deploy

## Local Development

To run this project locally:

1. Clone the repository
   ```
   git clone https://github.com/yourusername/linkedin-clone.git
   cd linkedin-clone
   ```

2. Open the minimal-viewer.html file in your browser
   - Either double-click the file
   - Or enter `file:///path/to/your/linkedin-clone/minimal-viewer.html` in your browser

## License

MIT License 
