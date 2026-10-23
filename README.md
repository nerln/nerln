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
<a href="https://nerln.github.io/tamiz/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/tamiz-dark.png">
<img src="https://nerln.github.io/highlights/tamiz.png" alt="tamiz. Valencian aid and grants. Your answers never leave the browser. Shows the start page, in Spanish, with the headline about aid and grants you may qualify for and a button to start." width="100%">
</picture>
</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://aprendecontigo.pages.dev/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/contigo-dark.png">
<img src="https://nerln.github.io/highlights/contigo.png" alt="contigo. Learn a language, with you. Alone first, then with someone you love. Shows the start of its site, with the headline about studying alone first and then with someone, beside a phone showing the app." width="100%">
</picture>
</a>
</td>
<td width="50%" valign="top">
<a href="https://nerln.github.io/scriba/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/scriba-dark.png">
<img src="https://nerln.github.io/highlights/scriba.png" alt="scriba. Voice memo in, document with named speakers out, all on your machine. Shows the Mac window where the two voices of a recording are named, with the transcript below." width="100%">
</picture>
</a>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<a href="https://nerln.github.io/plancia/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/plancia-dark.png">
<img src="https://nerln.github.io/highlights/plancia.png" alt="plancia. A Mac board for Claude Code and Codex tasks, with a spoken recap. Shows the Today window on the Mac, with a recap of the day and the next tasks by project." width="100%">
</picture>
</a>
</td>
<td width="50%" valign="top">
<a href="https://nerln.github.io/argano/">
<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://nerln.github.io/highlights/argano-dark.png">
<img src="https://nerln.github.io/highlights/argano.png" alt="argano. Repairs a video that will not play, in the browser. Nothing is uploaded. Shows its page in the browser, with a drop area for a video that will not play and a note that the video is not uploaded." width="100%">
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
