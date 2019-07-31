
# Getting Started with NumPy

## Introduction

NumPy is one of the main libraries for performing scientific computing in Python. Using NumPy, you can create high-performance multi-dimensional arrays, and several tools to work with these arrays. 

A NumPy array can store a grid of values. All the values must be of the same type. NumPy arrays are n-dimensional, and the number of dimensions is denoted the *rank* of the NumPy array. The shape of an array is a tuple of integers which hold the size of the array along each of the dimensions.

For more information on NumPy, we refer to http://www.numpy.org/.


## Objectives

You will be able to:

* Understand how to initialize NumPy arrays from nested Python lists and access elements using square brackets
* Understand the shape attribute on NumPy arrays
* Understand how to create arrays from scratch including np.zeros, np.ones, np.full
* Learn to perform scalar and vector math  

## NumPy array creation and basic operations

First, remember how the naming for NumPy is to import it as `np`.

One easy way to create a numpy array is from a python list. The two are similar in a number of manners but NumPy is optimized in a number of ways for performing mathematical operations, including having a number of built in methods that will be extraordinarily useful.

## Broadcasting Mathematical Operations

Notice right off the bat how basic mathematical operations will be applied element wise in a NumPy array versus a literal interpretation with a python list:

## Even more math!

### Scalar Math

* np.add(arr,1) | Add 1 to each array element
* np.subtract(arr,2) | Subtract 2 from each array element
* np.multiply(arr,3) | Multiply each array element by 3
* np.divide(arr,4) | Divide each array element by 4 (returns np.nan for division by zero)
* np.power(arr,5) | Raise each array element to the 5th power  
  
### Vector Math

* np.add(arr1,arr2) | Elementwise add arr2 to arr1
* np.subtract(arr1,arr2) | Elementwise subtract arr2 from arr1
* np.multiply(arr1,arr2) | Elementwise multiply arr1 by arr2
* np.divide(arr1,arr2) | Elementwise divide arr1 by arr2
* np.power(arr1,arr2) | Elementwise raise arr1 raised to the power of arr2
* np.array_equal(arr1,arr2) | Returns True if the arrays have the same elements and shape
* np.sqrt(arr) | Square root of each element in the array
* np.sin(arr) | Sine of each element in the array
* np.log(arr) | Natural log of each element in the array
* np.abs(arr) | Absolute value of each element in the array
* np.ceil(arr) | Rounds up to the nearest int
* np.floor(arr) | Rounds down to the nearest int
* np.round(arr) | Rounds to the nearest int

### Here's a few more examples from the list above

## Multidimensional Arrays
NumPy arrays are also very useful for storing multidimensional data such as matrices. Notice how NumPy tries to nicely align the elements.

## The Shape Attribute
One of the most important attributes to understand with this is the shape of a NumPy array.

### We can also have higher dimensional data such as working with 3 dimensional data
<img src="images/Image_195_3D array.png" width=500>

## Built-in Methods for Creating Arrays
NumPy also has several built in methods for creating arrays that are useful in practice. In particular these methods are particularly useful:
* `np.zeros(shape)` 
* `np.ones(shape)`
* `np.full(shape, fill)`

### Similarly the `np.ones()` method returns an array of ones

### The `np.full()` method allows you to create an array of arbitrary values

## Numpy array subsetting

You can subset NumPy arrays very similar to list slicing in python.

### This becomes particularly useful in multidimensional arrays when we can slice on multiple dimensions

### Notice that you can't slice in multiple dimensions naturally with built in lists

### 3D Slicing

## Summary

Great! You learned about a bunch of NumPy commands. Now, let's move over to the lab to put your new skills into practice!
