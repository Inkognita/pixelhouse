# pixelhouse

[![PyVersion](https://img.shields.io/pypi/pyversions/pixelhouse.svg)](https://img.shields.io/pypi/pyversions/pixelhouse.svg)
[![PyPI](https://img.shields.io/pypi/v/pixelhouse.svg)](https://pypi.python.org/pypi/pixelhouse)

A minimalist drawing library for making beautiful animations in python.
Anything that can be drawn can be moved.
_Very much a work in progress!_

      pip install pixelhouse

## Examples (click for source)

[![Example image: blue woods](examples/blue_woods.png)](examples/blue_woods.py)

[![Example image: Logo](examples/logo_pixelhouse.png)](examples/logo_pixelhouse.py)
[![Example image: Circle Lines](examples/circle_lines.png)](examples/circle_lines.py)

[![](examples/simple_circles.png)](examples/small_demos.py)
[![](examples/teyleen_982.png)](examples/small_demos.py)
[![](examples/teyleen_116.png)](examples/small_demos.py)
[![](examples/moving_circles.gif)](examples/small_demos.py)
[![](examples/checkerboard.gif)](examples/small_demos.py)
[![](examples/pacman.gif)](examples/small_demos.py)
[![](examples/timer.gif)](examples/small_demos.py)

## Wishlist / Roadmap

#### Primitives 
+ [x] Line
+ [x] Circle
+ [x] Ellipse
+ [x] Polyline
+ [x] Backgrounds
+ [ ] Text

#### Transforms
+ [x] Rotation
+ [x] Translation
+ [x] Scale
+ [x] Elastic distortion
+ [x] Generic elastic deformations

#### Gradients
+ [x] Linear gradients with transparent elements

#### Layers
+ [x] Additive
+ [x] Subtractive
+ [x] Overlay
+ [x] Direct (for primitives)

#### Filters
+ [x] Blur
+ [x] Instagram-style filters (keras not needed)
+ [ ] Histogram normalization

#### Easing
+ [x] Named easing, Pennser equations
+ [x] Generic beizer easing

#### Color/Palettes
+ [x] Named colors
+ [x] Top palettes
+ [ ] Random palettes

#### File IO
+ [x] Save to gif
+ [x] Save to mp4 
+ [ ] Load from gif
+ [ ] Load from mp4

#### Devops
+ [x] Unified class for artists
+ [x] Proper library
+ [ ] setup.py
+ [ ] pip install
+ [ ] Context mangager for canvas and animation
+ [ ] Unit tests
+ [ ] Doc coverage
+ [ ] Subpixel resolution
+ [x] Hide cv2 weird colorspace, BGR -> RGB


## Credits

+ [Travis Hoppe](https://twitter.com/metasemantic?lang=en)

## Projects used 

+ [`opencv`](https://opencv.org/)
+ [Easing functions](https://github.com/semitable/easing-functions)
+ [Bezier curves](https://github.com/reptillicus/Bezier)
