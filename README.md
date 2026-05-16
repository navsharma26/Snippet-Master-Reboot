# snp·try

Code snippet hub (Next.js frontend + Node/Mongo backend). Rebranded from Snippet Master; use GitHub repo name **`snp-try`** if you want the URL to match.

**Rename on GitHub:** open the repo → **Settings → General → Repository name** → set to `snp-try` → Rename. Then clone:

```bash
git clone https://github.com/navsharma26/snp-try.git
cd snp-try
```

Until you rename, clone the current URL:

```bash
git clone https://github.com/navsharma26/Snippet-Master-Reboot.git
```

## Installation

1. Install dependencies in each part of the project as needed, for example:

   ```bash
   cd snippet-master && npm install
   cd ../backend && npm install
   ```

1. Create a `.env` file in the **backend** (server) folder.
2. Add the following environment variables:

- `PORT=8000`
- `MONGO_URI=<your-mongo-uri>`
- `CLIENT_URL=http://localhost:3000`
- `JWT_SECRET=<your-jwt-secret>`

Replace placeholders with your MongoDB URI and a strong JWT secret.

## Development

From `snippet-master/`:

```bash
npm run dev
```

Use **Node 18 or 20 LTS** for Next.js 12 compatibility.

## Contributing

1. Fork the repository and clone it locally.
2. Create a branch for your feature or fix.
