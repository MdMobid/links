# 🔗 Simple URL Shortener Using GitHub Pages

A lightweight, customizable URL shortener using **GitHub Pages** and **client-side redirection** via query strings. Fork, deploy, and instantly create your own redirect service like:

```
https://<username>.github.io/links?id=your_key
```

---

## 🚀 Features

- **No Server Needed**: Fully static site using GitHub Pages and client-side redirection.
- **Instant Deployment**: Just fork and let GitHub Actions handle the deployment.
- **Custom Short Links**: Redirect based on `?id=` query parameters.
- **Editable JSON**: Manage redirects via a simple `links.json` file.

---

## 🌐 Live Usage Example

After deployment, visiting:

```
https://<your-username>.github.io/links?id=url1
```

...will redirect to the corresponding destination defined in your `links.json`, like:

```json
{
  "url1": "https://example.com/page1",
  "url2": "https://example.com/page2"
}
```

---

## 🚀 Getting Started

### Step 1: ⭐ Star This Repository

Click the **Star** button in the top right to show support.

### Step 2: 🍴 Fork This Repository

Click the **Fork** button to create your own copy of this repo.

### Step 3: 🛠 Enable GitHub Pages

GitHub Actions will automatically deploy your site. To confirm:

- Go to **Settings > Pages**
- Set the source to the `gh-pages` branch and root (`/`)

### Step 4: 📝 Add Your Redirect Links

Edit the `links.json` file in the root of the repository. Format:

```json
{
  "url1": "https://example.com/page1",
  "url2": "https://example.com/page2"
}
```

### Step 5: 🔗 Access Your Links

Once deployed, use:

```
https://<your-username>.github.io/links?id=url1
```

This will redirect to `https://example.com/page1`.

---

## 🛠 Technologies Used

- HTML
- JavaScript
- GitHub Pages
- GitHub Actions

---

## 🥇 Credits

**Built with ❤️ by [MdMobid](https://github.com/MdMobid)**
