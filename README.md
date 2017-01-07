# unet-color
Deep colorizer based on unet architecture (Encoder decoder with skip connections) without a GAN. 
Trained with flickr-8k dataset for 50 epochs and 10k samples from Celeb dataset for 2 epochs. 

Usage
=====

python colorizer_gan.py --data_path path_to_flickr_8k_data --model_path path_to_save_the_model

<img src="https://raw.githubusercontent.com/4g/unet-color/master/images/grayscale_3.png" height="384"><img src="https://raw.githubusercontent.com/4g/unet-color/master/images/colored_3.png" height="384"> 

<img src="https://raw.githubusercontent.com/4g/unet-color/master/images/grayscale_4.png" height="384"> <img src="https://raw.githubusercontent.com/4g/unet-color/master/images/colored_4.png" height="384"> 

<img src="https://raw.githubusercontent.com/4g/unet-color/master/images/grayscale_2.png" height="384"><img src="https://raw.githubusercontent.com/4g/unet-color/master/images/colored_2.png" height="384"> 


1] http://lmb.informatik.uni-freiburg.de/people/ronneber/u-net/
2] https://github.com/phillipi/pix2pix
