# How to Get Your HTML Website Live

Follow these simple steps to view your website locally, host it online for free, connect a custom domain, and ensure your contact form works.

## 1. View the Website Locally

### Step-by-Step:

1. **Save Your HTML File:**
   - Copy the HTML code provided into a text editor (like Notepad on Windows, TextEdit on Mac, or any code editor like VSCode).
   - Save the file with a `.html` extension, e.g., `index.html`.

2. **Open in a Browser:**
   - Locate the saved `index.html` file on your computer.
   - Double-click the file to open it in your default web browser.
   - You should now see your website displayed in the browser.

## 2. Host Your Website Online for Free

### Using GitHub Pages:

1. **Create a GitHub Account:**
   - Go to [GitHub](https://github.com) and sign up for a free account if you don't have one.

2. **Create a New Repository:**
   - Click on the "+" icon in the top-right corner and select "New repository."
   - Name your repository (e.g., `my-website`) and make it public.
   - Click "Create repository."

3. **Upload Your HTML File:**
   - On your repository page, click "Add file" > "Upload files."
   - Drag and drop your `index.html` file into the upload area.
   - Click "Commit changes" to save the file to your repository.

4. **Enable GitHub Pages:**
   - Go to the "Settings" tab of your repository.
   - Scroll down to the "GitHub Pages" section.
   - Under "Source," select the branch (usually `main`) and click "Save."
   - Your site will be published at `https://your-username.github.io/repository-name`.

### Using Netlify:

1. **Create a Netlify Account:**
   - Go to [Netlify](https://www.netlify.com) and sign up for a free account.

2. **Deploy Your Site:**
   - Click "New site from Git" on your Netlify dashboard.
   - Connect your GitHub account and select the repository you created.
   - Follow the prompts to deploy your site.
   - Your site will be live at a Netlify-provided URL.

## 3. Connect a Custom Domain

### Using GitHub Pages:

1. **Purchase a Domain:**
   - Buy a domain from a registrar like [Namecheap](https://www.namecheap.com) or [GoDaddy](https://www.godaddy.com).

2. **Configure DNS Settings:**
   - In your domain registrar's dashboard, find the DNS settings.
   - Add a CNAME record pointing `www` to `your-username.github.io`.

3. **Set Up GitHub Pages:**
   - In your GitHub repository settings, under "GitHub Pages," enter your custom domain in the "Custom domain" field.

### Using Netlify:

1. **Add a Custom Domain:**
   - In your Netlify dashboard, go to your site settings.
   - Click "Domain management" and then "Add custom domain."
   - Enter your domain name and follow the instructions to update your DNS settings.

## 4. Ensure the Contact Form Works

### Using Formspree:

1. **Sign Up for Formspree:**
   - Go to [Formspree](https://formspree.io) and create a free account.

2. **Get Your Form ID:**
   - Create a new form and copy the form ID provided.

3. **Update Your HTML:**
   - Replace `your-form-id` in the form action URL with your actual Formspree form ID.

4. **Test Your Form:**
   - Submit the form on your live site to ensure it sends emails to your specified address.

## 5. Handle Assets Like Images

- **External Images:**
  - Your HTML uses images from `https://source.unsplash.com`. These are hosted externally, so you don't need to upload them.

- **Local Images:**
  - If you have local images, upload them to your GitHub repository or Netlify site in the same way as your HTML file.
  - Update the `src` attribute in your HTML to point to the correct path.

By following these steps, your website should be live, accessible via a custom domain, and fully functional with a working contact form. Enjoy your new online presence!