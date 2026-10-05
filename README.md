# Tariff Truth

Compare GB energy tariffs against your **real** half-hourly usage instead of estimates.

- Fetches your electricity and gas readings straight from the Octopus Energy API (API key + account number), or reads a CSV export.
- Pulls every Octopus tariff for your region with its real price history, including Agile's half-hourly prices.
- Detects EV charging and works out what each tariff would cost if you moved charging into its cheapest slots.
- Lets you enter tariffs from other suppliers by hand.

Everything runs in your browser. Your API key is sent only to `api.octopus.energy` and is stored only if you tick "Remember on this device".

It's a single static `index.html`, so no build step is needed.
