# IU Xray Report Generation

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Python](https://img.shields.io/badge/python-3.10+-blue.svg)

## Overview

IU-Xray-Report-Generation is a project aimed at generating medical reports from chest X-ray images. The project leverages advanced deep learning techniques to automatically interpret X-ray images and produce comprehensive and accurate reports.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **Automated Report Generation:** Generate detailed medical reports from chest X-ray images.
- **Deep Learning Models:** Utilizes state-of-the-art deep learning models for image processing and natural language generation.
- **End-to-End Pipeline:** Complete pipeline from image preprocessing to report generation.
- **Customizable:** Easy to modify and extend for different datasets and model architectures.

## Dataset

The IU X-ray dataset consists of chest X-ray images and corresponding medical reports. Ensure you have the necessary permissions to use the dataset and comply with its terms of use.
You can download the dataset from [here](https://drive.google.com/file/d/1DS6NYirOXQf8qYieSVMvqNwuOlgAbM_E/view?usp=sharing) and then put the files in data/iu_xray.


## Model Architecture

This project uses a hybrid architecture combining convolutional neural networks (CNNs) for image feature extraction and recurrent neural networks (RNNs) for report generation. The architecture can be visualized as follows:

1. **CNN Encoder:** Extracts features from the X-ray images.
2. **Attention Mechanism:** Focuses on relevant parts of the image during report generation.
3. **RNN Decoder:** Generates the report text based on the extracted features.

## Results

The model achieves competitive performance on the IU X-ray dataset, with significant improvements over baseline methods.

## Contributing

We welcome contributions to improve IU-Xray-Report-Generation. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank the contributors of the IU X-ray dataset and the developers of the deep learning frameworks used in this project.

## Citation

If you find this project useful in your research, please cite the following paper:

```bibtex
@inproceedings{chen-emnlp-2020-r2gen,
    title = "Generating Radiology Reports via Memory-driven Transformer",
    author = "Chen, Zhihong and
      Song, Yan  and
      Chang, Tsung-Hui and
      Wan, Xiang",
    booktitle = "Proceedings of the 2020 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2020",
}
```
---

