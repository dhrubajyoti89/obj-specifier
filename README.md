<h1 align="center">Object Specifier</h1>

##  Dataset
The dataset used can be downloaded here - [Click to Download](https://www.kaggle.com/valentynsichkar/yolo-coco-data)

This is ready to use data with weights and configuration along with coco names to detect objects with YOLO algorithm.

##  Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> [See here]()

##  Installation
1. Clone the repo
```
$ git clone https://github.com/dhrubajyoti89/obj-specifier.git
```

2. Change your directory to the cloned repo and create a Python virtual environment named 'test'
```
$ mkvirtualenv test
```

3. Now, run the following command in your Terminal/Command Prompt to install the libraries required
```
$ pip3 install -r requirements.txt
```

##  Working

1. Open terminal. Go into the cloned project directory folder and type the following command:
```
$ python3 yolo.py --dataset dataset
```

2. To detect objects in an image type the following command: 
```
$ python3 yolo.py -i "images/1.jpg" -y "yolo-coco"
```

##  Results

#### Our model gave 81% accuracy for Object Detection after training 

## Project Demo

[Dev Link](https://dev.to/dhrubajyoti89/object-specifier-yolo-coco-107b)

![](https://github.com/dhrubajyoti89/obj-specifier/blob/master/Readme_images/ss.png)

Feel free to mail me for any doubts/query 
:email: dhruba.chakraborty2019@gift.edu.in

## Contribution
Feel free to **file a new issue** with a respective title and description on the the Object Specifier(https://github.com/dhrubajyoti89/obj-specifier/issues) repository. If you already found a solution to your problem, **I would love to review your pull request**! 

## Owner
[Dhrubajyoti Chakraborty](https://github.com/dhrubajyoti89)

## Credits
* [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)
* [https://www.kaggle.com](https://www.kaggle.com)

## License
MIT © [Dhrubajyoti Chakraborty](https://github.com/dhrubajyoti89/obj-specifier/blob/master/LICENSE)
