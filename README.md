# NETMEM
using neural networks to compress images to a smaller size with minimal loss

in short:

this works by leveraging the fact that neural networks memorize data with "activation patterns", instead of memorising exactly what each pixel looks like.

how to use:

1: download the .ipynb file.

2: prapare the images you want to memorize in a directory.

3: replace the settings at the beginning to whatever you want. (note: this doesnt have to be the actual parameters of the images, they will be resized)

4: replace my directory with the images with the directory you want to memorize when loading the data.

5: train the network. (expiriment with your own parameters, such as: learning rate, pruning amount, image resolution, etc...)

6: prune the network. (i found that a pruning rate of around 0.1 - 0.15 is good without any denoiser)

7: test the network.

where can i find additional information:

i will add a proper scientific paper in some time.
