# Juice Shop Setup Instructions (Kali Linux)

## 1. Install Node.js (correct version for Juice Shop)
```bash
curl -fsSL https://deb.nodesource.com/setup_20.x | sudo -E bash -
sudo apt install -y nodejs
```

## 2. Clone and Run Juice Shop
```bash
git clone https://github.com/juice-shop/juice-shop.git
cd juice-shop
npm install
npm start
```

Visit the app at [http://localhost:3000](http://localhost:3000)

## 3. Tools for Testing
- Browser (Firefox or Chromium)
- OWASP ZAP (Installed via apt or downloaded from OWASP site)
