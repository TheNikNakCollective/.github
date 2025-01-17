# The NikNak Collective

Welcome to **The NikNak Collective**, an open-source social media platform dedicated to fostering community, creativity, and collaboration. This project thrives on the contributions and engagement of users like you. Together, we can build a better digital space for everyone.

---

## 🌟 Vision
The NikNak Collective aims to create an inclusive, user-driven platform where individuals can share their stories, connect with like-minded people, and collaborate on meaningful projects. Unlike traditional social media, The NikNak Collective prioritizes transparency, user empowerment, and open innovation.

---

## 🛠 Features

- **Open Source:** Fully transparent codebase, allowing anyone to contribute, audit, or adapt the platform.
- **Decentralized Structure:** Users maintain control over their data and content.
- **Customizable Feeds:** Tailor your experience with personalized algorithms.
- **Creative Collaboration:** Tools for co-authoring posts, sharing ideas, and organizing events.
- **Moderation by Community:** A fair and democratic approach to managing content and user behavior.

---

## Getting Started

### Prerequisites

Ensure the following tools are installed on your system:

- **Docker**: [Install Docker](https://docs.docker.com/get-docker/)
- **Docker Compose**: [Install Docker Compose](https://docs.docker.com/compose/install/)
- 
### Clone Repos

```bash
mkdir theniknakcollective
cd theniknakcollective
git clone https://github.com/TheNikNakCollective/NikNakLocalStack.git
git clone https://github.com/TheNikNakCollective/NikNakAirflow.git
git clone https://github.com/TheNikNakCollective/NikNakPackages.git
git clone https://github.com/TheNikNakCollective/NikNakApp.git
```
### Setup Airflow

```bash
cd NikNakAirflow
make setup
```

### Setup LocalStack

```bash
cd NikNakLocalStack
make setup
make niknak
```

### Setup Packages

```bash
cd NikNakPackages
yarn install
```

## 🛡 License

The NikNak Collective is licensed under the [GPL-3.0 License](LICENSE), ensuring that the platform remains free and open for all users, with contributions shared under the same terms.
