# API Response AES Decryptor

A static, browser-based AES-CBC API response decryptor.

## Deploy

### Netlify
1. Upload the `index.html` file to Netlify Drop.
2. Netlify will provide a shareable `.netlify.app` URL.

### GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html` to the repository root.
3. Go to Settings → Pages.
4. Choose Deploy from a branch → `main` → `/ (root)`.
5. Save and use the generated GitHub Pages URL.

## Privacy

The application is designed to perform the cryptographic operations in the browser using the Web Crypto API. This package does not add a backend or analytics service.

Do not enter secrets into any public/shared instance unless you understand the trust and security implications of the browser/device and hosting environment.

## Files

- `index.html` — complete deployable application.
