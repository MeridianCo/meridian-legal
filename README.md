# meridian-legal

Static legal document hub for the Meridian app. Hosts the privacy policy, terms of service, EULA, and cookie policy as standalone HTML pages served via GitHub Pages.

## Structure

```
meridian-legal/
  index.html
  policies/
    privacy_policy.html
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

## Updating a Policy

1. Edit the relevant file in `policies/`
2. Update the "Last updated" date at the top of the document
3. Consult the relevant update trigger doc above to confirm the change warrants an update
4. Commit and push — GitHub Pages deploys automatically

## Contact

Legal questions: [meridiancohq@gmail.com](mailto:meridiancohq@gmail.com)