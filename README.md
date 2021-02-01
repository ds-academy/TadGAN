# TadGAN

TadGAN: Time Series Anomaly Detection Using Generative Adversarial Networks
paper link : https://arxiv.org/abs/2009.07769

본 Repo는 TadGAN 알고리즘을 TF 2.0 Version에 맞게 구현한 코드를 가지고 있습니다.
TadGAN은 Python library 중 orion-ml (https://github.com/signals-dev/Orion) 을 활용하여 사용할 수 있습니다.

Pip install을 통해 바로 사용할 수 있으나 orion-ml에서 지원하는 TF가 2.0버전 미만에서 제대로 작동되는 문제가 있습니다.
최신 버전의 TF, Keras를 제대로 지원하지 못하고 있습니다. 따라서, 이를 TF 2.0 이상의 최신 버전에서
사용자가 직접 모델을 Customized 할 수 있도록 모델 부분만 따로 떼어내서 구현한 내용입니다.
