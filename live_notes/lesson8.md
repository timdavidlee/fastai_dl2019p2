## Lesson 8 Markdown Notes

![](https://snag.gy/HiJUsO.jpg)

Welcome to the course, for those of you who come every year, its a very different course.

![](https://snag.gy/B1gdqJ.jpg)


### What we will do

- Implement fastai library from foundations (from scratch). 
- Read and implement papers
- Implementing much of pytorch
- Going deeper into applications that are not fully-baked in yet
    - seq2seq
    - attention
    - Transformer

- Use JIT / CUDA
- Last 2 lessons, implementing some lessons in Swift
- Part 1 was more practical, learn a technique and use it
- So whats this classes approach? We will teach you the tools to implement papers, experiment with them, and try them out for yourselves
- We used to call part 2 cutting edge, but now the cutting edge is now the engineering part of deep learning. The most effective people are the ones who can successfully build and deploy models

![](https://snag.gy/7ZKEb4.jpg)

- Part 1 was topdown, saw how deep learning is used in practice, and how to use it, and how to get results
- Part 2 will be bottom up: lets you see the connections between the various things. then you can customize your algo for your own problem, doing the things you need it to do.

![](https://snag.gy/JOS1eB.jpg)

- Chris Lattner: build LLVM, built the default compiler C++ clang. And he built Swift, and is now focusing on deep learning
- None of the previous languages were designed for the multi-processor operations, designed by a compiler specialists
- Another option is **Julia** for numerical programming, which is farther along; So now there are two choices.
- (Jeremy) played around with the swift library over the xmas break. 

![](https://snag.gy/gNJOx1.jpg)

S4TF = swift for tensoflow

![](https://snag.gy/kya1A0.jpg)


## Implement Fastai and Pytorch functionality 
![](https://snag.gy/s8EnWD.jpg)


#### Rules

- We are allowed to use pure python
- Standard python library
- Non-data sci modules
- pytorch - only for arrays and rng
- fastai.datasets (for source materials)
- matplotlib
- Once we recreate a function we can use the real version downstream

##### Intention

![](https://snag.gy/JN5AUZ.jpg)

![](https://snag.gy/wliTZO.jpg)

##### From part 1

![](https://snag.gy/yrN4nc.jpg)

For topics that you don't master, go back to the previous lesson.

##### Train really good models.
![](https://snag.gy/pq30xn.jpg)


1. overfit (make sure you have too much predictive power)
2. Reduce the overfitting
3. [there is no step 3] Understand the model

##### How to reduce overfitting
![](https://snag.gy/6MbfDr.jpg)

- This should be the order in while you deal and reduce overfitting
- Many beginner students go in reverse and try to limit architecture complexity, which should be the last thing to be done

##### Read papers

![](https://snag.gy/EuJkUF.jpg)

Papers can be very intimidating to read. The simplest of calculations on excel can be a large jumble of symbols in a paper.

**Tip 1**: learn to pronounce the greek letters, makes equations more approachable.


![](https://snag.gy/6QOl9K.jpg)

**Tip 2**: Learn the math symbols - check wikipedia. Detexify - uses machine learning to determine what symbols you are looking at. The nice thing about this is it gives the latex.

## Course Overview

![](https://snag.gy/0QSVoH.jpg)

For the next few lessons. We will be making a competant CNN model.