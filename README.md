# pyqt-using-finetuned-resnet50-example
<div align="center">
  <img src="https://user-images.githubusercontent.com/55078043/229002952-9afe57de-b0b6-400f-9628-b8e0044d3f7b.png" width="150px" height="150px"><br/><br/>
  
  [![](https://dcbadge.vercel.app/api/server/cHekprskVE)](https://discord.gg/cHekprskVE)
</div>

PyQt example of using fine-tuned resnet50 model for image classficiation of user-defined image (anteater, hyena)

## What is ResNet50?
ResNet50 is an image classification model. While it is excellent on its own, it is often used in creating custom models due to its flexibility in transfer learning and fine-tuning.

## What is fine-tuning?
You can find it in the Internet. Well..

If you want to understand the fine-tuning, i think you have to know the concept of the transfer learning first.

Fine-tuning is process that making any model to recognize or process the user-defined dataset. See the kaggle notebook in the How To Run section to know how it works.

## Requirements
* PyQt5 >= 5.14
* torch
* torchvision
* numpy

## How to Run
1. Get the fine-tuned model from this <a href="https://www.kaggle.com/code/yoonjunggyu/pytorch-fine-tuning-resnet50/notebook">kaggle notebook</a>.
2. git clone ~
3. Put the model file (result.pth) into the root folder of this repo.
4. pip install -r requirements.txt
5. python main.py
6. Type the image url of anteater or hyena.
7. Press "Run" 

## Preview
![image](https://github.com/yjg30737/pyqt-using-finetuned-resnet50-example/assets/55078043/1884cb11-5f1e-4140-92d3-6e9f25790c50)

The result was hyena with a probability of 99.96% :)
