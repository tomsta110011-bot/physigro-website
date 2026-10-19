# Codex instructions for Physigro

Work only in this repository. Do not touch CareerValue or any other repository.

## Goal
Finish and visually QA the Physigro Physiotherapy website for Brianna Short in Glen Innes, NSW.

## Non-negotiables
- Preserve the current brand direction, supplied copy, fees, booking URL and clinic contact details unless a real bug requires a change.
- Use the local image assets in this repository. Do not replace them with remote image proxies, generic stock, AI-generated imagery or tiny thumbnails.
- Check all image crops at desktop, tablet and mobile sizes. Photos should look sharp and natural, not stretched or over-cropped.
- Keep `<meta name="robots" content="noindex,nofollow">` and `robots.txt` blocking indexing until the owner explicitly approves launch.
- Keep this site completely separate from CareerValue.

## Expected image mapping
- `bri-speaking.avif`: homepage hero + About Bri
- `general-physio.avif`: general physiotherapy
- `paediatrics.avif`: paediatric physiotherapy
- `pelvic-health.webp`: women's pelvic health
- `physigro-logo.webp`: header/branding

## QA
Before deployment:
1. Run the site locally and open every page.
2. Check desktop, tablet and mobile layouts.
3. Verify every local image loads with correct aspect ratio and no visible blur from upscaling.
4. Check all internal links, phone/email links and the PracSuite booking link.
5. Confirm accessibility basics: alt text, focus states, labels and usable mobile navigation.
6. Keep the current noindex state.

## Deployment
Once the site is visually clean, deploy to the existing Vercel project `physigro-preview` if that project is available to the environment.

Real-world launch checks still required: confirm the exact opening hours with Bri and confirm commercial website consent for any client/child photographs.
