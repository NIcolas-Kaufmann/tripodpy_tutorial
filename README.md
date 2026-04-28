# Installation instructions
Clone the `DustPy` and `Siframe` repos,
- http://github.com/stammler/simframe/

- https://github.com/stammler/dustpy

install them `pip install .` in the appropriate folders.


Clone `tripodpy` https://github.com/tripod-code/tripodpy, then it can be installed via

`pip install .`

or

`pip install --no-build-isolation --editable .`

for editable installation. In the latter case you need to have `meson-python` and `ninja` installed.

`pip install meson-python ninja`


# Contents 

## basic.ipynb 
- minimal setup with and example of how to reconstruct the size distribution
## composition.ipynb
- example of a disk with different evaporating and condesating components
## gap.ipynb
-example with static gas disk with a gap added