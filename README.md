# TadGAN

TadGAN: Time Series Anomaly Detection Using Generative Adversarial Networks
paper link : https://arxiv.org/abs/2009.07769

[KOR]
본 Repo는 TadGAN 알고리즘을 TF 2.0 Version에 맞게 구현한 코드를 가지고 있습니다.
TadGAN은 Python library 중 orion-ml (https://github.com/signals-dev/Orion) 을 활용하여 사용할 수 있습니다.
orion-ml은 Pip install을 통해 바로 사용할 수 있으나 orion-ml에서 지원하는 TF가 2.0버전 미만에서만 작동됩니다. 
최신 버전의 TF, Keras를 제대로 지원하지 못하고 있습니다. 따라서, 이를 TF 2.0 이상의 최신 버전에서
사용자가 직접 모델을 Customized 할 수 있도록 모델 부분만 따로 떼어내서 구현한 내용입니다.

[ENG]
This repository implements a TadGAN for tensorflow 2.0 version. 
If you want to use the original TadGAN, please visit this -> Orion-ml(https://github.com/signals-dev/Orion)
Orion-ml can be installed through pip, but tensorflow supported by orion-ml is less than version 2.0. 
Therefore, please refer to this code when running TadGAN in tensorflow version 2.0 or higher.

[Note]
현재 Forecasting, Validation 은 구현 중에 있습니다. 코드 대부분이 Orion-ml에서 제공하는 TadGAN tutorial과 
동일하니, 해당 부분은 Orion-ml에서 제공하는 TadGAN tutorial을 참고 해주세요.
현재 새로운 환경에서 개발 작업 중 입니다. 

Forecasting, Validation functions are being implemented. Most of the code is based on TadGAN tutorial
provided by Orion-ml. Please refer to the TadGAN tutorial. 