# Shift Studio

Shift Studio is a high-energy fitness booking site for class discovery, live availability, time slot selection, member details, booking creation, and confirmation flows.

This website is powered by Wix Headless and built using [wix-headless.dev](https://www.wix-headless.dev).

## Links

- Live site: [https://shiftstudio.store/](https://shiftstudio.store/)
- Source: [https://github.com/wix-incubator/shiftstudio](https://github.com/wix-incubator/shiftstudio)
- Wix site ID: `00cf9cae-9576-4233-9c9f-0a42a7b09ca9`

## What It Showcases

- A custom Astro class booking journey backed by Wix Bookings.
- Service discovery, availability lookup, and class slot selection.
- Booking creation from a custom front end.
- Paid class/session handoff through Wix eCommerce checkout.
- Redirect handling for checkout and confirmation flows.
- Public `robots.txt` and `llms.txt` configured through Wix SEO txt APIs.
- Deployment with `wix release`.

## Wix Solutions Used

- Wix Headless Site for the managed site/runtime foundation.
- Wix Bookings for classes, services, availability, and booking creation.
- Wix eCommerce for paid session checkout.
- Wix Redirects for checkout/confirmation redirects.

## Wix SDKs And Packages

- `@wix/astro`
- `@wix/astro-pages`
- `@wix/sdk`
- `@wix/bookings`
- `@wix/ecom`
- `@wix/redirects`

## Local Development

Create a local env file from `.env.example` or run the Wix CLI env setup for the connected site.

```bash
npm install
npm run dev
```

## Build And Release

```bash
npm run build
npm run release
```
