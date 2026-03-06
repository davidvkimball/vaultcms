# Vault CMS

The open-source headless content management system that turns [Obsidian](https://obsidian.md) into a publishing platform for your [Astro](https://astro.build) website.

![Vault CMS cover with Obsidian and Astro logos at the bottom.](https://github.com/user-attachments/assets/fb5d8368-71dd-4bf8-8851-36ada6d4f530)

## Features 

- **Auto-detection and automation**: Detects your Astro routes and content structure automatically.
- **CMS-like homepage**: See your content in a visual grid and perform bulk actions.
- **Preconfigured**: Optimized settings, hotkeys, and plugins for the Astro workflow.
- **Headless and flexible**: Just Markdown files and a workspace ready to be customized by you.
- **Compatability**: Works with almost any Astro theme.

## Quick Start

The fastest way to install Vault CMS into your Astro project is via the CLI at your project root:

```bash
pnpm create vaultcms
```

*The installer will detect your Astro project, scan your routes, and install at the project root by default for full asset compatibility.*

### Manual Installation

If you prefer to install manually, you can download the latest version of Vault CMS and place it directly into your Astro project.

1. **Download the source**: [Clone this repository](https://github.com/davidvkimball/vaultcms) or [download the ZIP archive](https://github.com/davidvkimball/vaultcms/archive/refs/heads/master.zip).
2. **Locate your project root**: This is typically the directory containing `astro.config.mjs` and `package.json`.
3. **Move the files**: Copy the `.obsidian` and `_bases` folders (and `_GUIDE.md`) from the Vault CMS source into your project root.
4. **Open in Obsidian**: Open the project root as a new vault in Obsidian.

### Presets

For themes like **Starlight**, **Slate**, or **Chiri**, run the CLI and choose a preset when prompted:

```bash
pnpm create vaultcms
```

To skip the prompt and set the template in one go (e.g. for scripts), add `-- --template <name>` after the command. See all presets at the [Presets Repo](https://github.com/davidvkimball/vaultcms-presets).

## Deep Dive

- **Documentation**: [docs.vaultcms.org](https://docs.vaultcms.org)
- **Video Guide**: [Set Up Guide on YouTube](https://www.youtube.com/watch?v=3zeqJ5tqmaQ)
- **Community**: [Join the Discord](https://discord.gg/gyrNHAwHK8)

> [!NOTE]
> To see Vault CMS combined with an Astro site specifically designed with it in mind, check out the [Astro Modular](https://github.com/davidvkimball/astro-modular) theme.

![Vault CMS Showcase.](https://github.com/user-attachments/assets/0d1ea89e-9d6b-40b1-944d-cfe6143e222e)
