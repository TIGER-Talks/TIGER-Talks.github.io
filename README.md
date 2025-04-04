# Development Documentation

## Template Source 

* Theme Research Group: https://github.com/HugoBlox/theme-research-group
* Theme Customization: https://bootstrap.hugoblox.com/getting-started
* Markdown Formatting: https://docs.hugoblox.com/reference/markdown/
* HugoBlox Builder: https://github.com/HugoBlox/hugo-blox-builder
* Free images: https://unsplash.com/

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
