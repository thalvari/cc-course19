# Group Picasso
### Usage
* Download the 
[pre-trained model](https://storage.googleapis.com/download.magenta.tensorflow.org/models/arbitrary_style_transfer.tar.gz)
and extract the file(s) to this folder
* Run only this project and only once with ```python main.py -c group_picasso/test_config.json -p 1```

### Examples
Original content, style, markovified styles and generated artifacts:

![](images/content/golden_gate_sq.jpg)
![](images/example_styles/towers_1916_sq.jpg)
![](gifs/m1.gif)
![](gifs/a1.gif)

![](images/content/colva_beach_sq.jpg)
![](images/example_styles/clouds-over-bor-1940_sq.jpg)
![](gifs/m2.gif)
![](gifs/a2.gif)

![](images/content/statue_of_liberty_sq.jpg)
![](images/example_styles/zigzag_colorful.jpg)
![](gifs/m3.gif)
![](gifs/a3.gif)

![](images/content/eiffel_tower.jpg)
![](images/example_styles/red_texture_sq.jpg)
![](gifs/m4.gif)
![](gifs/a4.gif)

### Library references
* [Fast Style Transfer for Arbitrary Styles](https://github.com/tensorflow/magenta/tree/master/magenta/models/arbitrary_image_stylization)
