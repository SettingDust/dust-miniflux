# Miniflux

Deploy a self-hosted version of [Miniflux](https://miniflux.app) on Railway. Internally it uses a PostgreSQL database to store the data.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/lvcwAq?referralCode=Fe9NGe)

## ✨ Features

- Miniflux
- PostgreSQL deployed on Railway but can use external databases too. Just set the ENV variable `$DATABASE_URL` with connection parameters. See [lib/pq](https://pkg.go.dev/github.com/lib/pq#hdr-Connection_String_Parameters) for more details.

## 💁‍♀️ How to use

- Click the Railway button 👆
- Add the required environment variables
- Deploy

## Themes

To install a theme: Go to **Settings > Custom CSS** and paste the contents there

1. https://gist.github.com/TaylanTatli/c1c725691a69eeb9c5f5889371317ed5
2. https://github.com/fengkx/miniflux-theme-pure
3. https://codeberg.org/zoenglinghou/miniflux-theme

## 📝 Notes

- Source repo: https://github.com/miniflux/v2/
- Docs: https://miniflux.app/
