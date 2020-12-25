[![Build Status](https://api.travis-ci.com/dassencio/image-dft.svg?branch=master)](https://travis-ci.com/dassencio/image-dft)

# Description

`image-dft` is a script (written in Python 3) which computes and displays the inverse DFTs
of the magnitude and phase components of the DFT of an input image. It implements
the algorithm described [here](https://diego.assencio.com/?index=81059bc883bd6156c2e83f83e2e38c2b).

# License

All code from this project is licensed under the GPLv3. See the
[`LICENSE`](https://github.com/dassencio/image-dft/tree/master/LICENSE)
file for more information.

# Required modules

The following modules are used:

- `matplotlib`
- `numpy`

You can install them with the following command:

    pip3 install matplotlib numpy

# Usage instructions

The script can be executed as in the following example:

    ./image-dft -i image.jpg

To enhance the contrast of the generated images (with histogram equalization),
add `-e` to the command above. Here is an example of the displayed output
(with histogram equalization enabled):

<p align="center">
<img src="https://github.com/dassencio/image-dft/blob/master/.README/example-output.jpg" alt="example output">
</p>

For more details on the parameters which `image-dft` can take, run
`./image-dft -h`.

# Contributors & contact information

Diego Assencio / diego@assencio.com
