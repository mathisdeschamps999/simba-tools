# Simba tools website

Static one-page site for Simba tools, publisher page for practical Unity Editor tools.

The current product presented here is **Asset Library Organizer & URP Inspector**.

## Local preview

Open `index.html` in a browser.

Or, from this folder, start a small local HTTP server if you have one available. For example:

```
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Publish with GitHub Pages

1. Create a GitHub repository.
2. Push this folder to the `main` branch.
3. Open the repository **Settings**.
4. Open **Pages**.
5. Set **Source** to **GitHub Actions**.
6. Wait until the **Deploy GitHub Pages** workflow finishes.

The workflow file is `.github/workflows/pages.yml`. It uses the official GitHub Pages actions and does not require a personal token in the repository.

The Asset Store button on the page is still an in-page link. After the product is published, replace it with the Unity Asset Store product URL. The placeholder is marked in `index.html`.

## Contact

mathisdeschamps999@gmail.com
