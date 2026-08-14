<div align="center">

# Pazent

### Every security bug deserves a regression test.

Open-source tools that turn offensive security evidence into defensive controls.

[![ExploitSpec](https://img.shields.io/badge/ExploitSpec-RED%20%E2%86%92%20GREEN%20%E2%86%92%20STABLE-3fd0d4?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/pazent/exploitspec)
[![GitHub Marketplace](https://img.shields.io/badge/GitHub%20Marketplace-Install-2ea44f?style=for-the-badge&logo=githubactions&logoColor=white)](https://github.com/marketplace/actions/exploitspec-security-regression-tests)
[![Apache-2.0](https://img.shields.io/badge/license-Apache--2.0-c8a96b?style=for-the-badge)](https://github.com/pazent/exploitspec/blob/main/LICENSE)

</div>

## ExploitSpec

[ExploitSpec](https://github.com/pazent/exploitspec) turns a confirmed HTTP
exploit into a deterministic, reviewable regression test. It keeps pentest
evidence alive after remediation by proving three things:

- **RED** — the invariant fails on the known-vulnerable baseline;
- **GREEN** — it passes after the fix;
- **STABLE** — the fix keeps passing across repeated runs.

![ExploitSpec RED, GREEN, STABLE demo](https://raw.githubusercontent.com/pazent/exploitspec/v0.1.0/docs/demo.svg)

Try the complete synthetic demo locally:

```bash
git clone https://github.com/pazent/exploitspec.git
cd exploitspec
make demo
```

No account. No telemetry. No paid tier. Apache-2.0.

## Build with us

We care about narrow security promises, reproducible evidence, deterministic
tests, conservative handling of secrets, and honest documentation of limits.

- [Read the specification](https://github.com/pazent/exploitspec/blob/main/docs/specification.md)
- [Install the GitHub Action](https://github.com/marketplace/actions/exploitspec-security-regression-tests)
- [Fork the passing consumer template](https://github.com/pazent/exploitspec-demo)
- [Read the BOLA/IDOR case study](https://github.com/pazent/exploitspec/discussions/8)
- [See the roadmap](https://github.com/pazent/exploitspec/blob/main/ROADMAP.md)
- [Propose an idea](https://github.com/pazent/exploitspec/discussions/categories/ideas)
- [Contribute](https://github.com/pazent/exploitspec/blob/main/CONTRIBUTING.md)

Maintained by [Pazent](https://github.com/Pazificateur69).
