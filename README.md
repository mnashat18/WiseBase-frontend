# Wisebase Frontend

Angular 21 web app for **Wisebase**, a multi-role workforce management platform (owner, HR, manager, employee). I built Wisebase at DataC and keep improving it.

**Product page:** https://conntinuity.datac.com/

## Screenshots

<img width="49%" alt="Wisebase web app screen 1" src="https://github.com/user-attachments/assets/3d039e30-06c3-416a-bbe6-dea0c70e57c2" />
<img width="49%" alt="Wisebase web app screen 2" src="https://github.com/user-attachments/assets/1da91603-edd7-4e1f-80f2-a06ca8ec6703" />
<img width="49%" alt="Wisebase web app screen 3" src="https://github.com/user-attachments/assets/f1e04610-e53a-4afb-b6b0-a3fe5d597329" />
<img width="49%" alt="Wisebase web app screen 4" src="https://github.com/user-attachments/assets/9003c3ba-132d-4ef2-8b59-ae261f68c11f" />
<img width="49%" alt="Wisebase web app screen 5" src="https://github.com/user-attachments/assets/28695ba7-1ee6-422a-8e63-c8f7161050a3" />

## What the app does

- Role-based interfaces for Owner, HR, Manager and Employee
- Sign-up, login, password reset and workspace invitations
- Workspace and company setup, departments and members
- Readiness requests, alerts, compliance and reports views
- Notifications and responsive layouts

## Tech stack

Angular 21, TypeScript, RxJS, Tailwind CSS, reactive forms, route guards, HttpClient. Tests with Playwright (`e2e/`). Docker and Nginx for deployment.

## How it fits together

The app talks to the Wisebase backend over REST APIs. The backend is Directus on PostgreSQL, and the repo includes the Directus extension used by the web app in `directus-extensions/`. The same backend serves the Flutter mobile app and the AI service.

## Repository layout

| Path | Contents |
| --- | --- |
| `src/` | Angular application source |
| `directus-extensions/` | Directus extension used by the app |
| `e2e/` | Playwright end-to-end tests |
| `docs/` | Project documentation |
| `performance/` | Load test scripts |
| `server/` | Server-side helpers |
| `Dockerfile`, `nginx.conf` | Container and web server setup |

The `*_AUDIT.md`, `WEB_*.md` and `FRONTEND_PRD_AUDIT.md` files in the root are internal review notes.

## Run locally

```bash
npm install
npm start
```

## Related repositories

- [WiseBase-app](https://github.com/mnashat18/WiseBase-app): Flutter Android app
- [WiseBase-ai-server](https://github.com/mnashat18/WiseBase-ai-server) and [WiseBase_ai_v2](https://github.com/mnashat18/WiseBase_ai_v2): Python and FastAPI AI services
- [wisebace-Node-Backend](https://github.com/mnashat18/wisebace-Node-Backend): Node.js backend migration work

## Author

Mohamed Nashat Ghonim, Full-Stack Developer
[LinkedIn](https://www.linkedin.com/in/mohamed-nashat-ghonim/) · [GitHub](https://github.com/mnashat18) · mnashat2508@gmail.com
