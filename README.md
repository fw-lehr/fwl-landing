# FW Lehr Landingpage
Die Webseite besteht aus einer statischen React-Seite, die Links zur eigentlichen Webseite und einigen Social Media Accounts beinhaltet. Außerdem gibt es noch Kontaktinformationen.

Die Webseite ist über https://go.fw-lehr.de zu erreichen.

## Spezielle Weiterleitung 
Auf dem Server (derzeit VPS) ist für den nginx-reverse-Proxy in einer speziellen Datei `go.fw-lehr.de_location` unter `vhosts.d` eine Weiterleitung von `/maibaum-2026` auf ein Formular in der nextcloud eingerichtet, damit man Feedback geben kann.  

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.

