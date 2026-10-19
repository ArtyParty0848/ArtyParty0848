# Hey, I'm James 👋

Marine Veteran | Cybersecurity Student | Homelab Tinkerer

I build and maintain a home infrastructure lab focused on virtualization,
networking, storage, automation, and practical infrastructure testing.

## Featured Work

### [HybridOps / Proxmox Infrastructure Evaluation](https://github.com/ArtyParty0848/hybridops-proxmox-evaluation)

Independent practitioner evaluation of HybridOps.Core against a dedicated
Dell PowerEdge R740xd Proxmox staging environment.

The evaluation covers:

- Proxmox image and template lifecycle
- networking and IPAM authority
- PostgreSQL HA
- RKE2
- infrastructure automation validation
- failure analysis and recovery testing

Stage 1 included a full Ubuntu image lifecycle:

`build → template → full clone → boot → guest-agent readiness → cleanup → destroy`

The initial run exposed several real-world integration issues involving
Proxmox permissions, SDN access, storage selection, ISO handling, and
WSL/Packer networking. A clean procedural replay then completed successfully
end-to-end.

**Current status**

- Stage 1: ✅ Image & Template Lifecycle — Passed
- Stage 2: ⏳ Network & IPAM Authority
- Stage 3: ⏳ PostgreSQL HA
- Stage 4: ⏳ RKE2

## Homelab

Current areas of focus:

- Proxmox VE
- Dell PowerEdge servers
- TrueNAS
- 10Gb networking
- virtualization and storage
- Linux and Windows administration
- infrastructure automation
- disaster recovery and validation

## Projects

- [HybridOps Proxmox Evaluation](https://github.com/ArtyParty0848/hybridops-proxmox-evaluation) — staged evaluation of HybridOps.Core on Proxmox VE
- R740xd server build and migration
