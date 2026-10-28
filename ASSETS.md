# Assets and licences

The MIT licence in [LICENSE](./LICENSE) covers the **code only**. Everything under `public/` is
listed here with where it came from.

This is the open edition. The original project also used district houses built from a purchased
asset pack and some street props; those are **not** included and not redistributable. Districts
are drawn from primitive shapes instead.

## 3D models (`public/models/`)

| File                                  | Origin                                                                                                                                                                               | Status                                                                                                        |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------- |
| `quaternius-tree-v1.glb`              | The lightest tree from Quaternius's [Textured LowPoly Trees](https://quaternius.itch.io/textured-lowpoly-trees), converted from FBX by `scripts/convert-quaternius-tree.mjs`.        | CC0 1.0                                                                                                       |
| `fpt-walk-v2.glb`, `grab-walk-v2.glb` | Walking characters. Text-to-image model → image-to-3D with Hunyuan3D-2.1 → body cut into parts and walk cycle authored in Blender → `scripts/optimize-glb.mjs` (`character` preset). | **To confirm**: Tencent Hunyuan3D licence terms (territory and usage limits) and the text-to-image model used |
| `ho-guom-v1.glb`                      | Hồ Gươm landmark, optimised from an authoring export. Origin not recorded.                                                                                                           | **To confirm**                                                                                                |
| `pin-tree-v1.glb`, `tree-v1.glb`      | Trees. Origin not recorded.                                                                                                                                                          | **To confirm**                                                                                                |

"To confirm" files were made by the author with generative tools. Their licence has not been
checked yet, so do not rely on them for anything beyond running this demo.

## Logos (`public/logos/`)

See [public/logos/NOTICE.md](./public/logos/NOTICE.md).

| File                                                              | Origin                                                                                                              | Status                                                                                     |
| ----------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ |
| `deepseek`, `zhipu`, `gemma`, `qwen`, `meta` (colour and `-mono`) | [lobe-icons](https://github.com/lobehub/lobe-icons) (`@lobehub/icons-static-svg`)                                   | Icon files MIT. The marks are trademarks of DeepSeek, Z.ai, Google, Alibaba Qwen and Meta. |
| `fpt.svg`, `fpt-mono.svg`                                         | FPT Smart Cloud logo from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Fpt_smart_cloud.png), cropped | Trademark of FPT. Used only to identify the platform.                                      |

Logos appear only to say which model each district serves. They do not imply endorsement.

## Fonts (`public/fonts/`)

| File                  | Licence                         |
| --------------------- | ------------------------------- |
| `dm-sans-latin.woff2` | SIL OFL 1.1 (`dm-sans-OFL.txt`) |
| `manrope-latin.woff2` | SIL OFL 1.1 (`manrope-OFL.txt`) |

## Data

Token usage, queue sizes, traffic and the people-in-town figure are simulated. Prices and context
lengths were taken from the FPT serverless catalog at the time of writing and may be out of date.
