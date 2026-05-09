You are given an m x n integer matrix grid​​​, where m and n are both even integers, and an integer k.
The matrix is composed of several layers, which is shown in the below image, where each color is its own layer:
<img src="https://assets.leetcode.com/uploads/2021/06/10/ringofgrid.png"/>
A cyclic rotation of the matrix is done by cyclically rotating each layer in the matrix. To cyclically rotate a layer once, each element in the layer will take the place of the adjacent element in the counter-clockwise direction. An example rotation is shown below:
<img src="https://assets.leetcode.com/uploads/2021/06/22/explanation_grid.jpg"/>
Return the matrix after applying k cyclic rotations to it.
