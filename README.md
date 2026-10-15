# Mug Ledger

A Torn City mugging dashboard. Log in with a **Full Access** Torn API key and it charts the cash you've mugged (and had mugged from you) over the last 7, 30 or 90 days, or all time.

It runs entirely in your browser: the key is only sent to `api.torn.com` and is forgotten when you close the tab, unless you tick **Keep me signed in on this device**. Then the key is saved in that browser and the site logs you straight in and pulls new mugs each time you open it; **Log out** forgets it. Nothing is stored on a server. Your mugging history (never the key) is saved in your browser so it only has to be pulled from Torn once; later visits fetch only new mugs.

## Admin page

Player **3292901** gets an **Admin** button (or open the site with `#admin` at the end of the address). Other players share a **Custom** Torn key with only the `user › log` selection; the admin adds each key, and the page pulls every player's mugs straight from Torn, with totals per player and a full dashboard for each. The keys and their mugs are stored only in the admin's browser. A shared key can read all of that player's activity logs, so players should know what it's for, and can delete it in Torn at any time to stop sharing.

Served with GitHub Pages from the `mug-ledger` branch.
