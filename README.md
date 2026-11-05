# Falcha Filmation Studio — GitHub Pages edition

This is a static HTML conversion of the supplied PHP website. It preserves the dark cinematic presentation, logo and supplied image assets, category switching, service/about/contact dialogs and film player.

## Publish on GitHub Pages
1. Create a new GitHub repository (for example `falcha-filmation`).
2. Upload `index.html` from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to provide the public website URL.

## Contact form setup
The proposal form is configured for `devkotarejil@gmail.com` using FormSubmit (`https://formsubmit.co`). On the first real submission, FormSubmit sends an activation email to that inbox. Open it and confirm the activation link. After activation, new proposals will be delivered to that inbox. Check spam if the activation email is not visible.

GitHub Pages serves static files only; it cannot run PHP. This conversion removes PHP handlers and uses a hosted form endpoint for email delivery. Do not add Gmail passwords or private API keys to this repository.

## Notes
- The supplied PHP data references sample demonstration MP4 files hosted by Google. Replace those sample video URLs in the `films` object near the bottom of `index.html` with your own licensed showreel and project videos before launch.
- The supplied package contained image assets but no original video files.
