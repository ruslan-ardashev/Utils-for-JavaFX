Utils for JavaFX
==========
A series of JavaFX utilities to facilitate development.


### Tester
* [Java File](https://github.com/ruslan120101/Utils-for-JavaFX/blob/master/Tester/Tester.java)
* Creates a Scene in JavaFX for easy, visual testing.


### SilentFailArrayList
* [Java File](https://github.com/ruslan120101/Utils-for-JavaFX/blob/master/SilentFailArrayList/SilentFailArrayList.java)
* An ArrayList that doesn't crash when an index that's out of bounds is referenced.


### ImageToInt2DArray
* [Java File](https://github.com/ruslan120101/Utils-for-JavaFX/blob/master/ImageToInt2DArray/ImageToInt2DArray.java)
* Specify your "resolution" (i.e. dimensions of array)
* Converts a JavaFX **Image** object to a 2D array of integers
  * **Bits 31 --> 24** opacity
  * **Bits 23 --> 16** r
  * **Bits 15 --> 8** g
  * **Bits 7 --> 0** b


### IntArray2DToImageConverter
* [Java File](https://github.com/ruslan120101/Utils-JavaFX/tree/master/IntArray2DToImageConverter)
* Converts a two-dimensional integer array to a JavaFX **Image**
* Intended to work in conjunction with the util above
