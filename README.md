# Development Documentation

## Template Source 

* Theme Research Group: https://github.com/HugoBlox/theme-research-group
* Theme Customization: https://bootstrap.hugoblox.com/getting-started
* Markdown Formatting: https://docs.hugoblox.com/reference/markdown/
* HugoBlox Builder: https://github.com/HugoBlox/hugo-blox-builder
* Free images: https://unsplash.com/

## Local Development Guide

### Prerequisites

1. Install [Go](https://go.dev/doc/install) (version 1.20 or later).
2. Install [Hugo-Extended](https://gohugo.io/installation/) (version 0.120.0 or later).
> [!NOTE]
> Please use the **Extended** version of Hugo.
> 
   - For example, on macOS, you can use [Homebrew](https://brew.sh/) to install Hugo Extended:
     ```bash
     brew install hugo
     ```
   - On Windows, you can install Hugo Extended using [Chocolatey](https://chocolatey.org/), [Scoop](https://scoop.sh/), or Winget:
     ```bash
     choco install hugo-extended
     ```
     refer to https://gohugo.io/installation/windows/ for more details.

### Local Development and Preview

1. Edit the files according to the [Adding a New Talk](#adding-a-new-talk) section.
2. Run the following command to start the local development server:
   ```bash
   hugo server
   ```
   refer to [Hugo Server Documentation](https://gohugo.io/commands/hugo_server/) for more details.
   

## Adding a New Talk

### Step 1: Add a New Talk

1. Copy the folder [content/talk/11-Apr-2025/](content/talk/11-Apr-2025) and rename it with **the new talk date**.
2. Update the `index.md` file with the new talk details.
   * Please refer to [Markdown Formatting](https://docs.hugoblox.com/reference/markdown/) for Hugo Markdown syntax.
3. Change the `featured.jpg` image to the new talk image.
   * Please put all images in the [assets/media/](assets/media/) folder.

> [!NOTE]
> It is not suggested to use `hugo new  --kind event event/my-talk-name` command to create a new talk. 
> We have a custom layout for the talk page, which is not supported by the default Hugo event layout.
> 

### Step 2: Add the Talk to the Homepage

1. Edit the [content/_index.md](content/_index.md) file.
2. Update the `id: section-upcoming-talks` section with the new talk details.

Key Checklist:

- [ ] `subtitle` - Update the talk title.
- [ ] `text` - Update the talk details.
- [ ] `chenglongma_countdown` - Update the talk `date`.
  - The date format is `YYYY-MM-DD HH:MM`, which is **Australian Eastern Standard Time (AEST)**.
- [ ] `cta_link` - Update the link to the **Registration** page.

## Update a Past Talk

1. Update the `index.md` file in the respective talk folder.
2. Update the `featured.jpg` image if required.
3. Update the talk resources, such as `url_pdf`, `url_video`, `url_slides`, etc.

## Advanced Customization

Please refer to [Hugo Blox Docs](https://docs.hugoblox.com/reference/extend/) for advanced customization.

> [!WARNING]
> Please deliberately change the files in [layouts/](./layouts) folder.
> 
