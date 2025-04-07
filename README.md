Minimal reproduction of a content-length-mismatch with vite + react + mui + sass when accessing a dev server on Android emulator 

To start run the following commands within `/my-app/`:

1. npm install
2. npm run tailwind
3. npm run dev

Confirm the website loads into the browser.
Run an Android emulator, and use the Chrome browser.
- Use the device inspector to see the network tab to have visibility of the error

Navigate to the dev site (e.g., localhost:port -> 10.0.2.2:port)

The site will either:
- Work initially, and fail on subsequent reloads
- Not work at all
