# pyqt-using-finetuned-resnet50-example
PyQt example of using fine-tuned resnet50 model for image classficiation of user-defined image (anteater, hyena)

## How to Run
Assuming you already had the pytorch and torchvision.

1. Get the fine-tuned model from this <a href="https://www.kaggle.com/code/yoonjunggyu/pytorch-fine-tuning-resnet50/notebook">kaggle notebook</a>.
2. git clone ~
3. Put the model file (result.pth) into the root folder of this repo.
4. python main.py
5. Type the image url of anteater or hyena.
6. Press "Run" 

## Preview
![image](https://github.com/yjg30737/pyqt-using-finetuned-resnet50-example/assets/55078043/1884cb11-5f1e-4140-92d3-6e9f25790c50)

The result was hyena with a probability of 99.96% :)
