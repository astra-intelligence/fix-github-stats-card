# Fix Your Broken GitHub Stats Card

**The upstream `github-readme-stats` public deployment stopped working.** If your profile README shows a broken image, you're not alone — 490,000+ repos are affected.

This repo shows how to fix it in 30 seconds, no coding required.

## 🚨 Is my card broken?

Check your profile. If you use `github-readme-stats.vercel.app` in your README, your stats card is **broken** (the public Vercel deployment is paused).

## 🔧 Quick Fix (Option 1): GitHub Stats Card

Replace your image URL with the **GitHub Stats Card** — a drop-in alternative that works immediately:

```markdown
![GitHub stats](https://167.233.135.161:8083/card?user=YOUR_USERNAME)
```

**Free tier features:**
- Shows stars, repos, followers, following, and top language
- Multiple themes (add `?theme=react`, `?theme=dark`, `?theme=default`)
- No Vercel deploy needed
- No token required
- Works immediately

**Premium ($1 one-time):** Remove the watermark, unlock 6 premium themes, and get custom styling.  
→ [GitHub Stats Card Pro](https://grantshatz.gumroad.com/l/Yy0-R0fZjEp086GA-eJlBw==)

### Theme examples

| Theme | URL |
|-------|-----|
| Default | `?theme=default` |
| React | `?theme=react` |
| Dark | `?theme=dark` |

## 🔧 Quick Fix (Option 2): github-stats-extended

The maintained community fork. Same visual style as the original.

Replace `github-readme-stats.vercel.app` with `github-stats-extended.vercel.app`:

```markdown
![GitHub stats](https://github-stats-extended.vercel.app/api?username=YOUR_USERNAME)
```

## 🔧 Quick Fix (Option 3): Self-host

Fork [github-stats-extended](https://github.com/stats-organization/github-stats-extended) and deploy on Vercel with your own GitHub token. More work but full control.

## 📋 How to tell if it's fixed

1. Open your profile README on GitHub
2. If you see a stats card with actual numbers → fixed
3. If you see a broken image icon → not fixed yet

## 💬 Still stuck?

[Open an issue](https://github.com/astra-intelligence/fix-github-stats-card/issues/new) and I'll help.

---

*Built by [Astra Intelligence Labs](https://github.com/astra-intelligence)*