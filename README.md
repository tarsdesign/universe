<h3  style="display:flex; gap:5px;">
  <svg width="25" height="25" viewBox="0 0 36 36" fill="none" 
   xmlns="http://www.w3.org/2000/svg">
    <g clip-path="url(#clip0_780_3722)" >
      <path d="M17.7308 7.91863C19.8161 7.91612 21.8556 8.53589 23.5922 9.69987L27.0685 6.19608C24.3817 4.14327 21.1031 3.03223 17.732 3.03223C14.361 3.03223 11.0823 4.14327 8.39555 6.19608L11.8682 9.69865C13.608 8.54062 15.6461 7.92181 17.7308 7.91863Z" fill="black"/>
      <path d="M7.10178 18.6355C7.10026 16.5325 7.7144 14.4758 8.86722 12.7233L5.38848 9.21582C3.35159 11.9255 2.24915 15.2324 2.24915 18.6324C2.24915 22.0324 3.35159 25.3393 5.38848 28.049L8.86359 24.5452C7.71118 22.7935 7.09821 20.7374 7.10178 18.6355Z" fill="black"/>
      <path d="M17.7308 29.3515C15.6455 29.3537 13.6062 28.734 11.8695 27.5703L8.39435 31.0741C11.0803 33.1288 14.3593 34.2411 17.7308 34.2411C21.1024 34.2411 24.3814 33.1288 27.0673 31.0741L23.591 27.5703C21.8547 28.7341 19.8157 29.3538 17.7308 29.3515Z" fill="black"/>
      <path d="M30.0707 9.22168L26.5944 12.7255C27.7465 14.4775 28.361 16.5331 28.361 18.6352C28.361 20.7374 27.7465 22.7929 26.5944 24.5449L30.0707 28.0487C32.1086 25.3406 33.2118 22.0346 33.2118 18.6352C33.2118 15.2358 32.1086 11.9298 30.0707 9.22168Z" fill="black"/>
      <path d="M36 0C33.5349 2.90352 31.0007 5.74592 28.4423 8.55775C27.1691 9.971 25.8705 11.3598 24.5852 12.7596L20.6894 16.9248L16.7547 21.0533L14.7722 23.1059L13.7804 24.1292L12.7813 25.1463C10.1137 27.8616 7.4328 30.5524 4.67551 33.1759C7.13937 30.2712 9.67355 27.43 12.2332 24.6182L13.1911 23.5619L14.1611 22.513L16.089 20.4163L19.9873 16.2524L23.922 12.1239C25.2461 10.7583 26.5544 9.38174 27.8954 8.03084C30.5557 5.31558 33.2439 2.62478 36 0Z" fill="black"/>
      <path d="M21.7043 13.0674C20.0067 15.0821 18.2534 17.0492 16.4843 18.9967C15.604 19.9747 14.7056 20.9368 13.8168 21.9063L11.1128 24.7866L8.38707 27.64C7.46797 28.5814 6.55978 29.5325 5.63099 30.4641C3.78309 32.3382 1.91822 34.194 0 35.9997C1.69754 33.9862 3.44965 32.0179 5.21994 30.0741C6.09902 29.096 6.99872 28.1351 7.88751 27.1657L10.5866 24.2854L13.3136 21.4332C14.2315 20.4906 15.1409 19.5407 16.0697 18.6079C17.9175 16.7289 19.7836 14.8731 21.7043 13.0674Z" fill="black"/>
    </g>
    <defs>
      <clipPath id="clip0_780_3722">
        <rect width="36" height="36" fill="white"/>
      </clipPath>
    </defs>
  </svg>
  UNIVERSE Monorepo
</h3>

This is a **TurboRepo**-powered monorepo containing multiple applications and packages designed to power the Tars Universe ecosystem. Built with performance, scalability, and developer experience in mind.

---

## 📁 Monorepo Structure

```
.
├── apps/                  # Full-stack or frontend applications
│   ├── admin
│   ├── assets-web
│   ├── social-network
│   ├── tars-industries
│   └── wallet
├── packages/              # Shared packages and modules
│   ├── assets
│   ├── config
│   ├── context
│   ├── crop-tool
│   ├── models
│   ├── services
│   ├── ui
│   └── utils
├── turbo.json
├── pnpm-workspace.yaml
├── package.json
├── README.md
```

---

## 🚀 Getting Started

### 1. Install dependencies

```bash
pnpm install
```

### 2. Run all apps in parallel (development)

```bash
pnpm dev
```

This uses [Turborepo](https://turbo.build/repo) to intelligently cache and run tasks across the monorepo.

---

## 📦 Apps

| App Name          | Description                       |
| ----------------- | --------------------------------- |
| `admin`           | Admin dashboard for internal use  |
| `assets-web`      | Asset viewer/manager UI           |
| `social-network`  | Core social platform              |
| `tars-industries` | Primary business-facing product   |
| `wallet`          | Wallet for transactions or tokens |

---

## 🧩 Packages

| Package     | Purpose                                     |
| ----------- | ------------------------------------------- |
| `assets`    | Shared media or image assets                |
| `config`    | Centralized config (Tailwind, ESLint, etc.) |
| `context`   | Shared React contexts                       |
| `crop-tool` | Image cropping utility                      |
| `models`    | Shared schemas and data types               |
| `services`  | API and backend service logic               |
| `ui`        | Reusable UI components                      |
| `utils`     | General utility functions                   |

---

## 🧪 Versioning and Branch Strategy

We follow a staged versioning model to iterate and experiment while moving toward a production-ready release.

| Version       | Description                                                                   |
| ------------- | ----------------------------------------------------------------------------- |
| `v1.0.0`      | Unfinished MVP with integrated frontend and backend technologies              |
| `v1.1.0`      | Adds a demo project mechanism to the unfinished MVP                           |
| `v2.0.0`      | Experimental version focused only on frontend with basic features             |
| `release/1.0` | **Current active branch for production development**. Intended for deployment |
| `main`        | Production-ready codebase. Developers clone from here to contribute           |

### 🧑‍💻 Contributing

To contribute:

1. Clone the repository.
2. Checkout from the `main` branch.
3. Create a new branch:

   ```bash
   git checkout -b features/[feature-name]
   ```

4. Submit a pull request for review and merge.

Help us grow the **Tars Universe** — one feature at a time. 🚀

---

## 🛠️ Tooling

- **Turborepo** – Monorepo orchestration
- **PNPM** – Efficient package management
- **React + TailwindCSS** – Frontend stack
- **ESLint + Prettier** – Code quality and consistency
- **Typescript** – Static type checking

---

## 📄 License

[Proprietary](./LICENSE)

---

> Built with ❤️ by TARS INDUSTRIES
