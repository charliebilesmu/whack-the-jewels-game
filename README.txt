WHACK THE JEWELS - Juice Runners x Run The Jewels
=================================================
Upload this whole folder (index.html + the assets folder) to any static host.
Keep the folder structure as it is. No build step, no server code.

Before launch, edit the CONFIG block at the top of index.html:
  ENDPOINT     where leads are POSTed (Google Sheets / Klaviyo / webhook). Empty = leads only stored in the player's browser.
  PRODUCT_URL  "Find it" button destination (currently juicerunners.com)
  PRIVACY_URL  privacy policy link (currently juicerunners.com)
  SHARE_URL    link used by the share button (blank = page URL)
  ART_OPACITY  background artwork strength (1 = full, 0.5 = half)

Handy URL flags: ?admin=1 shows the CSV lead download, ?debug=1 exposes test hooks, ?nopause=1 stops auto-pause.
Prize-draw terms are not defined yet: the game says "prize entries" (1 per player + 1 per hand caught).
