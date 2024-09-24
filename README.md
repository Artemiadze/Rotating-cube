# Rotating cube

## The mathematical algorithm of the program

This program uses rotation matrices in three-dimensional space. In linear algebra rotation matrix is a transformation matrix that is used to perform a rotation in Euclidean space. For example, using the convention below, the matrix

```math
    R = 
    \begin{bsmallmatrix}
    cos(𝜃) & -sin(𝜃)\\
    sin(𝜃) & cos(𝜃)
    \end{bsmallmatrix} 
```

rotates points in the xy plane counterclockwise through an angle θ about the origin of a two-dimensional Cartesian coordinate system. To perform the rotation on a plane point with standard coordinates v = (x, y), it should be written as a column vector, and multiplied by the matrix R:
```math
R\times {\color{black}V} = 
    \begin{bsmallmatrix}
    cos(𝜃) & -sin(𝜃)\\
    sin(𝜃) & cos(𝜃)
    \end{bsmallmatrix}\times
    \begin{bsmallmatrix}
    x\\
    y
    \end{bsmallmatrix} = 
    \begin{bsmallmatrix}
    x\times cos(𝜃) - y\times sin(𝜃)\\
    x\times sin(𝜃) + y\times cos(𝜃)
    \end{bsmallmatrix}
```
If you are interested in a detailed description of the rotation algorithm, then you can read the article on [Wikipedia](https://en.wikipedia.org/wiki/Rotation_matrix).

## Visualization

![GIF](IMG_9598.gif)

## Installation (Linux)
1. Installing the GCC compiler (if you don't have one)

    To update the package list, use the following command:

    ```sudo apt update```

    Now we install GCC using the following command:

    ```sudo apt install gcc```

    To install build-essentials, use the following command:

    ```sudo apt install build-essential```

2. Cloning a repository

```git clone https://github.com/Artemiadze/Rotating-cube.git```

3. Going to the directory "Rotating-cube"

```cd Rotating-cube```

4. Launching the program

```gcc cube.c -o cube -lm```

```./cube```

 5. Stopping the program and clearing the console

    You have to click:

     ```CTRL+C```

    After  enter into the console:

    ```clear```

 ## Resources

 [Rotation Matrix](https://en.wikipedia.org/wiki/Rotation_matrix) - the mathematics involved in the project.

 [Code](https://www.youtube.com/watch?v=p09i_hoFdd0) - The code from video involved in the project.