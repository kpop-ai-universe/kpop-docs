---
label: RVC Disconnected Guide
author: kyuroll
---

# How to train with RVC Disconnected


!!!danger "Outdated Content"
This tutorial is considered outdated as RVC Disconnected is now discontinued. Use for reference only.
!!!

## Step 1: Audio Separation (Dataset)
The most important part of creating an AI model is having a clean dataset. The cleaner the audio (no background noise or distortion), the more realistic the final voice will sound. Ensure your audios are high quality and in **WAV** format.

**Recommended Tools:**
- **cobalt.tools**: Best option (no ads).
- **mvsep.com**: Good online alternative (create an account to skip the queue).

**Useful UVR Models:**
- **[MDXC] MB InstVoc Duality v1**: Best for extracting the acapella.
- **[MDXC] MB Inst v1e**: To extract the instrumental.
- **[MDXC] Mel-Karaoke**: For backing vocals.
- **[VR Arch] 6-HP Karaoke**: Cleanest way to get lead vocals.

**Aggressiveness Note:** I recommend using **25** for the ideal balance. For De-Echo or De-Noise, you can go up to **100**. Ensure your file is under 10MB.

## Step 2: Dataset Editing with Audacity
This is the tedious part: removing every strange detail or background noise.
- Use `CTRL + L` to silence selected areas.
- Use `CTRL + K` to cut empty parts.
- **Tip:** Combine all your song snippets into one single file BEFORE extracting the acapella. Then, clean the dataset and save it as a **WAV** inside a **ZIP** file.

## Step 3: Model Training
1. Open the [RVC Disconnected Colab](https://colab.research.google.com/drive/1XIPCP9ken63S7M6b5ui1b36Cs17sP-NS).
2. Upload your `.zip` file to the dedicated folder in your Google Drive.
3. Set your model name and the **target sample rate**.

**Epochs Configuration:**
- 10min audio + pre-train: Increase by 100 until it sounds good.
- No pre-train: 200-300 epochs.
- <5min audio (no pre-train): Max 250-300 epochs.
- >10min audio (no pre-train): 400-500 epochs.
- >20min audio: 500+ epochs (do not exceed 800 to avoid overtraining).

Once finished, click **"Export model to drive"** and **"Index Training"**. Download the `.pth` and the `ADDED` files, ZIP them, and upload to HuggingFace.