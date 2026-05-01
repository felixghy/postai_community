# PostAI Community — Prompt Image Mirror

A self-hosted mirror of the 291 prompt images used by the [PostAI Realtor AI Prompts library](https://postai.sg/realtor-ai-community/), plus original PostAI sample outputs.

The original sources are reliable but third-party. This repo exists as a **fallback host** in case any upstream becomes unavailable, rate-limited, or moves.

## Folder structure

| Folder | Files | Origin | License |
|---|---|---|---|
| `jacwu/` | 65 | [github.com/jacwu/demo-gpt-image-2](https://github.com/jacwu/demo-gpt-image-2) | Per upstream repo |
| `jamez/cases/<N>/` | 100 | [github.com/jamez-bondos/awesome-gpt4o-images](https://github.com/jamez-bondos/awesome-gpt4o-images) | Per upstream repo |
| `youmind/` | 126 | [github.com/youmindlab/awesome-gpt-image-2](https://github.com/youmindlab/awesome-gpt-image-2) (originally hosted on `cms-assets.youmind.com`) | CC BY 4.0 |
| `postai-samples/` | 2+ | Original PostAI outputs | © PostAI — free commercial use for property agents |

## How files are referenced

The PostAI website references images via the GitHub raw CDN, e.g.:

```
https://raw.githubusercontent.com/felixghy/postai_community/main/jacwu/047_32_wechat_cat_stickers.png
https://raw.githubusercontent.com/felixghy/postai_community/main/youmind/1777106848083_vbv8om_HGpge6qWIAAT0CT.jpg
https://raw.githubusercontent.com/felixghy/postai_community/main/jamez/cases/81/example.png
https://raw.githubusercontent.com/felixghy/postai_community/main/postai-samples/luxury-real-estate-brochure-sample.png
```

## Attribution

Original prompts curated by:
- **YouMind OpenLab** — [awesome-gpt-image-2](https://github.com/youmindlab/awesome-gpt-image-2) (CC BY 4.0)
- **Jacky Wu** — [demo-gpt-image-2](https://github.com/jacwu/demo-gpt-image-2)
- **James Bond / jamez-bondos** — [awesome-gpt4o-images](https://github.com/jamez-bondos/awesome-gpt4o-images)

Realtor adaptations and `postai-samples/` outputs by the **PostAI Editorial Team**.
