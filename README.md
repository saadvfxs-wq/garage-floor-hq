# Garage Floor HQ — booking site

Single-page booking website for **Garage Floor HQ** (@garagefloorhq).

## What's here

- `index.html` — the complete site (HTML, CSS and JavaScript in one file)
- `assets/profile.jpg` — the Instagram profile image, used as the brand logo
- `assets/post-1.jpg`, `assets/post-2.jpg` — real photos from the account, used in the gallery

## Booking behaviour

- **Desktop:** a full booking form sits on the right of the hero section.
- **Phones and tablets (≤900px):** the same booking form is pinned to the top of the screen. Tap **+ More details** to open the remaining fields; the panel scrolls inside the fixed bar.

Submitting a request validates the fields, saves it in the browser's `localStorage`, copies the request text, and offers a direct Instagram DM link with the message prefilled. There is no server-side booking backend connected yet — to receive requests automatically, connect the form to an email service or form endpoint.

## View locally

From the project root:

```bat
start-server.bat
```

Then open `http://localhost:8080/garage-floor-hq/index.html`.

## Temporary public preview

The live preview is a Cloudflare quick tunnel pointing at a local Node static server. It stays online only while those background processes run, and the URL changes if the tunnel is restarted.
