# market_online — Demo

market_online is a small web demo that showcases a simple online marketplace. The repository contains static HTML/CSS pages that demonstrate buyer, seller, and admin flows and a few themed pages used for the project.

## What's in `market_online/`

- `index.html`: Landing / entry page for the demo.
- `login.html`: Simple login form (static demo).
- `signup.html` and `seller_signup.html`: Signup pages for buyers and sellers.
- `buyer_products.html`: Product listing view for buyers.
- `seller_dashboard.html`: Seller dashboard (static mockup).
- `seller_product_upload.html`: Seller product upload form (static mockup).
- `admin_dashboard.html`: Admin dashboard mockup.
- `user_page.html`: Example user account page.
- `fin3.html`: A final/event page used in the demo.
- `market_online_welcome.html` + `market_online_welcome.css`: A themed welcome page and stylesheet.
- `cameroon_theme.css`: An alternate theme stylesheet used by some pages.
- `pactpyth/`: Additional demo assets or scripts (folder).

Each page is a static HTML file (no backend). The files show layout, navigation, and simple forms to illustrate how flows could work in a full application.

## Preview locally

1. From the project root run a small HTTP server (recommended so relative links and assets load correctly):

```
cd /workspaces/market_online
python3 -m http.server 8000
```

2. Open a browser and visit:

- `http://localhost:8000/market_online/index.html` — demo landing page
- or open any other file under `market_online/`, for example `http://localhost:8000/market_online/market_online_welcome.html`.

You can also open the HTML files directly in a browser from the filesystem, but a local server is preferred.

## Notes & next steps

- This repository is a static prototype intended for presentation and rapid UX iteration.
- To turn this into a working app you can:
  - Add a backend (Node, Flask, Django, etc.) for authentication and data storage.
  - Replace static forms with real API calls and persistent storage.
  - Integrate a build system and package manager for assets.

## Contributing

Feel free to open issues or submit pull requests to add features, improve styling, or wire a backend.

## License

This project is provided as-is for market_online/demo use. Add a license of your choice if you plan to publish or distribute it broadly.

---
Author: `monpheibel`

