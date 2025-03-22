<img src='resources/nerficg_banner.png' width=100%>

![Python](https://img.shields.io/static/v1?label=Python&message=3.11&color=success&logo=Python)&nbsp;![PyTorch](https://img.shields.io/static/v1?label=Pytorch&message=2.5&color=success&logo=PyTorch)&nbsp;![CUDA](https://img.shields.io/static/v1?label=CUDA&message=11.8&color=success&logo=NVIDIA)&nbsp;![OS](https://img.shields.io/static/v1?label=OS&message=Linux&color=success&logo=Linux)&nbsp;[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)

# Welcome to the NeRFICG project page!

NeRFICG is a flexible PyTorch framework for simple and efficient implementation and evaluation of neural radiance fields and rasterization-based view synthesis methods, including a GUI for interactive rendering.

<div class="image-row">
<a href="resources/teaser_videos/inpc.mp4">
    <img src="resources/teaser_videos/inpc.gif" width="48%"/>
</a>
<a href="resources/teaser_videos/dnpc.mp4">
    <img src="resources/teaser_videos/dnpc.gif" width="48%"/>
</a>
</div>

## Project structure
This project consists of multiple subrepositories.
Check out the [main repository](https://github.com/nerficg-project/nerficg) as a starting point for further instructions.

## Standalone Methods
- [HTGS](https://github.com/nerficg-project/HTGS) - A perspective-correct and view-consistent approach for 3D Gaussian splatting accelerated through hybrid transparency.
- [DNPC](https://github.com/MoritzKappel/D-NPC) - An efficient high-quality method for dynamic scene reconstruction from monocular video.
- [INPC](https://github.com/nerficg-project/INPC) - A method for high-quality novel view synthesis that uses an implicit volumetric model in combination with fast neural point rendering.
- [MoNeRF](https://github.com/MoritzKappel/MoNeRF) - An extremely fast neural radiance field approach for monocularized sequences like the [D-NeRF](https://github.com/albertpumarola/D-NeRF) dataset.

## License and Citation

This framework is licensed under the [MIT license](https://github.com/nerficg-project/nerficg/blob/main/LICENSE).

If you use this project in your research code, please consider citing it:
```bibtex
@software{nerficg,
    author = {Kappel, Moritz and Hahlbohm, Florian and Scholz, Timon},
    license = {MIT},
    month = {1},
    title = {NeRFICG},
    url = {https://github.com/nerficg-project},
    version = {1.0},
    year = {2025}
}
```
