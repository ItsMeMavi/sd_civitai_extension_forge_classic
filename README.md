# Civitai Extension for Forge-Classic Stable Diffusion Web UI

Manage and interact with your Forge-Classic SD instance right from Civitai



## Features
- [x] Automatically download preview images for all models, LORAs, and embeds
- [x] Automatically download a model based on the model hash upon applying pasted generation params
- [x] Resources in Metadata: Include the SHA256 hash of all resources used in an image to be able to automatically link to corresponding resources on Civitai
- [x] Flexible Resource Naming in Metadata: Hashify the names of resources in prompts to avoid issues with resource renaming and make prompts more portable
- [x] **[Civitai Link (Alpha)](https://civitai.com/v/civitai-link-intro):** Optional websocket connection to be able to add/remove resources and more in your SD instance while browsing Civitai or other Civitai Link enabled sites.

## Installation

### Through the Extensions UI (Recommended)
1. Open the Extensions Tab in Forge-Classic SD Web UI
2. In the Extension Tab Open the "Instal from URL" tab
3. Paste `https://github.com/ItsMeMavi/sd_civitai_extension_forge_classic.git` into the URL input
4. Press install and wait for it to complete
5. **Restart Automatic1111** (Reloading the UI will not install the necessary requirements)

