# HTGM v2 Hindi LLM – Session 21 | 180+ Hours Training Progress 🚀

## Overview

Session 21 of HTGM v2 Hindi LLM training is now completed.

This session highlights an important phase in long-term LLM training — **high learning rate instability**. While total training reached **180+ hours** and **48K+ optimizer steps**, the model showed noticeable fluctuation in validation performance.

This is a critical learning stage in building a Hindi LLM from scratch.

---

## Session Information

- Session Number: 21  
- Total Training Time: 180+ Hours  
- Total Sessions Completed: 21  
- Optimizer Steps: 48,922+  
- Training Progress: ~5%  

---

## Technical Details

- Model Name: HTGM v2  
- Type: Hindi Large Language Model (Hindi LLM)  
- Architecture: GPT-style Transformer  
- Model Size: 163.4M Parameters  
- Sequence Length: 2048  
- Vocabulary Size: 100,000  
- Dataset Size: ~41GB  
- Platform: Kaggle  
- GPU: 2x NVIDIA T4  
- Tokenizer: Hugging Face BPE  

---

## Training Progress

- Resumed From Checkpoint: `ckpt_final_s1489843.pt`  
- Current Step: 48,922+  
- Mid Checkpoints:
  - `ckpt_s47000.pt`
  - `ckpt_s48000.pt`  
- Final Checkpoint:
  - `ckpt_final_s1565523.pt`  

---

## Dataset Used

- chunk_1.txt  
- chunk_2.txt  
- chunk_3.txt  

---

## Training Metrics

### Core Metrics

- Training Loss: 4.1719  
- Peak Loss (Session): 5.0052  
- Final Validation Loss: 4.9570  
- Validation Perplexity: 142.16  
- Training Perplexity: 64.83  

### Optimization Metrics

- Learning Rate: ~2.99e-04  
- Gradient Norm: 0.3604  
- Tokens/sec: ~2817  

---

## Key Observations

### What Happened

- Validation loss slightly increased  
- Perplexity increased (~142)  
- Loss spikes observed  
- Learning rate significantly higher than stable range  

### What It Means

This is a **high learning rate instability phase**.

Model updates became aggressive, leading to oscillating training behavior.

---

## Why This Matters

This session proves:

- Training pipeline is stable  
- Checkpoint system is reliable  
- But hyperparameter tuning is critical  

Especially:

👉 Learning rate control directly impacts stability  

---

## Current Status

- Training continues  
- No crashes  
- GPU utilization stable  
- Checkpoints working perfectly  
- Model still learning overall  

---

## Next Steps

- Reduce learning rate  
- Stabilize scheduler  
- Avoid aggressive updates  
- Push beyond 50K steps  
- Prepare for Supervised Fine-Tuning (SFT)  

---

## Author

**Mahesh Editor**  
Independent AI Researcher  
India AI Official  

---

## Build in Public

No shortcuts.  
No fake results.  
Only real experiments.

This is how real AI is built — step by step.
