# 🎙️ Wav2Lip – Simplified Google Colab Setup

This notebook provides a **clean, functional Google Colab implementation** of the Wav2Lip model — enabling high-quality lip-syncing from a face image and an audio clip.

### 🛠️ What’s Different About This Repo?

While the original [Wav2Lip repository](https://github.com/Rudrabha/Wav2Lip) offers the full model code and paper, it’s not designed to run smoothly in Google Colab out of the box. This notebook streamlines that process:

- ✅ **Tested Colab workflow** — all steps work as of [May 2025]
- 🛠️ **Fixes common errors** (like `librosa` incompatibility)
- 🧹 **Removed vestigial/debug code** to simplify the process
- 🎬 Ideal for creators, experimenters, or AI-curious users wanting a fast result

---

# What goes in?
<img width="618" alt="AbberantMiss" src="https://github.com/user-attachments/assets/3d85bd2d-55e1-4194-bff6-2ea2f813fd70" />

# What comes out?


https://github.com/user-attachments/assets/dbee784f-9cee-4205-8493-49da56e65135


## 📄 Requirements

- A Google account
- Google Colab (free to use)
- One face image (`.jpg` or `.png`)
- One audio file (`.wav`, mono preferred)(converter present in notebook as well)

---

## 🚀 How to Use

1. Open the notebook in Colab:  
   👉 [Run on Colab]([https://colab.research.google.com/drive/YOUR_NOTEBOOK_LINK](https://colab.research.google.com/drive/17QQpBTHAiTBHQg91qtcQiLMp9K14XOGP?usp=sharing))

2. Upload your face image and audio clip  
3. Run cells sequentially  
4. Download your synced video!

---

## 🧠 Background

Wav2Lip is a state-of-the-art lip-sync model developed by Rudrabha et al. This notebook uses the official pretrained models and simplifies the setup for use in browser-based environments.

For more on the research:  
📄 [Wav2Lip Paper](https://arxiv.org/abs/2008.10010)  
🔗 [Official GitHub Repo](https://github.com/Rudrabha/Wav2Lip)

---

## ⚠️ Known Challenges (and Fixes Included)

- **`librosa` import errors** due to version conflicts  
- File path issues on Colab with `.wav` files  
- `audio.py` decoding workaround for some audio formats

All of these are resolved or patched in this notebook.

---

## 📜 License

This repo uses the Wav2Lip model weights under the license provided by the original authors.  
Notebook authored by Spencer Toulouse. Feel free to remix this setup — attribution appreciated.

---

## ✨ Notes

This is part of a broader effort to make research-backed tools more accessible to artists, animators, and builders.  
More projects like this: [spencer-video.com](https://spencer-video.com)
# wav2lip-colab-simplified
This notebook provides a **clean, functional Google Colab implementation** of the Wav2Lip model — enabling scary early AI vibe lip-syncing from a face image and an audio clip.
