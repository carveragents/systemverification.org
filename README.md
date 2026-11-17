# systemverification.org

Source for [systemverification.org](https://systemverification.org), home of the **System Verification Engineering (SVE) Manifesto**.

> Verify every change. Keep verifying the system. Learn from every outcome.

## Contents

| File | Purpose |
|---|---|
| `index.html` | The manifesto site (single static page) |
| `SVE_Manifesto_v1_0.pdf` | PDF version of the manifesto |
| `SIGNATORIES.md` | People who support the manifesto |
| `CONTRIBUTING.md` | How to sign and propose changes |
| `CNAME` | Custom domain for GitHub Pages |
| `.nojekyll` | Serve files as-is, skip Jekyll |

## Sign the manifesto

See [CONTRIBUTING.md](CONTRIBUTING.md). In short, open a pull request adding one line to `SIGNATORIES.md`:

```
- Your Name, Role, Organization
```

## Suggest changes

Open an issue for substantive changes to the text. Versions are tracked in the changelog below.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Changelog

- **v1.0** (16 November 2026): Initial release.

## License

The manifesto text is licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
