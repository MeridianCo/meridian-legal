# meridian-legal

Static legal document hub for the Meridian app. Hosts the privacy policy, terms of service, EULA, and cookie policy as standalone HTML pages served via GitHub Pages.

The docs/ folder contains an update trigger file for each policy,  meaning whenever something changes in how Meridian collects, processes, or shares data, the docs tell you when and which policies need to be updated and why.

## Structure

```
meridian-legal/
  index.html
  policies/
    privacy-policy.html
    terms-of-service.html
    end-user-license-agreement.html
    cookie-policy.html
  docs/
    privacy_updates.md
    tos_updates.md
    eula_updates.md
    cookie_updates.md
```

## Policies

| Policy | URL | Update Triggers |
|---|---|---|
| Privacy Policy | `#privacy` | [When to update](docs/privacy_updates.md) |
| Terms of Service | `#tos` | [When to update](docs/tos_updates.md) |
| EULA | `#eula` | [When to update](docs/eula_updates.md) |
| Cookie Policy | `#cookies` | [When to update](docs/cookie_updates.md) |

## Contact

Legal questions: [meridiancohq@gmail.com](mailto:meridiancohq@gmail.com)