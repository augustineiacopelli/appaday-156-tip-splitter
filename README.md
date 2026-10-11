# Tip Splitter

**AppADay 156** &middot; Utility &middot; [Live app](https://augustineiacopelli.github.io/appaday-156-tip-splitter/) &middot; [AppADay Portfolio](https://augustineiacopelli.github.io/appaday/)

Tip Splitter turns a restaurant check into an even split in seconds. Enter the bill, tap a 15, 18, 20, or 25 percent chip or type your own, and set the party size. The tip, grand total, and each share update live, and a round up toggle lifts every share to the next whole dollar and shows the true tip.

## How it works

Type the bill total on the decimal keypad. Pick a tip with one of the four preset chips, or type any percent up to 100 (two decimals allowed) in the Custom field. Use the minus and plus buttons to set how many people are splitting, from 1 to 99. The receipt card updates on every keystroke with the subtotal, the tip, the grand total, and each person's share in large type.

When a total does not divide evenly, the app says exactly who pays the extra cent, for example 1 pays $39.34 and 2 pay $39.33, so the shares always add up to the check. Turn on Round up each share and every share rises to the next whole dollar. The extra goes to the tip, and the receipt shows how much rounding added and the resulting effective tip percent.

All money math runs in integer cents, and tip percents are held in hundredths of a percent, so there are no floating point surprises.

## Settings

The gear in the header opens Settings, where you can set the default tip percent the app opens with and choose a currency symbol (dollar, euro, pound, yen, rupee, won, real, krona, or franc). Settings are saved in your browser's localStorage. Reset everything clears the saved settings and the current check after a second confirming tap.

## Home screen

Add it to an iPhone or Android home screen and it launches full screen as Tip Splitter with its own icon.

## Built with

One self-contained `index.html` of vanilla HTML, CSS, and JavaScript, with Space Grotesk and IBM Plex Mono from Google Fonts. No frameworks, no build step, no network calls beyond the fonts.

Part of AppADay, one complete web app shipped every day.
