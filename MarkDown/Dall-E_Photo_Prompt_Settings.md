---
title: Dall-E Photo prompt settings
creation date: 2023-10-22 11:02
modification date: Sunday 22nd October 2023 11:02:45
author: Christer Johansson
tags:
  - AI/Dall-e
  - AI
---
# Dall-E Photo prompt settings

Here are the available settings and commands that can be used with DALL·E for camera photos:

1. **Size** (`size`): Specifies the resolution of the requested image.
   - Options: `1792x1024` (wide), `1024x1024` (square), `1024x1792` (tall).
2. **Prompts** (`prompts`): A list of textual descriptions for the images you want to generate. Each description should be detailed and intricate to provide DALL·E with clear instructions on what to create.
3. **Seeds** (`seeds`): A list of seeds to use for each prompt. If you want to modify a previous image, you can populate this field with the seed used to generate that image from the image metadata.
4. **Quality** (`q`): Adjusts the quality level of the image.
   - For example: `--q 1.5`.
5. **Version** (`v`): Adjusts the version level.
   - For example: `--v 5`.
6. **Aperture** (`f`): Specifies the aperture setting.
   - For example: `f/2.8`.
7. **ISO** (`ISO`): Specifies the ISO setting.
   - For example: `ISO 400`.
8. **Shutter Speed**: Specifies the shutter speed.
   - For example: `1/200 sec`.
9. **Camera Brand/Model**: You can specify a camera brand and model.
   - For example: `Nikon D850`.
10. **Lens Brand/Model**: You can specify a lens brand and model.
   - For example: `Canon EF 600mm f/4L`.
11. **Aspect Ratio** (`ar`): Specifies the aspect ratio of the image.
   - For example: `--ar 16:9`.
12. **Specific Keywords**: You can use specific keywords like "HDR", "macro", "wide-angle", "telephoto", etc., to define the type or style of the photo.

Keep in mind that while DALL·E can take these settings into account, it's primarily guided by the textual description in the `prompts` field. The more detailed and intricate the description, the better the result is likely to be. Additionally, not all of the mentioned commands may directly impact the output, as DALL·E's primary guidance comes from the prompt description.