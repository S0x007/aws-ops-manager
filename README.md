<p align="center">
  <img src="image/home.png" width="600" alt="AWS Ops Manager" />
</p>

# AWS Ops Manager

A cross-platform desktop client for AWS operations management. Use your **AWS Access Key / Secret Key** to manage EC2, S3, EBS, Security Groups, Elastic IPs, Key Pairs, AMI, and network resources — all from one app.

> **How it works:** The tool connects to AWS via your Access Key / Secret Key. No cloud account provided — you bring your own credentials. Supports `~/.aws/config` profiles and built-in AES-256-GCM encrypted credential storage.

**English** | [简体中文](README.zh-CN.md)

<p align="center">
  <img src="image/img_en.png" width="600" alt="English UI" />
</p>

## Features

- **EC2** — instance list, start/stop/reboot, 8-tab detail, CloudWatch charts, SSM terminal & Run Command
- **S3** — bucket browser, upload/download with progress, inline file editor, bucket detail (policy, encryption, lifecycle, etc.)
- **EBS & Snapshots** — volume create/attach/detach, snapshot management
- **Security Groups** — inbound/outbound rules with 8 presets (SSH/HTTP/HTTPS/MySQL/...)
- **Network** — VPC, subnets, route tables, IGW, NAT gateways
- **Elastic IPs & Key Pairs** — allocate/associate/release, create/import (.pem download)
- **AMI** — list owned images, cross-region copy, deregister
- **Credentials** — `~/.aws/config` profiles + AES-256-GCM encrypted custom keys
- **Bilingual UI** — English / 简体中文
- **Cmd+K** global search, dark/light theme, API cache

## Download

[Latest Release](https://github.com/S0x007/aws-ops-manager/releases)

| Platform | Format |
|----------|--------|
| macOS (Apple Silicon) | `.dmg` |
| macOS (Intel) | `.dmg` |
| Windows | `.exe` installer |
| Linux | `.AppImage` |

## License

[MIT](LICENSE)
