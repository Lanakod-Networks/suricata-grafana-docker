<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" align="center" width="30%">
</p>
<p align="center"><h1 align="center"><code>❯ Suricata Grafana Docker</code></h1></p>
<p align="center">
	<em><code>❯ lanakod-networking</code></em>
</p>
<p align="center">
	<!-- local repository, no metadata badges. --></p>
<p align="center">Built with the tools and technologies:</p>
<p align="center">
	<img src="https://img.shields.io/badge/Grafana-F46800.svg?style=default&logo=Grafana&logoColor=white" alt="Grafana">
	<img src="https://img.shields.io/badge/Docker-2496ED.svg?style=default&logo=Docker&logoColor=white" alt="Docker">
</p>
<br>

##  Table of Contents

- [ Overview](#-overview)
- [ Features](#-features)
- [ Project Structure](#-project-structure)
  - [ Project Index](#-project-index)
- [ Getting Started](#-getting-started)
  - [ Prerequisites](#-prerequisites)
  - [ Installation](#-installation)
  - [ Usage](#-usage)
  - [ Testing](#-testing)
- [ Project Roadmap](#-project-roadmap)
- [ Contributing](#-contributing)
- [ License](#-license)
- [ Acknowledgments](#-acknowledgments)

---

##  Overview

<code>❯ TODO</code>

---

##  Features

<code>❯ TODO</code>

---

##  Project Structure

```sh
└── /
    ├── docker-compose.yml
    ├── eve.json
    ├── loki-local-config.yaml
    ├── promtail-config.yml
    ├── readme-ai.md
    ├── README.md
    ├── suricata
    │   ├── classification.config
    │   ├── reference.config
    │   ├── suricata.yaml
    │   ├── threshold.config
    │   └── update.yaml
    └── suricata-rules
        └── .gitkeep
```


###  Project Index
<details open>
	<summary><b><code>/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='/docker-compose.yml'>docker-compose.yml</a></b></td>
				<td><code>❯ Docker compose config file</code></td>
			</tr>
			<tr>
				<td><b><a href='/eve.json'>eve.json</a></b></td>
				<td><code>❯ Suricata logs</code></td>
			</tr>
			<tr>
				<td><b><a href='/loki-local-config.yaml'>loki-local-config.yaml</a></b></td>
				<td><code>❯ Loki configuration file</code></td>
			</tr>
			<tr>
				<td><b><a href='/promtail-config.yml'>promtail-config.yml</a></b></td>
				<td><code>❯ Promtail configuration file</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- suricata Submodule -->
		<summary><b>suricata</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='/suricata/classification.config'>classification.config</a></b></td>
				<td><code>❯ Suricata config</code></td>
			</tr>
			<tr>
				<td><b><a href='/suricata/reference.config'>reference.config</a></b></td>
				<td><code>❯ Suricata config</code></td>
			</tr>
			<tr>
				<td><b><a href='/suricata/suricata.yaml'>suricata.yaml</a></b></td>
				<td><code>❯ Suricata config</code></td>
			</tr>
			<tr>
				<td><b><a href='/suricata/threshold.config'>threshold.config</a></b></td>
				<td><code>❯ Suricata config</code></td>
			</tr>
			<tr>
				<td><b><a href='/suricata/update.yaml'>update.yaml</a></b></td>
				<td><code>❯ Suricata config</code></td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---
##  Getting Started

###  Prerequisites

Before getting started with , ensure your runtime environment meets the following requirements:

- **Programming Language:** Error detecting primary_language: {'yml': 2, 'json': 1, 'yaml': 3, 'config': 3}
- **Container Runtime:** Docker


###  Installation

Install  using one of the following methods:

**Build from source:**

1. Clone the  repository:
```sh
❯ git clone https://github.com/Lanakod-Networks/suricata-grafana-docker.git
```

2. Navigate to the project directory:
```sh
❯ cd suricata-grafana-docker
```

3. Run docker compose:


**Using `docker`** &nbsp; [<img align="center" src="https://img.shields.io/badge/Docker-2CA5E0.svg?style={badge_style}&logo=docker&logoColor=white" />](https://www.docker.com/)

```sh
❯ docker compose up -d
```

4. Inside suricata docker container exec command:
```sh
suricata-update -f
```

5. After signing in into Grafana don't forget to add dashboard with id `22247`
---
##  Project Roadmap

- [X] **`Task 1`**: <strike>Implement feature one.</strike>
- [ ] **`Task 2`**: Implement feature two.
- [ ] **`Task 3`**: Implement feature three.

---

##  License

This project is protected under the [MIT LICENSE](./LICENSE) License. For more details, refer to the [LICENSE](./LICENSE) file.

---