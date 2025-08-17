# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a growing, work-in-progress FPV (First Person View) drone knowledge base repository containing technical documentation and guides for FPV drone enthusiasts. The repository is primarily documentation-focused using Markdown files, not a software project with code that needs to be built or tested.

## Repository Structure

```
fpv-drones-kb/
├── README.md                        # Main repository overview and index
├── happymodel-tinywhoop-setup/     # Tinywhoop setup guides
│   └── setup.md                    # Mobula6 HD Race configuration guide
└── hdzero/                         # HDZero-specific documentation
    └── streaming.md                # RTSP streaming setup guide
```

**Note**: Asset folders (`_assets/`) contain images and media files. There's no need to explore or list individual asset files.

## Content Management

### Documentation Standards

- All documentation is written in Markdown format
- Guides should include comprehensive table of contents
- Technical guides should include:
  - Clear requirements section
  - Step-by-step instructions
  - Command examples with explanations
  - Visual aids where appropriate (stored in `_assets/` directory)

### Adding New Content

When adding new FPV-related documentation:
1. Create appropriate topic directories if they don't exist (e.g., `betaflight/`, `elrs/`, `analog-vtx/`)
2. Place topic-specific images in `[topic]/_assets/` within each topic folder
3. Place shared/global assets in the root `_assets/` directory
4. Update the main README.md to include links to new guides
5. Use relative links for internal documentation references
6. Reference images from markdown files using `./_assets/image.png` for local assets

### Current Content

The knowledge base currently includes:
- **HDZero**: Video transmission and streaming guides
- **Tinywhoop Setup**: Configuration guides for HappyModel drones (Mobula6 HD Race)

### Planned Topics

As a work-in-progress knowledge base, future content may cover:
- Radio control systems (ELRS, Crossfire, FrSky)
- Video transmission systems (analog, DJI, Walksnail)
- Flight controllers and firmware (Betaflight, INAV, Ardupilot)
- FPV hardware guides and build logs
- Racing and freestyle techniques
- Safety and regulations

## Important Notes

- This is a documentation repository - there are no build commands, tests, or linting required
- Focus on creating clear, technically accurate FPV drone documentation
- Ensure all network configuration examples prioritize security best practices
- When documenting streaming or network setups, always include firewall and security considerations