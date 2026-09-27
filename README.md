# PackPal 🧳

**Pack smarter. Travel lighter.**

PackPal builds your holiday packing list for you. Tell it where you're going, when, what you're doing and how you're travelling, and it works out what you actually need (and what you don't).

## What it does

- **Weather-aware lists.** Pulls the forecast for your destination and dates, and changes the list to match. Trips more than 16 days away use the same dates over the last three years until the live forecast is available.
- **Trip types.** Beach, pool, city, nightlife, hiking, skiing, business, wedding, festival and cruise, in any combination.
- **"How many?" counts.** Suggests how many of each thing to pack based on trip length and weather, and you can adjust them.
- **Baggage allowances.** Presets for Ryanair, easyJet, Jet2, TUI, British Airways and Wizz Air, or set your own. Each bag shows how full it is as you tick things off.
- **"You probably don't need".** Things you can leave at home, with the reason.
- **Shopping list, departure checklist and a final "What am I forgetting?" check** before you're marked as packed.
- **Saved trips.** Everything is kept in your browser, so you can come back to it.

## Run it on GitHub Pages

1. Create a new repository and add `index.html`, `favicon.svg`, `og-image.png` and this `README.md`.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

There's no build step. It's a single HTML file.

Once it's live, open `index.html` and change `og-image.png` in the `og:image` tag to the full address, e.g. `https://<your-username>.github.io/<repo-name>/og-image.png`. WhatsApp, Slack and Facebook need the full address to show the preview image.

## Privacy

There are no accounts, cookies or tracking. Trips and lists are saved in your own browser's local storage. The only outside request is to Open-Meteo for the place and weather, which receives the destination name and dates.

## Things to know

- Weather data comes from [Open-Meteo](https://open-meteo.com/) (CC BY 4.0), which is free for non-commercial use. If PackPal ever makes money (ads, affiliate links), you'll need an Open-Meteo commercial plan.
- Baggage allowances change often. The presets were checked in September 2026. Always check your booking.
- Item weights are rough averages for planning, not exact.
- Trips are saved per browser, so a trip planned on your laptop won't appear on your phone.

## Credits

Weather data by [Open-Meteo.com](https://open-meteo.com/).
