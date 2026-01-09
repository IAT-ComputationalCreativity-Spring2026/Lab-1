# IAT 460 — Week 1 Lab: Introduction to Python, PyTorch, and Data Modalities

Welcome to the Week 1 lab for **IAT 460 - Computational Creativity**! This repository contains the lab materials for exploring basic programming, data manipulation, and creative computing using Python.

---

## Lab Overview

In this lab, you will get hands-on experience with:

- **Python basics**: loading, inspecting, and manipulating data.
- **Data modalities**:
  - **Images** with Pillow
  - **Audio** with librosa
  - **Symbolic music / MIDI** with pretty_midi
- **PyTorch basics**: tensors, modules, and operations (introduction only)
- **Visualization**: matplotlib and IPython display utilities

**Objectives**:

- Observe and experiment with different types of data.
- Learn to manipulate images, audio, and MIDI symbolically.
- Prepare for more advanced generative workflows later in the course.

> **Note**: You are not expected to understand all the code yet. Focus on exploration, experimentation, and discussion.

---

## Running python notebooks

### Option 1

If you are familiar with github, you can clone this repo and run the notebook in your IDE or tool of choice.

```bash
git clone https://github.com/IAT-ComputationalCreativity-Spring2026/Lab-1.git
cd Lab-1
```

Create a python virtual environmment (Python 3.12 recommended).

```bash
python3 -m venv .venv
# or
conda create -n iat460lab1 python=3.12
```

### Option 2

The provided notebook is accessible in Google Colab and requires no setup ([link](https://colab.research.google.com/github/IAT-ComputationalCreativity-Spring2026/Lab-1/blob/main/lab.ipynb))

---

## Working with assets

If you're comfortable with python libraries, here is a list of suggestions for you to potentially check out:

- 2D Images:        [PIL (Pillow)](https://pillow.readthedocs.io/en/stable/index.html)
- Symbolic Music:   [pretty_midi](https://craffel.github.io/pretty-midi/)
- Audio:            [librosa](https://librosa.org/doc/latest/index.html)
- Video:            [MoviePy](https://zulko.github.io/moviepy/)
- Text:             [NLTK](https://www.nltk.org/)
- 3D Mesh:          [PyMesh](https://pymesh.readthedocs.io/en/latest/)
- Compute Shaders:  [Python Arcade](https://api.arcade.academy/en/stable/tutorials/compute_shader/index.html)

Some more general multi-media libraries

- [pygame](https://www.pygame.org/wiki/about): More established than aformentioned Python Arcade but no custom shaders
- [OpenCV](https://opencv.org/): Useful for images, video, etc. May be overkill in simple cases
- [torchvision](https://pytorch.org/vision/stable/index.html), [torchaudio](https://pytorch.org/audio/stable/index.html): Mostly for integrating with PyTorch models but may contain some useful GPU-accelerated functionality
