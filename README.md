<div align="center">

# 🧶 Unravel: Recovering an Interactive 3D Scene from a Single Image


<a href="https://arxiv.org/abs/2610.16146"><img src="https://img.shields.io/badge/arXiv-2610.16146-b31b1b.svg" alt="arXiv"></a>
<a href="https://arxiv.org/abs/2610.02274"><img src="https://img.shields.io/badge/Tech%20Report-2610.02274-blue.svg" alt="Technical Report"></a>
<a href="https://github.com/SII-Hui/Unravel"><img src="https://img.shields.io/badge/Code-GitHub-black.svg" alt="Code"></a>

📢 Unravel is also covered in the technical report [*Awomo-SimDataEngine: Agentic Simulation-Ready World Generation*](https://arxiv.org/abs/2610.02274).

</div>

<p align="center">
  <img src="assets/Teaser.jpg" width="100%" alt="Unravel teaser">
</p>

✨ **Unravel** turns a single image into an interactive 3D scene where every object is an independent, movable asset. It first takes the scene apart, removing objects from the image layer by layer until the room is empty and capturing each one as a 3D asset when it is best exposed. It then rebuilds the scene in reverse removal order, followed by physical settling and an agentic audit, yielding a faithful and physically plausible layout.

## 🧩 Deconstruct → Recompose

<p align="center">
  <img src="assets/Video.gif" width="100%" alt="Unravel pipeline animation">
</p>

**Phase 1 · Layer-wise deconstruction**: plan, edit and verify removals round by round, saving each object as an individual asset before it is removed.  
**Phase 2 · Support-aware recomposition**: rebuild the scene in reverse order, aligning and placing each asset, refining support and reducing object overlap.

## 🚀 Quick Start

⚙️ Coming soon!

## 🎨 Qualitative Results

### 🔍 Layer-wise Deconstruction Traces

<p align="center">
  <img src="assets/Results_1.jpg" width="100%" alt="Deconstruction traces with extracted assets">
</p>

<p align="center">
  <img src="assets/Results_2.jpg" width="100%" alt="More deconstruction traces">
</p>


### 🏠 More Reconstructed Scenes

<p align="center">
  <img src="assets/Results_3.jpg" width="100%" alt="Additional reconstructions">
</p>



## 🙏 Acknowledgements

Unravel is built upon several excellent open-source projects. We thank the authors of [MoGe](https://github.com/microsoft/MoGe), [SAM 3](https://github.com/facebookresearch/sam3) and [TRELLIS.2](https://github.com/microsoft/TRELLIS.2) for making their code and models publicly available.

## 📝 Citation

If you find this work useful, please consider citing:

```bibtex
@misc{shan2026unravelrecoveringinteractive3d,
      title={Unravel: Recovering an Interactive 3D Scene from a Single Image}, 
      author={Hui Shan and Keyang Luo and Binjia Zhou and Ming Li and Kai Li and Xin Wang and Zhenyang Li and Zesong Yang and Weikai Chen and Runze Zhang and Xin Wang and Yanwei Fu and Zhen Chen and Xiangru Huang},
      year={2026},
      eprint={2610.16146},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2610.16146}, 
}
```
