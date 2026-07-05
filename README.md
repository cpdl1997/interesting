# 🛠️ deployment.yaml — run me

Hey you. 👋

There's a tiny web app in this repo. It looks like a little code editor with a
green **▶ Run** button. That's the whole interface. Go ahead — open it and press Run.

## The catch

When you hit Run, things... won't go smoothly. You'll meet one of the most
famous errors in all of DevOps — the kind that has ruined many a deploy and
many a coffee. Nothing is actually broken with your machine. The little config
just has a mistake in it.

**Your quest:** read the terminal output, find the mistake in the code, fix it,
and press Run again.

## Stuck? That's allowed.

- Tap **Need a hint?** — the hints get more specific each time you press it.
  The last one basically hands you the answer, so use them at your own pace.
- Tap **Reset** to put the original file back if you tinker yourself into a corner.
- Keyboard shortcut: **⌘/Ctrl + Enter** runs the code too.

When the deploy finally goes green and the pod reads `1/1 Running`... well.
You'll see. I'm not going to spoil it. 😊

## How to run it

Just open the app in a browser — there's nothing to install. If someone sent
you a link, click it. If you have the files, open `index.html`.

## Under the hood (for the curious)

It's a single HTML file. The YAML you edit is validated by a **real** YAML
parser (`js-yaml`) running right in your browser, so the error you see is a
genuine parse/deploy failure, not a fake one. No servers, no tracking, no
build step. Everything runs locally in the page.

---

*Made with care. Take your time, and enjoy the puzzle.* 💛
