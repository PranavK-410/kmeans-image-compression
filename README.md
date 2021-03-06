# Image Lossy Compression based on K-Means color clustering
Image compression framework based on color-clustering.

## Usage
See `demo/test.py`:

`import kmeans.kmeans_compression as kmeans`

`kmeans.compress(<path to the image>, <number of colors of the compressed output>)`

## Results:
### Original image:
<img src="https://github.com/dshahrokhian/kmeans-lossy-compression/blob/master/tests/futur.png" width="600" hspace="46">

### Compressed image:

**Note:** The approximate file size is measured without taking into account the overhead of the (colors,size) annotation.

<img src="https://github.com/dshahrokhian/kmeans-lossy-compression/blob/master/tests/16colors.png">
<img src="https://github.com/dshahrokhian/kmeans-lossy-compression/blob/master/tests/5colors.png">
<img src="https://github.com/dshahrokhian/kmeans-lossy-compression/blob/master/tests/2colors.png">
