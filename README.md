# TGPU Wellness

Standalone TGPU Digital Ecosystem application under TGPU Legacy.

- Public website: https://wellness.tgpu.my/
- Cloudflare Worker: `tgpu-wellness`
- Production source: `public/`
- Cloudflare deployment: `npx wrangler deploy --config wrangler.jsonc`

## Migration
The site is copied without deleting the original from `MamduhSaffin/tgpu-ecosystem`, using the single-use GitHub Action in `.github/workflows/import-wellness.yml`. The original master portal and Azure backups remain unchanged.

Do not bind the live domain until the isolated Worker deployment and full site have been verified.
