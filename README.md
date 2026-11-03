<div align="right" lang="he">ב״ה</div>

# Portfolio — working demos

The hub page for Colin David Olivier: three clickable demos of systems I designed and shipped,
and a short account of how the work behind them maps to AI deployment, field engineering and
solutions architecture. Ramat Yishai, Israel; open across Israel and remote.

**[▶ colinolivier.vercel.app](https://colinolivier.vercel.app)**

| Demo | Live | Source |
|---|---|---|
| Restaurant ordering & delivery | [open](https://demo-restaurant-ordering.vercel.app) | [repo](https://github.com/Neuralowkey/demo-restaurant-ordering) |
| LeadGraph — researcher lead intelligence | [open](https://demo-leadgraph.vercel.app) | [repo](https://github.com/Neuralowkey/demo-leadgraph) |
| Yeshiva Operating System | [open](https://demo-yeshiva-os.vercel.app) | [repo](https://github.com/Neuralowkey/demo-yeshiva-os) |

Also public: [Mission Control](https://github.com/Neuralowkey/mission-control), the agentic
pipeline that runs my job search.

Every demo runs on invented data. No client information, code history, branding or
configuration is carried into any of these repositories.

## Editing

One `index.html` with inline CSS — no build step, no dependencies. English lives in the
markup; the Hebrew for every `data-i18n` key lives in the `HE` dictionary in the script at the
bottom, so change both together. Edit it and redeploy:

```bash
vercel --prod
```
