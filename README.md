<p align="center">
  <img src="profile/banner.svg" alt="ProxBeam: codegen toolchain for the Proxmox VE API" width="100%"/>
</p>

<h3 align="center">One source spec, many faithful bindings.</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Proxmox_VE-9.2.20-E57000?style=flat-square&logo=proxmox&logoColor=white" alt="Proxmox VE 9.2.20">
  <img src="https://img.shields.io/badge/endpoints-680-2EA043?style=flat-square" alt="680 endpoints">
  <img src="https://img.shields.io/badge/targets-7-8250DF?style=flat-square" alt="7 generated targets">
</p>

<p align="center">Built with ❤️ for the Proxmox community.</p>

<p align="center">
  <a href="https://github.com/sponsors/proxbeam"><img src="https://img.shields.io/badge/Sponsor_on_GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" height="36" alt="Sponsor on GitHub"></a>&nbsp;&nbsp;<a href="https://buymeacoffee.com/muhmdraouf"><img src="https://img.shields.io/badge/Buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" height="36" alt="Buy me a coffee"></a>
</p>

> [!NOTE]
> The repositories are being prepared for their public release.

## About

[Proxmox VE](https://www.proxmox.com/en/proxmox-ve) does not publish a
machine-readable OpenAPI specification for its REST API. ProxBeam
extracts the schema from the signed, versioned PVE packages, validates it into
a stable JSON specification, and generates client libraries and infrastructure
tooling from it. All targets are regenerated together, with one release per
pinned PVE schema version.

## Projects

| Category | Project | Description | Maintenance |
|---|---|---|---|
| Toolchain | `proxbeam` | Schema extraction and code generators | Hand-maintained |
| SDKs | `golang-sdk` | Go client | Generated |
| | `python-sdk` | Python client with type hints | Generated |
| | `typescript-sdk` | TypeScript client | Generated |
| | `rust-sdk` | Rust client | Generated |
| | `ruby-sdk` | Ruby client with RBS types | Generated |
| Infrastructure | `terraform-provider-proxmox` | Terraform provider | Generated |
| | `ansible-collection` | Ansible collection | Generated |
| CI | `fleeting-plugin-proxmox` | [GitLab Runner fleeting](https://docs.gitlab.com/runner/fleet_scaling/fleeting/) plugin for autoscaling CI job VMs | Hand-maintained |

Generated projects are produced by `proxbeam` from the PVE schema; each SDK
covers all 680 endpoints. Hand-maintained projects are developed and released
independently.

## Support

<p align="center">
  Built with ❤️ for the Proxmox community.<br>
  If these tools make your day a little easier, you can say thanks here:
</p>

<p align="center">
  <a href="https://github.com/sponsors/proxbeam"><img src="https://img.shields.io/badge/Sponsor_on_GitHub-EA4AAA?style=for-the-badge&logo=githubsponsors&logoColor=white" height="36" alt="Sponsor on GitHub"></a>&nbsp;&nbsp;<a href="https://buymeacoffee.com/muhmdraouf"><img src="https://img.shields.io/badge/Buy_me_a_coffee-FFDD00?style=for-the-badge&logo=buymeacoffee&logoColor=black" height="36" alt="Buy me a coffee"></a>
</p>
