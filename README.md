# AZIRAL skills for HyperFrames

Independent agent workflows by **Olzhas Azirali / AZIRAL**. This project is not affiliated with, endorsed by, or maintained by HeyGen.

![AZIRAL PRODUCT VIDEO](assets/cover.svg)

Plan product demonstrations that show one clear action, use evidence for product claims, and stay readable across language and aspect-ratio variants. These are original instructions for working with [HyperFrames by HeyGen](https://github.com/heygen-com/hyperframes).

[Русский](README.ru.md)

## Install

```sh
npx skills add azirali/hyperframes --skill aziral-product-video
```

The installer adds the skill to your selected coding agent. Rendering also needs a HyperFrames environment; use the [official quickstart](https://hyperframes.heygen.com/quickstart) for current setup and commands.

## Included

| File | Use |
| --- | --- |
| [`SKILL.md`](skills/aziral-product-video/SKILL.md) | Product evidence, story planning, multilingual variants, framing and delivery checks |
| [`brief-template.md`](skills/aziral-product-video/references/brief-template.md) | Reusable brief and shot-planning template |
| [`brief.json`](examples/product-demo/brief.json) | Fictional 12-second concept brief with English, Russian and Kazakh copy |
| [`openai.yaml`](skills/aziral-product-video/agents/openai.yaml) | Codex-facing metadata and example prompt |

The example is a planning input, not an implemented application or runnable composition. Missing source footage is explicit. Engine code, recorded footage, music and rendered videos are not included.

## Try it

Supply a recording or screenshots that you have permission to use, then ask:

```text
Use $aziral-product-video to plan a 12-second vertical demo from this app recording.
Show one action and its visible result. Prepare English, Russian and Kazakh text
variants, keep the UI readable, and identify unsupported claims. Deliver a
storyboard first. No voiceover or paid services are requested.
```

For rendering, specify the requested files, formats and sound. Translating a video's copy does not establish that the application itself supports those languages.

## Costs and scope

Local planning needs no paid media service. Rendering needs your own HyperFrames environment and its dependencies. Prefer local assets and rendering. Paid generation, cloud rendering, account linking and publication require the user's instructions and budget.

## Attribution and license

Official engine and upstream skills: [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes). Official documentation: [hyperframes.heygen.com](https://hyperframes.heygen.com/introduction).

AZIRAL's contribution here is the original `aziral-product-video` workflow, brief template and illustrative multilingual brief. [MIT](LICENSE) applies only to this repository's original files. Separately installed tools and supplied assets retain their own authorship and licenses.

Created by [Olzhas Azirali / AZIRAL](https://aziral.com/olzhas-azirali).

## Contributing

Clearer briefs, reproducible layout problems and language corrections are welcome. Include the requested format, relevant source context and observed result. Share only assets you have permission to publish.

## More AZIRAL skills

[HyperFrames workflows](https://github.com/azirali/hyperframes) · [Remotion promos](https://github.com/azirali/remotion) · [Brand frontend](https://github.com/azirali/taste-skill) · [UI release review](https://github.com/azirali/impeccable)

If this workflow helps your work, a star helps other developers discover it.
