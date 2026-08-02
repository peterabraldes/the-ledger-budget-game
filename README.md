# The Ledger: A Real Life Budgeting Game

An interactive budgeting game for young adults (ages 18 to 25) learning how to manage a real paycheck. Everyone in the game lives in Philadelphia and starts on 15 dollars per hour, full time. Players make thirteen choices across needs, wants, and savings, watch their money run down in real time, and see how consistent saving and investing grow over 10 or 40 years.

Built for the Insight Engine budgeting seminar.

## Play it

The game is a single self contained HTML page. There is no build step and no dependencies.

- **Locally:** open `index.html` in any modern browser.
- **On a phone:** host the page (see below) and open the link on your device. The layout is fully responsive.

Up to six people can play, each setting their own wage and weekly hours, and the final screen compares everyone.

## Host it as a website

Because `index.html` is one self contained file, hosting is quick. Any of these work:

- **GitHub Pages:** enable Pages on this repository (Settings, then Pages, then deploy from the `main` branch). Your public URL will be `https://<username>.github.io/<repo>/`.
- **Netlify:** drag `index.html` onto [netlify.com/drop](https://app.netlify.com/drop).
- **Cloudflare Pages** or **Vercel:** connect this repository and deploy the static page.

## How the numbers work

- **Take home pay** is estimated from the chosen wage and hours after FICA, federal income tax, Pennsylvania income tax, and the Philadelphia resident wage tax.
- **Costs** (rent, food, transit, and so on) are fixed dollar estimates for Philadelphia in 2025, so a higher wage buys more room in the budget rather than higher prices.
- **Growth projections** assume steady monthly contributions at 4 percent for savings and 7 percent for investing, compounded monthly.

The classic budgeting target shown in the game is 70 percent needs, 20 percent wants, and 10 percent saved.

## Files

- `index.html` is the deployable web page. This is what you host.
- `budget-game.html` is the same game body used to publish the Claude artifact version.

## Disclaimer

This is a teaching tool. The figures are realistic estimates for learning, not financial advice.

## Credits

Presented by Insight Engine. "Ignite your data. Uncover the insight." [insightengine.nz](https://insightengine.nz/)
