# Eza CLI (`eza`)

The official command-line interface for [Eza Cloud](https://eza.co.ke), the developer platform for Kenya and East Africa.

Deploy applications, manage PostgreSQL / Redis databases, configure secrets and custom domains, tail live application logs, and open secure database tunnels directly from your terminal.

---

## Installation

### Method 1: npm (Cross-Platform)

```bash
npm install -g @ezacloud/cli
```

### Method 2: Shell Script (Linux / macOS)

```bash
curl -fsSL https://eza.co.ke/install.sh | sh
```

### Method 3: Standalone Binaries

Download pre-compiled native binaries for Linux (x64, arm64), macOS (Apple Silicon, Intel), and Windows from the [Releases](https://github.com/ezacloud/eza-cli/releases) page.

---

## Quick Start

```bash
# Authenticate your terminal with Eza Cloud
eza login

# Link your current directory to an existing application
eza link

# Deploy from local source or git branch
eza deploy

# Tail live application logs
eza logs -f

# Set environment variables
eza env set DATABASE_URL=...

# Open a secure proxy tunnel to your managed PostgreSQL database
eza db tunnel
```

---

## Documentation

Full command documentation, deployment workflows, and guides: [eza.co.ke/docs/cli](https://eza.co.ke/docs/cli).
