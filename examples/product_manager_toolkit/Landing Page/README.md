# Step-by-Step Guide to Launch Your HTML Website

This guide will help you get your HTML website up and running locally and online, connect a custom domain, and ensure your contact form works.

## 1. View the Website Locally

### Requirements:
- A web browser (e.g., Chrome, Firefox, Safari)
- A text editor (e.g., Notepad, TextEdit, VSCode)

### Steps:
1. **Save Your HTML File:**
   - Copy the HTML code provided into a text editor.
   - Save the file with a `.html` extension, for example, `index.html`.

2. **Open the HTML File in a Browser:**
   - Locate the saved `index.html` file on your computer.
   - Double-click the file to open it in your default web browser.
   - You should now see your website displayed in the browser.

## 2. Host Your Website Online for Free

### Option 1: GitHub Pages

1. **Create a GitHub Account:**
   - Go to [GitHub](https://github.com) and sign up for a free account.

2. **Create a New Repository:**
   - Click on the "+" icon in the top-right corner and select "New repository."
   - Name your repository (e.g., `my-website`) and click "Create repository."

3. **Upload Your HTML File:**
   - Click "Add file" > "Upload files."
   - Drag and drop your `index.html` file into the repository.
   - Click "Commit changes" to save.

4. **Enable GitHub Pages:**
   - Go to the "Settings" tab of your repository.
   - Scroll down to "GitHub Pages" and select the "main" branch as the source.
   - Click "Save."
   - Your site will be available at `https://yourusername.github.io/my-website`.

### Option 2: Netlify

1. **Create a Netlify Account:**
   - Go to [Netlify](https://www.netlify.com) and sign up for a free account.

2. **Deploy Your Site:**
   - Click "New site from Git."
   - Connect your GitHub account and select your repository.
   - Follow the prompts to deploy your site.
   - Your site will be live at a Netlify-generated URL.

## 3. Connect a Custom Domain Name

### Steps:
1. **Purchase a Domain:**
   - Buy a domain from a registrar like [Namecheap](https://www.namecheap.com) or [GoDaddy](https://www.godaddy.com).

2. **Configure DNS Settings:**
   - For GitHub Pages:
     - Go to your domain registrar's DNS settings.
     - Add a CNAME record pointing to `yourusername.github.io`.
   - For Netlify:
     - In Netlify, go to "Domain settings" and add your custom domain.
     - Follow the instructions to update your DNS settings with your registrar.

3. **Verify Domain Connection:**
   - It may take a few hours for DNS changes to propagate.
   - Once done, your site should be accessible via your custom domain.

## 4. Ensure the Contact Form Works

### Using Formspree

1. **Set Up Formspree:**
   - Go to [Formspree](https://formspree.io) and sign up for a free account.

2. **Configure Your Form:**
   - Replace your form's `action` attribute with the Formspree endpoint.
   - Example: `<form action="https://formspree.io/f/your-form-id" method="POST">`

3. **Test Your Form:**
   - Submit the form on your website to ensure it sends emails to your specified address.

## 5. Handle Assets Like Images or SVGs

### Steps:
1. **Ensure Images are Accessible:**
   - If using external images (e.g., from Unsplash), ensure the URLs are correct.
   - For local images, upload them to your hosting platform and update the paths in your HTML.

2. **Check Image Display:**
   - Open your website and verify that all images load correctly.

By following these steps, you should have your HTML website live on the internet, accessible via a custom domain, and with a working contact form. Enjoy your new website!