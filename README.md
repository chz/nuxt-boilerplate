# Nuxt Boilerplate

A ready to use Nuxt 3 boilerplate

**Demo**: https://nuxt-boilerplate.onrender.com/

![screenshot](https://github.com/renegadevi/nuxt-boilerplate/blob/e806bae6efec29a19579d7cf76ef683ffe980917/.github/screenshot.png)
![lighthouse](https://github.com/renegadevi/nuxt-boilerplate/blob/e806bae6efec29a19579d7cf76ef683ffe980917/.github/lighthouse.png)



## Setup

### Prerequisites:

- [pnpm](https://pnpm.io/)
- [mkcert](https://github.com/FiloSottile/mkcert) (Optional localhost HTTPS)

### Install dependencies:

```bash
pnpm install
```

### Optional: `.env`

```ini
VITE_BASE_URL="https://localhost:3000/"
```

### Optional: Generate certificate for HTTPS for localhost

```bash
# mkdir certs
cd certs
mkcert localhost
```

## Start local server

### Start development server

```bash
# HTTP
pnpm run dev
# HTTPS
pnpm run dev-https
```

### Start production build server (HTTP)

```bash
# HTTP
pnpm run build;pnpm run preview
# HTTPS
pnpm run build;pnpm run preview-https
```

Check out the [deployment documentation](https://nuxt.com/docs/getting-started/deployment) for more information.


## Nuxt Modules included:
- [eslint](https://nuxt.com/modules/eslint)
- [pinia](https://nuxt.com/modules/pinia)
- [tailwindcss](https://nuxt.com/modules/tailwindcss)
- [i18n](https://nuxt.com/modules/i18n)
- [device](https://nuxt.com/modules/device)
- [devtools](https://nuxt.com/modules/devtools)
- [image](https://nuxt.com/modules/image)
- [google-fonts](https://nuxt.com/modules/google-fonts)
- [color-mode](https://nuxt.com/modules/color-mode)
- [icon](https://nuxt.com/modules/icon)
- [cookie-control](https://nuxt.com/modules/cookie-control)
