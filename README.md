# EWB-VPC-Peering
AWS VPC Peering project - Ananya R Shetty

**Name:** Ananya R Shetty
**Batch:** 1
**Region:** Asia Pacific (Sydney) ap-southeast-2

Two VPCs (10.10.0.0/16 and 10.20.0.0/16) connected with VPC peering,
with a public bastion in VPC A and private EC2 hosts in each VPC.

## Contents
- `Ananya_R_Shetty_EWB_VPC_Peering.pdf` - full project report
- `screenshots/` - evidence (routes, security groups, ping tests, cleanup)

## What was tested
- Baseline ping failure before peering
- Forward and reverse ping after peering and routes
- SSH to App-B through the bastion using ProxyJump
- Controlled failure by removing and restoring an ICMP rule
- Full cleanup of all resources
