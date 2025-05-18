# Guide to Creating a Free Programmer Portfolio on GitHub Pages

This guide explains how to create a free professional portfolio website using GitHub Pages to showcase your mobile app projects.

## Steps

### 1. Create a GitHub Account

If you don't already have a GitHub account, create a free account at [GitHub](https://github.com/signup).

### 2. Create a New Repository

1. Click the "+" button in the top right corner of the screen and select "New repository"
2. Name the repository `username.github.io` (replace "username" with your GitHub username)
3. Make the repository public
4. Click "Create repository"

### 3. Upload Portfolio Files

You can upload the portfolio files we've created using one of the following methods:

#### Method 1: Using the GitHub Interface

1. Go to the repository you created
2. Click "Add file" then "Upload files"
3. Drag and drop all files and folders from the folder we created
4. Click "Commit changes"

#### Method 2: Using Git (for Advanced Users)

```bash
git clone https://github.com/username/username.github.io.git
# Copy all portfolio files to the cloned folder
cd username.github.io
git add .
git commit -m "Initial portfolio commit"
git push -u origin main
```

### 4. Customize Your Portfolio

To customize your portfolio, you can edit the following files:

1. **_config.yml**: To edit basic information and social links
   - Update `social_media` with your account links
   - Modify `topics` to reflect your skills

2. **index.md**: To edit the welcome text and description
   - Update the introduction and description with your personal information

3. **_includes/example-projects.html**: To edit your projects
   - Update project names, descriptions, and links

### 5. Add Project Images (Optional)

To add images to your projects:

1. Create an `assets/images` folder if it doesn't exist
2. Upload your project images to this folder
3. Edit the `_includes/example-projects.html` file to add images:

```html
<img src="/assets/images/project-image.jpg" alt="Project description" class="width-full">
```

### 6. Publish Your Site

After uploading and customizing the files, GitHub Pages will automatically publish your site within a few minutes. You can access your site at:

```
https://username.github.io
```

### 7. Check Settings

1. Go to the "Settings" tab in your repository
2. Navigate to the "Pages" section in the sidebar
3. Make sure the source is set to "main" or "master"

## Updating Your Portfolio

To update your portfolio in the future, simply edit the files in the repository. You can:

1. Add new projects by editing the `_includes/example-projects.html` file
2. Update personal information in `_config.yml` and `index.md`
3. Add new images to the `assets/images` folder

## Additional Features

- **Blog**: You can add blog posts by creating files in the `_posts` folder
- **Additional Pages**: You can create additional pages such as "About" or "Contact"
- **Contact Form**: You can add a contact form using services like Formspree

## Support and Help

If you encounter any problems or have questions about customizing your portfolio, you can:

1. Review the [GitHub Pages documentation](https://docs.github.com/en/pages)
2. Search in the [GitHub Community](https://github.community/)
3. Contact me for additional assistance
