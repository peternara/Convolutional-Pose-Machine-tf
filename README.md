#   Convolutional Pose Machine implemented with tensorflow

This model is still work in progress.

Trainable with MPI dataset.

Details are in [my blog](https://blog.csdn.net/mpsk07/article/details/79522809) in Chinese.

![image](https://user-images.githubusercontent.com/6295576/44653246-2bcc7200-aa29-11e8-962d-da37f2d74c4b.png)



![CPM](https://raw.githubusercontent.com/mpskex/Convolutional-Pose-Machine-tf/master/demo/arch.png)

#   Model: Convolutional Pose Machine
Please go to my [site](http://mpskex.wicp.net/models) to choose the Convolutional Pose Machine model
And put the model in `model/` directory

#   Demo & Benchmark Results
![Demo](https://raw.githubusercontent.com/mpskex/Convolutional-Pose-Machine-tf/master/demo/demo.jpg)

![PCKh Benchmark Result](https://raw.githubusercontent.com/mpskex/Convolutional-Pose-Machine-tf/master/demo/PCKh.png)

##  Live demo avaliable (2018-Jul)
*   Live Camera Demo 
*   Offline Video Processing Demo

![Live Demo](https://raw.githubusercontent.com/mpskex/Convolutional-Pose-Machine-tf/master/demo/live.gif)

#   TODOs
*   Still working in benchmark (Not in this project's workflow)


#   Files
Filename|Usage
:-------|:----
predict.py|change the source file's image
train.py|use this to launch a training process
benchmark.py|live demo to test the model
valPCK.py|PCK metric validation 
CPM.py|NO USAGE PLEASE LEAVE INTACT
datagen.py|NO USAGE PLEASE LEAVE INTACT

##  Credit
### Cited [Convolutional Pose Machine](https://arxiv.org/abs/1602.00134)
    @inproceedings{wei2016cpm,
        author = {Shih-En Wei and Varun Ramakrishna and Takeo Kanade and Yaser Sheikh},
        booktitle = {CVPR},
        title = {Convolutional pose machines},
        year = {2016}
    }

    Thanks to wbenbihi@github for his batch generator~

    Author: Liu Fangrui aka mpsk
        Beijing University of Technology
            College of Computer Science & Technology
