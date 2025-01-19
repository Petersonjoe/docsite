# [Free AI Art Website](https://www.reddit.com/r/StableDiffusion/comments/18h7r2h/free_online_sdxl_generators/)

## Free Online SDXL Generators

### Resource - Update

- People often ask about online generators, so I've decided to make a post rather than writing the same reply again. Even if you have a local setup (which is of course more flexible and maybe faster), these online generators are useful when you are away from your computer, and also for testing out models and LoRAs without having to download them.

- My list consist only of free/semi-free sites that I've used personally. As for paid sites, there are just too many out there, and I've not tried them to have an opinion on them. But you are free to add comments about your favorite site here, of course.

- There are of course the two generators from the 800 pound gorillas of internet: [Bing/DALLE3](https://www.bing.com/images/create) and Google's [ImageFX/Imagine](https://aitestkitchen.withgoogle.com/tools/image-fx) (but it is available in US only?). There are also many free generators on discord, but I find them kind of clunky to use.

- The information is mostly up-to-date as of 2024-08-24, and I will try to keep it updated when things change. Please let me know if any information here is out of date by leaving a comment here.

### tensor. art (direct link to site is not allowed)

- 50 free credits per day, with the option of earning additional 50 through "interactions" such as posting images. Each generation can take between 0.5 to 2 (Flux at 25 steps) credits, depending on the number of steps. Additional credits are required for the use of upscaling and ADetailer. Note: if you use one of the turbo mode SDXL models, you can use CFG:2, Sampler: DPM++ SDE Karra at just 5 steps, which means you can generate **500 SDXL images per day!** This is a great way to test prompts.

- ComfyUI is offered as an alternative UI (but custom nodes are limited): tensor art/workflow. You may encounter weird errors and generation can be slow. But usually the image will come out eventually.

- Most of the major models and LoRAs are available and can be used by free accounts. Flux-Dev/Flux-Schenell-fp8 are supported. If you use 4-steps Flux-Schnell or (Flux-Dev + Schnell+LoRA) then each image only cost 0.4 credits.

- You can upload checkpoints and LoRAs. They must be public if you are using a free account. Paid "Pro" accounts can be used to host private LoRAs and checkpoints.

- N SFW generation are allowed, but there is some sort of filter, which I've never run into since I don't do N SFW.

- ADetailer is supported for fixing faces.

- Limited to 25 step (60 steps for paid)

- Hi-res has maximum resolution of 1920x1080 (very high limit for paid)

- Maximum of 3 LoRAs can be stacked (6 for paid)

- Image that are not posted will only be retained for 15 days (60 for pro)

- With the Pro account, you can also upload your own LoRAs for private use.

- **Tip:** if the image generation seems to get stuck, just close or refresh the Workspace. Reopen the Workspace and wait a bit. Your image will show up eventually, or you will see "Exception" and you will have to regenerate it again.

### [civitai.com/generate](https://civitai.com/login?returnUrl=%2Fgenerate)

- You can claim 25 free buzz per day (but you can easily earn more: <https://civitai.com/user/buzz-dashboard>, become a Civitai subscriber, or buy 5000 for $5). Each SDXL image costs around 3 buzz. At the moment, Flux generation is rather expensive.

- Cheap [LoRA training](https://education.civitai.com/using-civitai-the-on-site-lora-trainer/) (500 buzz or 50c per training for SDXL/SD1.5, 2000buzz for Flux).

- Huge selection of models and LoRAs

- Images can only be downloaded as JPEGs.

- When images are uploaded to Civitai the metadata will be parsed correctly.

- Selection of sampler is limited (Just basics ones like DPM++ 2M Karras, Euler)

- Some words are not allowed in prompts (for example, "dead"), but in general N SFW images are allowed.

- Quality is not as good as tensor. art, specially when LoRAs are used. (This problem has been fixed?)

- No LoRA based on a real person can be used.

- No ADetailer (yet)

- Resolution limited to 1024x1024, 1216x832 and 832x1216

### seaart.ai (note: direct link to site is banned) (Thanks to Ok-Vacation5730)

- A large selection of models and LoRAs

- Support LoRA training. Look under the "Train" tab and also "LoRA Template" for sample datasets.

- 150 Free "stamina" daily (Each SDXL image costs 6 stamina)

- ComfyUI is offered as an alternative UI.

- Flux is available via ComfyUI.

- Wide range of resolutions to choose from

- Images can be saved to a folder without having to be posted publically.

- Maximum of 40 steps

- Maximum of 3 LoRAs (up to 5 for paid account)

- Unsaved images are retained for only 14 days.

- Good selection of samplers

- **The user interface is a mess.** It is hard to figure out how to use the system, which has functionalities scattered all over the place in a non-intuitive way. Last time I tried, I cannot even download an image.

- ADetailer is only available for SD1.5

- Upscaler seems to produce poor quality images, at least none seems to work well for me when I tried it on SDXL models.

- **Tip:** to use SDXL, you need to click on SDXL (right beside "Default") on the top right-hand corner, or you'll be wondering why the resolutions are all wrong, and why you cannot switch to SDXL models.

- Make sure VAE is set to "auto".

- To download the image as PNG, you need to click on the image to show it in full screen, then the option to download will appear. Or you can save it to a folder first.

### [mage.space](https://mage.space)

- Seemingly unlimited SD3.5/Flux-Dev/Flux-Schnell.

- Weird, unintuitive user interface.

"Suggestive" images are blurred unless you pay.

### [LoRA Studio](https://lorastudio.co/models)

- Not really a "regular" image generator. Its main purpose is to let people explorer differnet LoRAs.

**No registration required (presumably no daily limit)**

- Just choose your LoRA and play with it.

### withflare.ai

- No limit on image generation

- SDXL Base only.

- Support for SDV

- Support for DALLE3

- Resolutions are limited to square, 16:9 and 9:16

- Choice of Sampler is a bit limited

### [leonardo.ai](https://app.leonardo.ai/) (thanks to u/Ancient-Camel1636)

- Besides their own proprietary models, leonardo.ai also supports the following openly available models: AlbedoXL (a very fine merged model), SDXL 0.9 base, Deliberate 1.1, DreamShaper v5-v7, RPG v4/v5, and Absolute Reality 1.6.

- Max resolution is 1536x1536

- Cost is tied to resolution. For 512x512 the cost is 2 points. For 832x1216 the cost is 3.

Free plan: <https://app.leonardo.ai/buy>

150 fast generations per day, combined in any of the following ways: (I believe this is out of date, currently even 512x512 cost 2 points)

- Up to 150 (768x768) generations per day

- Up to 30 upscales or unzooms per day

- Up to 75 background removals per day

- Daily free tokens when your balance falls below 150

Other features/limitations:

- Up to 1 pending jobs

- Private generations

- Priority infrastructure

- Relaxed generation queue

- No Concurrency

### [playgroundai.com](https://playgroundai.com/)

- Only base SDXL/Playground V2/2.5 supported (support for SD1.5 has been removed). But when you use SDXL there are many "filters" to choose from, and those filters have names such as "StarlightXL", "ZavyChromaXL", etc., so those filters are presumably LoRAs extracted from popular fine-tuned model.

- Create 10 (15?) images every 3 hours/Wait times during peak hours/Waiting period after 15 images

- Maximum resolution is 1024x1024

### [gen-image.com](https://gen-image.com/)

- Free to use, no registration needed.

- Unlimited generation per day.

- There is no N SFW filter, but since only model is SDXL Lightning based model, it is not that good at N SFW.

- SDXL Lightning based model (1024x1024)

- No special features

### [ideogram.ai](https://ideogram.ai/)

- Not recommended due to inability to delete images.

- New service with a proprietary model.

- 10 free prompts per day (4 images per prompt)

- WARNING: image generate are public and cannot be deleted!

- Prompt following is very good, almost DALLE3 level.

- Censored like DALLE3, but more relaxed. Nudity is not allowed, but the level of censorship is at least sane.

- Can render text very well.

- Can generate image with moderate complexity involving more than one subject.

### [stablehorde.net](https://stablehorde.net/)

- I also applaud the effort made by stablehorde.net for providing this valuable service to the community. The top 3 on my list, tensor. art, civitai.com, and seaart. ai probably still offer more models, but I've not used horde for a while, so horde's list of models and LoRAs may match those services too. But in general, the free services I mentioned are faster than horde.

- Here are some useful information for those to want to try stablehorde:

### Image Generation

- We provide [a client interface](https://dbzer0.itch.io/lucid-creations) requiring no installation and no technical expertise

- We have also a few dedicated Web UIs with even less requirements:
  - [Art Bot](https://tinybots.net/artbot)
  - [Stable UI](https://aqualxx.github.io/stable-ui/)
  - [AAAI UI](https://artificial-art.eu/)

- There are also mobile apps:
  - AI Painter ([iOS](https://apps.apple.com/hk/app/%E6%A9%9F%E7%95%AB%E5%B8%AB-%E5%B0%88%E6%A5%AD%E7%9A%84ai%E7%B9%AA%E7%95%ABapp/id1644645946) + [Android](https://play.google.com/store/apps/details?id=wkygame.ai.all.in.one))
  - aislingeach ([iOS](https://github.com/amiantos/aislingeach))
