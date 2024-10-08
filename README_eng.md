# from numpy import Neural Network

## How to submit your homework
- Create a private repository
  - Use this repository as a template, follow [these instructions](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template)
  - Add the course team [zelcookie](https://github.com/zelcookie) & [ksenia-klokova](https://github.com/ksenia-klokova) to the repository
    - [Instructions on how to add](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-personal-account-on-github/managing-access-to-your-personal-repositories/inviting-collaborators-to-a-personal-repository)
- Install dependencies with ```pip install -r requirements.txt```
- Complete the assignment
- Send the repository link to the teachers @zelcookie, @ksenia_klokova

## Task description
There are two versions of this homework: easy and hard.
In both versions, you need to implement a neural network in numpy.
The easy version differs from the hard one in that you need to do it directly in the training loop and with two layers. 
I.e. you need to describe `forward`, `backward` and the optimization step directly in the loop.
In the hard version, you need to do approximately the same thing, but in classes. 
The hard version is needed for developing a better understanding, however, it is more difficult due to the use of classes and, perhaps, yet unfamiliar form of this usage.
The abstractions in this homework are very useful for understanding what will be happening in Torch. 
This homework will give you a much deeper understanding, but it will also be more difficult to complete. 
You need to describe several layers: `Linear`, `ReLU`, `BCELoss`. The implementation of `Sigmoid` is already in `our_library.layers`. 
By implementing the layers above, you will be able to make an n-layer neural network with any number of layers. This is achieved by describing all the necessary logic:
- How to process input data and pass it on;
- Accept the gradient from the next layer, make `backward` for the current layer and pass the gradient to the previous layer;
- How to update weights if there are trainable weights in the layers.

Even if you don't fully complete the hard version of the homework, you can still send it to us (in order to not let it go to waste). 
I or the assistants will look and then we will discuss how to finish it.
Believe me, this homework is worth doing! You will get more experience by doing the hard one, albeit there is nothing wrong if you choose the easy one.
You will still have many opportunities to prove yourself as the course goes on.

The easy homework is in the notebook `Homework_Easy_(eng).ipynb`, the hard one is in `Homework_Hard_(eng).ipynb`

## Installing dependencies
Required third-party libraries

`pip install -r requirements.txt`

## Grading
We check the correctness of the learning logic, and you will be given comments on what needs to be corrected if the homework is submitted on time.
The literacy and style of the code will not be checked, but reading beautiful code is always lovely.
Maximum score: 10 (if you only submit the easy part, the maximum is 6 points).

## Deadline
15/10/2024
After that the maximum score for the hard version is 7

## Important requests from us
- Please don't send links to `colab`, send a link to your repository
- Before submitting the task, clean your code by removing unused code blocks and unimportant comments

## Additional materials
- [Andrej Karpathy's lecture](https://www.youtube.com/watch?v=VMj-3S1tku0)
- [Quite an old video of mine that might help you](https://www.youtube.com/watch?v=tZ0yCzWfbZc)
- [A very good tutorial](https://towardsdatascience.com/nothing-but-numpy-understanding-creating-binary-classification-neural-networks-with-e746423c8d5c)
