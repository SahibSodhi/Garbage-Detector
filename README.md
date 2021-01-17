# Garbage Detector
This is an application that uses Deep Learning to detect objects and classifies the method for waste management (recycling, compost, trash, hazardous).

## Motivation
The more we recycle, the less garbage winds up in our landfills and incineration plants. By reusing aluminum, paper, glass, plastics, and other materials, we can save production and energy costs, and reduce the negative impacts that the extraction and processing of virgin materials has on the environment. New products can be made from your recyclable waste material.
It all comes back to you. **Recycling gets down to one person taking action.** 

## Webapp
Built with Flask. Following [this tutorial](https://github.com/avinassh/pytorch-flask-api-heroku/blob/master/README.md).

Run the server:

	FLASK_ENV=development FLASK_APP=app.py python3.5 -m flask run

And upload pictures to try out the garbage detection AI. Example test images are in `test_images`.

## Mobile App
In folder "Sahib"

## Image Recognition
Our image recognition models are based on pre-trained models (DenseNet121 and MobileNet, trained on ImageNet) provided by [Torch](https://pytorch.org/docs/stable/torchvision/models.html) and [Keras](https://keras.io/applications/#mobilenet). We fine-tuned MobileNet to classify garbage material based on the [TrashNet data collection](https://github.com/garythung/trashnet).



