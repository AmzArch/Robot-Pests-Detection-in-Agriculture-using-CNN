# Robot-Pests-Detection-in-Agriculture-using-CNN
This repo uses robots with cameras in agriculture to detect pests on crops, utilizing a neural network trained on a dataset of 1,665 pest images.


Robotics is a rapidly growing field and is gaining traction in the agricultural field as well, where robots are used everywhere such as in automatic seeding, weed control, automatic fruit picking, automatic sprayers, harvesting, etc. I aim to use the robots that are already deployed in the field and use the inputs from existing cameras on them to identify pests on crops and send a notification to the farmers/owners so that the crops can be protected or pesticide spraying bots be deployed automatically. Towards this I have used a dataset containing images of Fruit Piercing Moth (373 Images), Gall Flies (489 Images), Locust (330 Images) and Stem Borer (473 Images) with a total of 1,665 images. The inputs here will be the pics taken by cameras on robots (for testing purposes will input a picture from google images) and the output will be the pest detected if any from the 4 categories - Fruit Piercing Moth, Gall Flies, Locust and Stem Borer. The Neural Network for the project is trained using Google Colab GPU’s to save on time.

Dataset picked up from: https://www.kaggle.com/datasets/abhinandanroul/pest-normalized

<img width="317" alt="Pest Identification" src="https://user-images.githubusercontent.com/78802695/231619963-3d5ac839-6cc8-4b1c-960b-a6d2e0935f92.png">
