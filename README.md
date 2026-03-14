# Stellar Tip Jar – Frontend

A simple open-source web application that allows users to **send tips to creators using the Stellar blockchain**.

This repository contains the **frontend interface** for the Stellar Tip Jar platform. It enables users to view creator profiles, send tips, and track transactions through an intuitive web interface.

The application interacts with a backend API and Soroban smart contracts deployed on the **Stellar Network**.

---

## Project Overview

Stellar Tip Jar is a lightweight platform that allows creators to receive tips directly from supporters using blockchain payments.

Instead of relying on centralized platforms, creators can simply share a link like:

```
https://tipjar.app/username
```

Supporters can then send tips using Stellar tokens.

---

## Repository Architecture

This project is part of a multi-repository architecture:

```
stellar-tipjar
│
├── stellar-tipjar-frontend
├── stellar-tipjar-backend
└── stellar-tipjar-contracts
```

* **Frontend:** User interface for creators and supporters
* **Backend:** API and data indexing service
* **Contracts:** Soroban smart contracts for handling tip payments

---

## Tech Stack

* React / Next.js
* TypeScript
* Stellar SDK
* Tailwind CSS (optional)
* Wallet integration (Freighter)

---

## Features

* Creator profile pages
* Send tips to creators
* Wallet connection
* View tip history
* Simple and clean UI
* Mobile responsive design

---

## Project Structure

```
src
│
├── components
├── pages
├── hooks
├── services
├── utils
└── styles
```

Example responsibilities:

* **components** – reusable UI elements
* **pages** – application routes
* **hooks** – wallet connection and blockchain hooks
* **services** – API communication
* **utils** – helper functions

---

## Getting Started

### 1. Clone the repository

```
git clone https://github.com/your-username/stellar-tipjar-frontend.git
cd stellar-tipjar-frontend
```

### 2. Install dependencies

```
npm install
```

### 3. Start the development server

```
npm run dev
```

The application should now be running at:

```
http://localhost:3000
```

---

## Environment Variables

Create a `.env` file in the root directory.

Example:

```
NEXT_PUBLIC_API_URL=http://localhost:8000
NEXT_PUBLIC_STELLAR_NETWORK=testnet
```

---

## Contributing

We welcome contributions from the open-source community.

Ways you can contribute:

* Improve UI/UX
* Add wallet integrations
* Implement new features
* Fix bugs
* Improve documentation

### Contribution Steps

1. Fork the repository
2. Create a new branch

```
git checkout -b feature/your-feature-name
```

3. Commit your changes
4. Push your branch
5. Open a Pull Request

---

## Roadmap

* Wallet connection (Freighter)
* Tip history dashboard
* Creator discovery page
* QR code tip links
* Dark mode support
* Mobile optimization

---

## Related Repositories

* stellar-tipjar-backend
* stellar-tipjar-contracts

---

## License

This project is licensed under the MIT License.

---

## Acknowledgements

Built using the Stellar ecosystem and Soroban smart contracts.
