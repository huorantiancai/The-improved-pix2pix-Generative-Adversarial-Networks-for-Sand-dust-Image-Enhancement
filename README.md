# The-improved-pix2pix-Generative-Adversarial-Networks-for-Sand-dust-Image-Enhancement






Training command ：python3 train.py --dataroot ./xx/ --name sc_pix2pix --model pix2pix --direction BtoA

The training data set actually used in this paper is in src\xx\train

Testing command : python3 test.py --dataroot ./xx/ --name sc_pix2pix --model pix2pix --direction BtoA

The testing data set actually used in this paper is in src\xx\test

If you don’t want to spend time training, we also provide trained weights for testing. The link is as follows

weights Link：https://pan.baidu.com/s/1-rSZemEAlsbaYBcVkuKQCw 
key：a1o8

Please unzip the downloaded weights to src\checkpoints\sc_pix2pix.

The result will be saved in src\results\sc_pix2pix\test_latest\images, and you can also observe the training process by installing the visdom plugin.
