### nerln

I build tools, then I publish the thing that checks them.

PhD researcher moving into mechanistic interpretability, with a past in immersive
VR. Everything here runs on a laptop, most of it on macOS, and none of it phones
home.

**What I am building now**

| | |
|---|---|
| [plancia](https://github.com/nerln/plancia) | One board for every task your coding agents have open, a spoken daily recap, and one place to send the work back |
| [claude-codex-bridge](https://github.com/nerln/claude-codex-bridge) | Moves a live coding conversation between Claude Code and Codex, both directions, as a native resumable session |
| [scriba](https://github.com/nerln/scriba) | Voice memo in, speaker labelled document out. Runs whisperX and pyannote locally and remembers who is who next time |
| [molo](https://github.com/nerln/molo) | A local queue for yt-dlp on Mac, Windows and Android |

**How these are written**

Every repository says what it does not do. When a claim can be checked, the check
ships with it: `plancia` carries 96 of them and refuses to cut a release if one
is red, `claude-codex-bridge` refuses to run against a version it has not been
tested against.

That is the whole idea. Anybody can claim a tool works. The interesting part is
handing you the thing that would catch me if it did not.
