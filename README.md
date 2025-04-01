# CycleGAN (Keras & PyTorch Implementation for SK hynix FAST TRACK)

This repository contains re-implementations of CycleGAN using both **Keras** and **PyTorch**, tailored for the **SK hynix FAST TRACK** project. The original CycleGAN architecture was adapted to explore unpaired image-to-image translation tasks relevant to real-world industrial use cases.

## Project Highlights

- Based on the paper:  
  [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks (Zhu et al., 2017)](https://arxiv.org/abs/1703.10593)
  
- Implemented using both:
  - **Keras (TensorFlow backend)**
  - **PyTorch**

- Used in **SK hynix FAST TRACK** for experimental research on domain translation tasks.

## Repository Structure


## Getting Started

1. Prepare your dataset in the following structure:
    ```
    data/
    ├── trainA/
    └── trainB/
    ```

2. Open and run one of the implementation notebooks depending on your preferred framework:
    - `Keras`: [`(keras)_CycleGAN.ipynb`](./(keras)_CycleGAN.ipynb)
    - `PyTorch`: [`(torch)_CycleGAN.ipynb`](./(torch)_CycleGAN.ipynb)

3. For explanation and line-by-line review of PyTorch code, see:  
   [`(torch)_CycleGAN_review.ipynb`](./(torch)_CycleGAN_review.ipynb)

4. For experimental or deeper versions of the architecture, check:  
   [`(deep)_CycleGAN.ipynb`](./(deep)_CycleGAN.ipynb)

## Original Paper

Original GitHub Repository: [https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix](https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix)

## Notes

- This codebase was used in the **SK hynix FAST TRACK** project to evaluate unpaired image translation models for internal use cases.
- All code is implemented in Jupyter Notebook format for accessibility and experimentation.

## License

This project is based on CycleGAN under the MIT License. Check the original repository for more details.
