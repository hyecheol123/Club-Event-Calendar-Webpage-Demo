# Club Event Calendar Webpage

[![Code Style: Google](https://img.shields.io/badge/code%20style-google-blueviolet.svg)](https://github.com/google/gts)

Repository for Club Event Calendar.
Originally built for Busan Developers Club (BGM): [BusanDevelopers/BGM-Event-Calendar-Webpage](https://github.com/BusanDevelopers/BGM-Event-Calendar-Webpage).

백앤드 API는 이 [리포지토리](https://github.com/BusanDevelopers/BGM-Event-Calendar-API)를, 지원하는 API 목록과 기능은 [API 문서](https://busandevelopers.github.io/BGM-Event-Calendar-API-Documentation/)를 참고해 주십시오.

## Scripts

Here is the list for npm/yarn scripts.
These are used to lint, test, build, and run teh code.

1. `lint`: lint the code.
2. `lint:fix`: lint the code and try auto-fix.
3. `dev`: Run webpack dev server
4. `build`: Build website based on the `browserslint`. (destination: `dist` Directory)

No tests are implemented.
To enforce code styling, inspect and lint the codes on commit and push.

## Dependencies/Environment

Developed and tested with `Ubuntu 20.04.3 LTS` and `Node v16.13.1`.

TypeScript React Development environment is set up manually with `ESLint`, `Prettier`, `WebPack`, and `Babel`, rather than using ohter Boilerplate codes (such as `create-react-app`).
For Code styling rules and deploy configurations, please refer to the setup files.

Used React 17.0.2 and React Router 6.1.1.
Also utilize Material UI (MUI) Library (v5.2.5) for elegant design.
