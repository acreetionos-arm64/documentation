# AcreetionOS ARM64 Documentation

**Repository**: [`acreetionos-arm64/documentation`](https://github.com/acreetionos-arm64/documentation)
**Purpose**: Technical architecture, development guides, and project documentation

## Documentation Index

### Core Architecture
- **[AcreetionOS-ARM64-Architecture.md](./AcreetionOS-ARM64-Architecture.md)** - Complete technical architecture (16,000+ words)
- **[AcreetionOS-ARM64-Proposal.md](./AcreetionOS-ARM64-Proposal.md)** - Upstream team communication proposal
- **[PROJECT-OVERVIEW.md](./PROJECT-OVERVIEW.md)** - Comprehensive project overview and goals

### Development Planning
- **[MILESTONE-0-PLAN.md](./MILESTONE-0-PLAN.md)** - Repository infrastructure setup plan
- **[ROADMAP.md](./ROADMAP.md)** - Development roadmap with effort estimates

## Project Context

This documentation supports the AcreetionOS ARM64 port project - a community-driven effort to create an ARM64 version of AcreetionOS Linux distribution.

**Key Information**:
- **Timeline**: 18-36 months, sustainable side project approach
- **Architecture Target**: ARM64/aarch64 with Raspberry Pi 5 primary target
- **Technical Strategy**: 90% upstream ARM packages + 10% AcreetionOS customizations
- **Organization**: [`acreetionos-arm64`](https://github.com/acreetionos-arm64) on GitHub

## Documentation Philosophy

- **Comprehensive**: Complete technical analysis and planning
- **Practical**: Developer-focused with actionable guidance
- **Educational**: Learning Linux distribution development
- **Respectful**: Proper attribution to upstream AcreetionOS team

## Multi-Repository Structure

This documentation repository is part of a larger multi-repository architecture:

```
acreetionos-arm64/workspace              # Main coordination
├── documentation/                       # ← This repository
├── iso-builder/                         # Main build system
├── custom-packages/                     # AcreetionOS components
├── arm64-toolchain/                     # Cross-compilation tools
└── [7 additional specialized repos]
```

## Contributing

Documentation contributions welcome in areas:
- Technical guides and tutorials
- Hardware-specific setup instructions
- Development workflow improvements
- User experience documentation

## Links

- **Main Workspace**: [`acreetionos-arm64/workspace`](https://github.com/acreetionos-arm64/workspace)
- **Organization**: [`acreetionos-arm64`](https://github.com/acreetionos-arm64)
- **AcreetionOS Upstream**: [gitlab.acreetionos.org](https://gitlab.acreetionos.org)