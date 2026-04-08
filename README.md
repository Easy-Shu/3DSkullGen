# 3DSkullGen
3D skull generation is essential for smart healthcare applications such as craniofacial reconstruction, forensic anthropology, and surgical planning. We collected 500 high-resolution skull meshes from the public MUG500+ database for skull generation tasks. All meshes were parameterized using non-rigid iterative closest point (ICP) and aligned to a unified template via Procrustes analysis.  The resulting parametric mesh dataset will be made publicly available after the acceptance of this paper.

<img src="https://github.com/Easy-Shu/3DSkullGen/blob/main/Fig_Dataset.png" width=100% alt="Demo"></img>
Examples of 3D skull parameterization. (a) Original skull meshes generated from CT images. (b) 3D registrated skull meshes created using the NICP algorithm. (c) Per-vertex registration error colormaps. The mean $\pm$ standard deviation of registration errors for all 600 real skull meshes is 0.45 $\pm$ 0.06 mm.


## Citation
If you find our work useful to your research, please consider citing:
```
@article{li2021mug500+,
  title={MUG500+: Database of 500 high-resolution healthy human skulls and 29 craniotomy skulls and implants},
  author={Li, Jianning and Krall, Marcell and Trummer, Florian and Memon, Afaque Rafique and Pepe, Antonio and Gsaxner, Christina and Jin, Yuan and Chen, Xiaojun and Deutschmann, Hannes and Zefferer, Ulrike and others},
  journal={Data in Brief},
  pages={107524},
  year={2021},
  publisher={Elsevier}
}
```

## Contacts
Please contact jpeter.zhang@mpu.edu.mo or open an issue for any questions or suggestions.

