# KUAICV_CDH_Assignment_221106
Improving image reconstruction performance using Implicit Neural Representations

<img width="600" alt="image" src="https://user-images.githubusercontent.com/41141851/204118382-38f361b7-f0e0-4e95-884d-33eb8eecb90a.png">

*Tancik, Matthew, et al. "Fourier features let networks learn high frequency functions in low dimensional domains." Advances in Neural Information Processing Systems 33 (2020)*

- Notion Link: [Notion Link](https://dongdong9698.notion.site/221106-07abc7ec0bba4914afe708951539b986)

<img width="1136" alt="image" src="https://user-images.githubusercontent.com/41141851/204118448-78d25a7a-f169-43b1-9949-5217c8c3f2c8.png">

---

## Getting Started

### Installation

```shell
git clone https://github.com/hyeon9698/KUAICV_CDH_Assignment_221106.git
cd KUAICV_CDH_Assignment_221106
```

### Download DIV2K_valid_HR Dataset

```
wget http://data.vision.ee.ethz.ch/cvl/DIV2K/DIV2K_valid_HR.zip
unzip DIV2K_valid_HR.zip
```

### Run ipynb file

|File name|Method|
|-:|-|
|baseline_No_fourier.ipynb|baseline no fourier|
|baseline_Fourier.ipynb|baseline|
|baseline_SIREN_only_activation.ipynb|baseline+Sine Activation|
|baseline_SIREN.ipynb|SIREN|
|baseline_SIREN_Fourier.ipynb|SIREN+Fourier|
|baseline_LPIPS_VGG.ipynb|LPIPS VGG|
|baseline_LPIPS_ALEX.ipynb|LPIPS ALEX|
|baseline_perceptual_loss.ipynb|Perceptual Loss|
|baseline_SIREN_Fourier_Perceptual_loss.ipynb|SIREN+Fourier+Percep.L|

---

## Quantitative Evaluation

<img width="400" alt="image" src="https://user-images.githubusercontent.com/41141851/204196197-e9fe540c-eeac-4c73-b34d-9c6d25ff37d5.png">

## Qualitative Analysis

![image](https://user-images.githubusercontent.com/41141851/204196664-44729e5f-58ac-44f7-9d33-7e73fe4f20bf.png)

## Reference

>- [Pytorch Fourier Feature Networks Code](https://github.com/ndahlquist/pytorch-fourier-feature-networks)
>- Fourier Feature Networks - Tancik, Matthew, et al. "Fourier features let networks learn high frequency functions in low
dimensional domains." Advances in Neural Information Processing Systems 33 (2020): 7537-7547.
>- SIREN - Sitzmann, Vincent, et al. "Implicit neural representations with periodic activation
functions." Advances in Neural Information Processing Systems 33 (2020)
>- LPIPS - Zhang, Richard, et al. "The unreasonable effectiveness of deep features as a perceptual metric."
Proceedings of the IEEE conference on computer vision and pattern recognition. 2018.
>- Perceptual Loss - Johnson, Justin, Alexandre Alahi, and Li Fei-Fei. "Perceptual losses for real-time style transfer and super-resolution." European conference on computer vision. Springer, Cham, 2016.