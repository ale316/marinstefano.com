# marinstefano.com

Single-page site for Stefano Marin, Consulente del Lavoro.

- `docs/` is the live site, published by GitHub Pages (branch `main`, folder `/docs`).
  Edit `docs/index.html` and push; the change is live in a minute or two.
- `docs/CNAME` holds the custom domain.
- `docs/fonts/` contains self-hosted Schibsted Grotesk (SIL Open Font License).

To preview locally:

```bash
python3 -m http.server 8765 --directory docs
```

## DNS (managed at Aruba)

| Name | Type | Value |
|---|---|---|
| `marinstefano.com` | A | `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153` |
| `marinstefano.com` | AAAA | `2606:50c0:8000::153`, `2606:50c0:8001::153`, `2606:50c0:8002::153`, `2606:50c0:8003::153` |
| `www` | CNAME | `ale316.github.io.` |

Mail records (`MX`, `mx`, `mail`, `webmail`, SPF `TXT`) stay on Aruba and must not be changed.
