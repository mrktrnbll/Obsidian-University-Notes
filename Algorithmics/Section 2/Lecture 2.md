---
tags:
  - Lecture
  - Algs
---
Lecture 2 | 05/10/23
:-- | --:

---
## Text Compression
* Special case of data compression
* Must be lossless **you need to read it after** - **some other formats like video or audio can sacrifice this requirement for speed**
	How to
	 -> You need an compression algorithm
	 -> An opposite decompression algorithm
### Huffman Encoding
- statistical method
	- fixed ASCII code is replaced with varied length of bit words (code word)
	- high recurring characters are given smaller bit words
	- bit words cannot be a prefix for another
		-> 001, 0101 y
		-> 001, 0010 n
	- representing with a huffman tree is good to show character "weight" or "distance from root"
	- creating tree is done using these characteristics
		- weight is just known as the frequency of a character.
		- distance from the root is decided upon by the weight and describes the syntax of a bit word.
### LZW compression
* similar to the Huffman method 