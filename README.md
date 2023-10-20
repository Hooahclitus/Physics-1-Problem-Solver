# Physics-1 Problem Solver

## Overview

The `physics-1-problem-solver` is a comprehensive solution designed to tackle various physics problems spanning topics from vector operations to Newton's laws of motion. This project provides detailed solutions and explanations to physics challenges by employing a range of utilities, vector operations, motion calculations, and force computations. It is based on the Leiningen project structure and derives its physics problems and equations from the textbook [University Physics Volume 1](https://openstax.org/details/books/university-physics-volume-1).

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [License](#license)

## Features

1. **Vector Operations**: Handle basic vector calculations such as:
   - Vector sum, difference, dot product, and cross product.
   - Scaling vectors.
   - Handling vectors of different dimensions.

2. **Motion Calculations**: Address problems related to:
   - Linear motion with constant acceleration.
   - Circular motion, tangential and radial acceleration.
   - Displacement and velocity computations.

3. **Force Computations**: Tackle challenges related to:
   - Newton's laws of motion.
   - Calculating force, tension, and gravitational potential energy.
   - Evaluating the work done and kinetic energy.

4. **Utility Functions**: Convert units, resolve vectors, and compute potential differences.

## Usage

The `physics-1-problem-solver` is a Leiningen project. To use it, simply clone the repository. There are no outside dependencies required and no additional installation instructions provided. After setting up, you can use the functionalities provided by the `physics-1-problem-solver` namespace. Import the necessary modules and leverage the functions to solve specific physics problems. Refer to the provided examples in the `core.clj` file for guidance.

```clojure
(ns your-namespace
  (:require [physics-1.core :as p1]))
```


## License
This project is licensed under the MIT License. Please see the `LICENSE` file for more details.
