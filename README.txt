# MXW01 Printer Web App

This is a tiny single-page Web Bluetooth app made specifically for the MXW01.

## Important
- Web Bluetooth requires a browser that supports Web Bluetooth and a secure HTTPS page.
- On Android, use a compatible browser such as Chrome. Amazon Silk may not expose Web Bluetooth.
- Turn the MXW01 on before pressing Connect.
- The app connects directly to the printer; it does not use the printer manufacturer's account/app.
- The printer is treated as 384 pixels wide and the image is converted to 1-bit thermal data.

## GitHub Pages
1. Create a new GitHub repository.
2. Upload `index.html`.
3. Open Settings -> Pages.
4. Choose "Deploy from a branch", select `main` and `/ (root)`, then Save.
5. Open the Pages URL in a Web Bluetooth-compatible browser.
