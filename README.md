# Neural Style Transfer

This is a Keras implementation of [A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576) by Leon A. Gatys, Alexander S. Ecker and Matthias Bethge.

### Content image - sydney opera house
![images_sydney](images/003sydney.jpg)

### Style image - picasso
![images_picasso](images/style_picasso.jpg)

### Transfer demo
![sydney_picasso_tranfer](docs/demo/slower_transfer.gif)




## Implementation
  basic usage:
  ```
  python styletransfer.py images/003sydney.jpg images/style_picasso.jpg result_sydney_picasso
  ```

  options:
  - content_weight
  - style_weight
  - iter


## Dependencies
- Python 3.x
- Keras
- Tensorflow

## Reference
This implementation uses some code from Francois Chollet's [Neural Style Transfer](https://github.com/fchollet/keras/blob/master/examples/neural_style_transfer.py).

This paper presents an algrithm for generating a mixed image with the content from the content image and the style from another image, using the convolutional neural network(CNN).

