# Shadow Moses Systems Launch Notes — 2026-03-28

## Public launch state
A temporary public version of the site was launched via localhost.run tunnel.

### Public URL
- `https://8ecad68c83b91f.lhr.life`

### Verified public path
- Landing page loads publicly
- `Get the breakdown` resolves publicly to:
  - `https://8ecad68c83b91f.lhr.life/breakdown.html`

## Important note
This is a **temporary tunnel URL**, not a permanent production host.

Use cases right now:
- share with girlfriend tonight
- satisfy immediate Stripe website requirement
- allow quick external review

Not ideal for long-term:
- URL is ephemeral
- tunnel depends on the local host + tunnel process remaining up
- should later be replaced with a stable host/domain

## Processes currently backing the public site
- local Python server on port `4174`
- localhost.run SSH tunnel forwarding to `localhost:4174`

If either stops, the public link dies.

## Next recommended upgrade
Move from temporary tunnel to a stable public host (GitHub Pages / Netlify / Vercel / similar) once the immediate Stripe and share-link needs are satisfied.
