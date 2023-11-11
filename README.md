## Neural Style Transfer 
This project have implementation of the original NST paper (:link: [Gatys et al.](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Gatys_Image_Style_Transfer_CVPR_2016_paper.pdf)).


### What is NST algorithm?
The algorithm transfers style from one input image (the style image) onto another input image (the content image) using CNN nets (VGG-19) and gives a composite, stylized image out which keeps the content from the content image but takes the style from the style image.


## Setup
1. Open Anaconda Prompt and navigate into project directory `cd path_to_repo`
2. Run `conda env create` (while in project directory)
3. Run `activate pytorch-nst`

## Usage

1. Copy content images to the default content image directory: `/data/content-images/`
2. Copy style images to the default style image directory: `/data/style-images/`
3. Run `python neural_style_transfer.py --content_img_name <content-img-name> --style_img_name <style-img-name>`

## Acknowledgements

I found these repos useful: (while developing this one)
* [fast_neural_style](https://github.com/pytorch/examples/tree/master/fast_neural_style) (PyTorch, feed-forward method)
* [neural-style-tf](https://github.com/cysmith/neural-style-tf/) (TensorFlow, optimization method)
* [neural-style](https://github.com/anishathalye/neural-style/) (TensorFlow, optimization method)


## some of my output

Path "/data/example/"