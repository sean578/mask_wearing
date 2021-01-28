# Mask wearing

## Resources

* [MaskedFace-Net paper](./maskedface_net.pdf)
* [MaskedFace-Net github](https://github.com/cabani/MaskedFace-Net)
* [Application to create masked faces](https://github.com/aqeelanwar/MaskTheFace) - has different types of mask
* [Mobile application proposal by maskedface-net creators](./maskedface_net_mobile_application.pdf)

## Plan - brainstorm

* Classification categories
  * Correct mask, incorrect mask
  * Uncovered chin, uncovered noise, uncovered nose & mouth
* Build up a new data-set with more variety of masks.
* Application where user can load photo & will provide category.
* Application where user can user webcam - provide category in real time.
* Classification - Learn PyTorch.
  * Training set, validation set, test set.
  * Cross validation
  * Normalising input images
  * Use a pre-trained face recognition model. - what does pytorch have
* CI using github actions.

## TODO

* Look at gitlab actions for CI
* Available pre-trained models for pytorch - face recognition

