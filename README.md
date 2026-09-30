# JobMatch AI — Privacy policy (GitHub Pages)

One static page: `index.html`. Source lives in `src/`.

## Publish (one time)

```bash
gh repo create jobmatch-privacy --public   # if the repo doesn't exist yet
# push contents, then enable Pages from main branch, root path:
gh api --method PUT repos/GASVS/jobmatch-privacy/pages -f src_branch=main -f source="/branches/main"
```

Wait ~1 minute, then: **https://gasvs.github.io/jobmatch-privacy/** — use that URL as `YOUR_PRIVACY_POLICY_URL` in Play Console, App Store Connect, and the in-app policy link.

## Update the policy

Edit `src/index.html`, push to `main`. Pages redeploys automatically (1–2 min).
