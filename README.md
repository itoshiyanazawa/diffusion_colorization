# Colorization of Historical Photographs using Diffusion Model

## Objective
The goal of this research is to colorize historical photographs using a diffusion model to improve their quality and contribute to research in the field of history. Colorization can enhance the clarity of photographs, allowing for better understanding of past situations and environments.

## Methodology
1. **Dataset**: The Historical Color Image Database, containing 1325 images taken between 1930 and 1970, was used for training and evaluation.
2. **Models**:
  - **Diffusion Model**: The palette model available on GitHub was used for colorization.
  - **Pix2Pix**: A comparative model based on Generative Adversarial Networks (GANs) for image-to-image translation.
3. **Data Preprocessing**: Images were resized to 256x256 and converted to grayscale using Python libraries (PIL and OpenCV).
4. **Training**: Original images and grayscale images were used as input-output pairs for training both models.
5. **Evaluation**:
  - **Quantitative**: Fréchet Inception Distance (FID), Inception Score (IS), and Mean Squared Error (MSE) were used for evaluation.
  - **Qualitative**: Visual evaluation and survey-based comparison between diffusion model and pix2pix outputs.

## Results
- The diffusion model outperformed pix2pix in terms of FID (30.00 vs. higher) and IS (11.28 vs. lower) scores.
- 88% of survey respondents found the diffusion model's colorization results more natural and free from artifacts compared to pix2pix.
- The diffusion model successfully colorized both human and machine subjects, while pix2pix struggled with various subjects.

## Conclusion
The diffusion model proved to be the superior choice for colorizing historical photographs, providing better quality and more consistent results across different subjects. This technique can be valuable for historical research, enabling a better understanding of the past through enhanced visual information.

## Keywords
Image synthesis, Diffusion model, GAN, FID, IS

## Reference
1. 宮脇勝, 鎌田祥史. 古写真を用いた歴史的景観の観察方法に関する研究. 都市計画論文集, Vol. 51, No. 3, pp. 320–327, 2016.
2. 桑山哲郎. カラー写真方式の歴史. 日本写真学会誌, Vol. 66, No. 6, pp. 569–576, 2003.
3. Benjamin Detenber and Samuel Winch. The impact of color on emotional responses to newspaper photographs. Visual Communication Quarterly, Vol. 8, pp. 4–14, 06 2001.
4. Frank Palermo, James Hays, and Alexei A. Efros. Dating historical color images, 2012.
5. Ian J. Goodfellow, Jean Pouget-Abadie, Mehdi Mirza, Bing Xu, David Warde-Farley, Sherjil Ozair,
Aaron Courville, and Yoshua Bengio. Generative adversarial networks, 2014.
6. Phillip Isola, Jun-Yan Zhu, Tinghui Zhou, and Alexei A. Efros. Image-to-image translation with
conditional adversarial networks, 2016.
7. Jonathan Ho, Ajay Jain, and Pieter Abbeel. Denoising diffusion probabilistic models, 2020.
8. Prafulla Dhariwal and Alex Nichol. Diffusion models beat gans on image synthesis, 2021.
9. Yann LeCun, Corinna Cortes, and Christopher J.C. Burges. The mnist database of handwritten digits.
http://yann.lecun.com/exdb/mnist/, 1998.
10. Joshua Susskind, Adam Anderson, and Geoffrey E. Hinton. The toronto face dataset, 2010.
11. Alex Krizhevsky. Learning multiple layers of features from tiny images, 2009.
12. Olga Russakovsky, Jia Deng, Hao Su, Jonathan Krause, Sanjeev Satheesh, Sean Ma, Zhiheng Huang,
Andrej Karpathy, Aditya Khosla, Michael Bernstein, Alexander C. Berg, and Li Fei-Fei. ImageNet Large Scale Visual Recognition Challenge. International Journal of Computer Vision (IJCV), Vol. 115, No. 3, pp. 211–252, 2015.
13. Chitwan Saharia, William Chan, Huiwen Chang, Chris A. Lee, Jonathan Ho, Tim Salimans, David J. Fleet, and Mohammad Norouzi. Palette: Image-to-image diffusion models, 2021.
14. Martin Heusel, Hubert Ramsauer, Thomas Unterthiner, Bernhard Nessler, and Sepp Hochreiter. Gans trained by a two time-scale update rule converge to a local nash equilibrium. 2017.
15. Overview of gan structure — machine learning — google developers. https://developers. google.com/machine-learning/gan/gan_structure, Last updated 2022-07-18.
16. Olaf Ronneberger, Philipp Fischer, and Thomas Brox. U-net: Convolutional networks for biomedical image segmentation, 2015.
17. Richard Zhang, Phillip Isola, and Alexei A. Efros. Colorful image colorization, 2016.
18. Inception v3 詳細ガイド — cloud tpu — google cloud. https://cloud.google.com/tpu/
docs/inception-v3-advanced?hl=ja, Last updated 2022-09-13.
19. Tim Salimans, Ian Goodfellow, Wojciech Zaremba, Vicki Cheung, Alec Radford, and Xi Chen.
26
Improved techniques for training gans, 2016.
20. Gaurav Parmar, Richard Zhang, and Jun-Yan Zhu. On aliased resizing and surprising subtleties in gan
evaluation, 2021.
21. Github - bioinf-jku/ttur: Two time-scale update rule for training gans. https://github.com/
bioinf-jku/TTUR, 2017.
22. Fid ― pytorch-ignite v0.4.10 documentation. https://pytorch.org/ignite/generated/
ignite.metrics.FID.html, Last updated on 2023.
23. Liangwei Jiang. Github - janspiry/palette-image-to-image-diffusion-models: Unofficial implementa-
tion of palette: Image-to-image diffusion models by pytorch. https://github.com/Janspiry/
Palette-Image-to-Image-Diffusion-Models, 2022.
24. Places-2 mit dataset — kaggle. https://www.kaggle.com/datasets/nickj26/
places2-mit-dataset, 2017.
