# Reverse Engineer Anything

This repository collects work around AI-assisted reverse engineering.

## Included project

- **[REA — Reverse Engineer Anything](https://github.com/morluto/rea)**, by [morluto](https://github.com/morluto). REA provides tools and an MCP integration for analyzing application behavior, JavaScript/Electron apps, binaries, and other software artifacts.
- The upstream repository is included in the [`rea/`](rea) folder as a **Git submodule**, preserving the original project, license, and Git history instead of copying or misattributing its source.

### Clone with the REA submodule

```bash
git clone --recurse-submodules https://github.com/dmcchesney96/Reverse-engineer-anything.git
```

If you already cloned the repository:

```bash
git submodule update --init --recursive
```

To move the REA submodule to a newer upstream revision:

```bash
git submodule update --remote --merge rea
git add rea
git commit -m "Update REA submodule"
```

## Using REA

REA's own documentation, prerequisites, and setup instructions are in [`rea/README.md`](rea/README.md).

From its published installation instructions, after installing Node.js and npm:

```bash
npx rea-agents setup
```

Review any configuration changes proposed by setup before approving. Including the submodule here does not automatically install or run REA.

## Credit and license

REA is maintained at [morluto/rea](https://github.com/morluto/rea) and distributed under the [MIT License](https://github.com/morluto/rea/blob/main/LICENSE). Its original code and license remain within the submodule.
