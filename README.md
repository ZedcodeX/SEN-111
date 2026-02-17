# SEN 111 - Introduction to Web Programming & Design

A modern, responsive course website for the Introduction to Web Programming & Design course at Admiralty University of Nigeria (ADUN).

## 📚 Course Content

This website covers the following topics:

- **Week 1:** Web Development Overview
- **Week 2:** HTML Document Structure  
- **Week 3:** Cascading Style Sheets (CSS)
- **Week 6:** JavaScript Fundamentals
- **Week 7:** DOM Manipulation & AJAX

## 🚀 Deploy to Vercel

Follow these steps to deploy this website to Vercel:

### Method 1: Deploy via Vercel Dashboard (Easiest)

1. **Create a GitHub Account** (if you don't have one)
   - Go to [github.com](https://github.com) and sign up

2. **Create a New Repository**
   - Click the "+" icon in the top right → "New repository"
   - Name it: `sen111-course-website`
   - Make it Public
   - Click "Create repository"

3. **Upload Files to GitHub**
   - On the repository page, click "uploading an existing file"
   - Drag and drop ALL files from this project:
     - `index.html`
     - `package.json`
     - `vercel.json`
     - `README.md`
   - Click "Commit changes"

4. **Deploy to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "Sign Up" and choose "Continue with GitHub"
   - Click "Import Project"
   - Select your `sen111-course-website` repository
   - Click "Deploy"
   - Wait 30-60 seconds for deployment to complete
   - Your site will be live at: `https://sen111-course-website-[random].vercel.app`

### Method 2: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Navigate to Project Directory**
   ```bash
   cd path/to/sen111-website
   ```

3. **Login to Vercel**
   ```bash
   vercel login
   ```

4. **Deploy**
   ```bash
   vercel
   ```
   
   Follow the prompts:
   - Set up and deploy? **Y**
   - Which scope? Select your account
   - Link to existing project? **N**
   - What's your project's name? `sen111-course-website`
   - In which directory is your code located? **./`**
   - Want to override settings? **N**

5. **Your site is now live!** Vercel will provide you with a URL.

### Method 3: Deploy via Git

1. **Initialize Git Repository**
   ```bash
   cd path/to/sen111-website
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub**
   ```bash
   git remote add origin https://github.com/yourusername/sen111-course-website.git
   git branch -M main
   git push -u origin main
   ```

3. **Import to Vercel** (follow steps from Method 1, step 4)

## 🌐 Custom Domain (Optional)

After deployment, you can add a custom domain:

1. Go to your project in Vercel Dashboard
2. Click "Settings" → "Domains"
3. Add your custom domain (e.g., `sen111.yourdomain.com`)
4. Follow Vercel's DNS configuration instructions

## 📱 Features

- **Responsive Design:** Works on desktop, tablet, and mobile
- **Smooth Navigation:** Sticky navigation with smooth scrolling
- **Clean Code:** Well-organized, commented HTML/CSS/JavaScript
- **Fast Loading:** Optimized for performance
- **Modern Design:** Professional academic aesthetic

## 🛠️ Local Development

To run locally:

```bash
# Using Python
python -m http.server 8000

# Or using Node.js
npx http-server -p 8000
```

Then open `http://localhost:8000` in your browser.

## 📄 License

MIT License - Feel free to use for educational purposes.

## 👨‍🏫 Course Information

**Course:** ADUN-SEN 111 - Introduction to Web Programming & Design  
**Department:** Software Engineering, Computing Science  
**Institution:** Admiralty University of Nigeria (ADUN), Delta State  
**Lecturer:** Bernard Ephraim

---

Built with ❤️ for ADUN students
