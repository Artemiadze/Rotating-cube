# Rotating cube

## The mathematical algorithm of the program

This program uses rotation matrices in three-dimensional space. In linear algebra rotation matrix is a transformation matrix that is used to perform a rotation in Euclidean space. For example, using the convention below, the matrix

$\documentclass{article}
    \usepackage{amsmath}
        \begin{document}
            \begin{equation*}
                R = 
                \begin{pmatrix}
                    sin(𝜃) & cos(𝜃)
                \end{pmatrix}
            \end{equation*}
\end{document}$

rotates points in the xy plane counterclockwise through an angle θ about the origin of a two-dimensional Cartesian coordinate system.
If you are interested in a detailed description of the rotation algorithm, then you can read the article on [Wikipedia](https://en.wikipedia.org/wiki/Rotation_matrix).

## Visualization

![GIF](IMG_9598.gif)
## Installation (Linux)
1. Installing the GCC compiler (if you don't have one)

Чтобы обновить список пакетов, используйте следующую команду:

```sudo apt update```
Теперь мы устанавливаем GCC с помощью следующей команды:

```sudo apt install gcc```
Чтобы установить build-essentials, используйте следующую команду:

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

 [Rotation Matrix](https://en.wikipedia.org/wiki/Rotation_matrix)

 [Code](https://www.youtube.com/watch?v=p09i_hoFdd0)