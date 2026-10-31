# Eugenio Nerelli

I'm a developer and PhD student at the Universitat de València, in the NIMLab group, where my research is on immersive virtual reality experiences for cultural heritage. I make apps for the web and the Mac, and tools for coding agents. My site is [nerln.github.io](https://nerln.github.io/).

<table>
<tr>
<td width="50%" valign="top">
<a href="https://nerln.github.io/ferro/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/ferro-dark.png">
<img src="https://nerln.github.io/highlights/ferro.png" alt="FERRO. A web app for workouts: plans, sets and the gym turnstile badge. Shows the start of its site, with the app on a phone in a hand." width="100%">
</picture>
</a>
</td>
<td width="50%" valign="top">
<a href="https://zaffo-cirrus.nerln.workers.dev/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/zaffo-dark.png">
<img src="https://nerln.github.io/highlights/zaffo.png" alt="ZAFFO. A 3D platformer for one or two, with Gianmattia Barone. In progress. Shows the title screen of the game, a blue dragon over a castle and floating islands, with the buttons to play alone or with a friend." width="100%">
</picture>
</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://nerln.github.io/tamiz/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/tamiz-dark.png">
<img src="https://nerln.github.io/highlights/tamiz.png" alt="tamiz. Valencian aid and grants. Your answers never leave the browser. Shows the start page, in Spanish, with the headline about aid and grants you may qualify for and a button to start." width="100%">
</picture>
</a>
</td>
<td width="50%" valign="top">
<a href="https://nerln.github.io/falla/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/falla-dark.png">
<img src="https://nerln.github.io/highlights/falla.png" alt="falla. Finds the frame where a 3D scene or a video breaks. In the browser. Shows its page, with the headline about finding the frame where a 3D scene breaks and a sample frame with the first problem outlined." width="100%">
</picture>
</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://woowoo-calendar.pages.dev/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/woowoo-dark.png">
<img src="https://nerln.github.io/highlights/woowoo.png" alt="WooWoo. A calendar with two views of the day: dates and thirteen moons. Shows the start of its site, with the headline about living by thirteen moons and a card that reads the day as a day of the fourth moon." width="100%">
</picture>
</a>
</td>
<td width="50%" valign="top">
<a href="https://nerln.github.io/reflip/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/reflip-dark.png">
<img src="https://nerln.github.io/highlights/reflip.png" alt="reflip. Removes text watermarks with a local model, then checks they are gone. Shows the Mac window with a text to rewrite, the rewritten result and the figures measured afterwards." width="100%">
</picture>
</a>
</td>
</tr>
</table>

[All projects](https://nerln.github.io/projects/)

### How these are written

I build tools, then I publish the thing that checks them.

When a claim can be checked, the check ships with the code. plancia runs 4956 checks before every push, against a throwaway archive that never touches yours, and its release script refuses to build a release if any of them fails. claude-codex-bridge writes a session only for CLI versions it has been verified against, and ships the drift check to run after either CLI updates.

That is the whole idea. Anybody can claim a tool works. The interesting part is handing you the thing that would catch me if it did not.

The clearest example is not a tool. [placa](https://nerln.github.io/placa/) forecasts a reality show from the vote splits the broadcaster reads out on air. It also refits itself backwards, each gala using only the galas before it, and reports the result on the page even though it is bad: over the eight galas it could test, up to 14 September 2026, its ranking put the person who actually left 4.88th on average when chance would put them 3.44th. Zero hits out of eight, p = 0.0091 in a one-sided permutation test. The test is on the page, and the data is in `data/retro.json` of the repository.
