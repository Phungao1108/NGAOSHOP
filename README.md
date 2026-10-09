<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/8a676553-75d8-4548-b2c3-33d231990b89

## Run Locally

**Prerequisites:**  Node.js (18+)

1. Install dependencies:
   `npm install`
2. Run the app:
   `npm run dev`
3. Open the URL Vite prints in the terminal (mặc định http://localhost:3000)

## Build for production / static hosting

`npm run build` sẽ tạo ra thư mục `dist/` chứa các file HTML/CSS/JS tĩnh, có thể mở trực tiếp bằng bất kỳ static server nào (Live Server, Nginx, GitHub Pages, v.v.).
