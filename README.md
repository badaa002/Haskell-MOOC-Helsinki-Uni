# Haskell Assignments

## Overview

This repository contains my solutions for the assignments from the [Haskell MOOC](https://haskell.mooc.fi), an online course on Functional Programming offered by the University of Helsinki. The course explores functional programming concepts using the Haskell programming language. 

## Course Material

The course material is openly available and can be accessed through the [course page](https://haskell.mooc.fi). In case the course page is down, you can find the material in this repository ([part1.html](part1.html), [part2.html](part2.html)).

## Exercises

The exercises are organized in the `exercises/` directory. Each exercise file is named sequentially as `Set1.hs`, `Set2.hs`, etc. To complete an exercise, edit the corresponding file according to the instructions provided within the file.

### Setting Up

Ensure you have all the required dependencies by running:

```
stack build
```

### Testing Solutions

You can test your solutions using the provided test files. Run the following command in the `exercises/` directory:

```
stack runhaskell SetXTest.hs
```

Replace `X` with the number of the exercise set you are working on.

For more information on working with exercises, refer to the course material [here](part1.html#working-on-the-exercises).

## Troubleshooting

### Common Issues and Fixes

- **Error: `While building package zlib-0.6.2.3`**
  - Install the zlib library headers. On Ubuntu, use:
    ```
    sudo apt install zlib1g-dev
    ```

- **Error: `Downloading lts-18.18 build plan ... RedownloadInvalidResponse`**
  - This occurs if your version of Stack is outdated. Upgrade it with:
    ```
    stack upgrade
    ```

## Notes

This repository is for personal use and learning. Feel free to explore the solutions, but ensure you adhere to the course's academic honesty policies if you're also participating in the Haskell MOOC.

## Acknowledgments

This course is licensed under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/). All credits for the course content and exercises go to the University of Helsinki and the Haskell MOOC team.
