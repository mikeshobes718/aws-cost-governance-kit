# AWS Cost Governance Kit

[![CI](https://github.com/mikeshobes718/aws-cost-governance-kit/actions/workflows/ci.yml/badge.svg)](https://github.com/mikeshobes718/aws-cost-governance-kit/actions/workflows/ci.yml) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

FinOps automation for AWS: inventory + tag policy checks, unused AMI/EBS cleanup, stranded resource reports; report/dry-run/execute modes.

## Features
- Inventory with tagging policy validation
- Unused AMI/EBS snapshot/volume discovery and cleanup
- Stranded resource detection (ENI, EIP, EBS, snapshots)
- Report, dry-run, and execute modes with summary output

## Quickstart
```bash
# Coming soon: CLI entrypoint
python -m cost_governance --help
```

## Architecture
- Python + boto3 with paginated, regional scans
- Policy as code for tag and lifecycle rules

## Roadmap
- Savings Plan/RI coverage heuristics
- Orphaned RDS/S3/GW scans
- Slack/Email digest reports

## License
MIT
