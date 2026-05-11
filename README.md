# Chandru Sankar - Portfolio Website

Personal portfolio website built with Jekyll and hosted on GitHub Pages.

## 🚀 Live Site

Visit: [https://chandrusankar.github.io](https://chandrusankar.github.io)

## 🛠️ Setup Instructions

### Prerequisites
- GitHub account
- Git installed on your local machine

### Quick Setup (GitHub Pages)

1. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "Deploy from a branch"
   - Select `main` branch and `/ (root)` folder
   - Click "Save"

2. **Update Configuration**
   - Edit `_config.yml` and update:
     - `email`: Your actual email address
     - `linkedin_username`: Your LinkedIn username
     - Any other social media handles

3. **Site will be live at**: `https://chandrusankar.github.io`

### Local Development (Optional)

If you want to test locally before pushing:

```bash
# Install Ruby and Bundler first
# Then run:
bundle install
bundle exec jekyll serve

# Visit http://localhost:4000
```

## 📁 Project Structure

```
chandrusankar.github.io/
├── _config.yml          # Site configuration
├── index.md             # Main portfolio page
├── assets/
│   └── css/
│       └── style.scss   # Custom styles
├── Gemfile              # Ruby dependencies
└── README.md           # This file
```

## 🎨 Customization

### Updating Content
- Edit `index.md` to update your portfolio content
- Update social links in `_config.yml`
- Modify colors and styles in `assets/css/style.scss`

### Adding Blog Posts
Create a `_posts` folder and add markdown files with format:
```
YYYY-MM-DD-title.md
```

### Adding Projects
Edit the projects section in `index.md` with your GitHub project links

## 🔧 Technologies Used

- **Jekyll** - Static site generator
- **GitHub Pages** - Hosting
- **Minima Theme** - Base theme
- **Custom CSS** - Modern styling

## 📝 License

This project is open source and available under the MIT License.

## 📧 Contact

- GitHub: [@ChandruSankar](https://github.com/ChandruSankar)
- LeetCode: [escchandru](https://leetcode.com/u/escchandru/)
- Twitter: [@escchandru](https://twitter.com/escchandru)
