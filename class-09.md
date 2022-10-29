---
layout: page
title: "Class 09"
permalink: /reading-notes/class-09/
---

## Dunder Methods

According to <https://dbader.org/blog/python-dunder-methods>, dunder methods, also called special methods or magic methods, are used to enhance the behavior of custom-built Python classes and make them behave more similarly to built-in Python types. Some examples of this idea of enhancement are:

- `__str__` or `__repr__` is used to print string representation of custom classes like how one can print string representations of lists and dictionaries
- `__len__` can be used to get the length of some property of a custom class like how one can get the length of a list or a string
- `__getitem__` can be used to provide access to a property of a custom class at a specific index or position like how one can get the value at a specific index of a list or the value at a specific key in a dictionary
- `__eq__` or `__lt__` can be used to provide comparison logic that mirrors mathematical comparison of numbers

## Probability

According to <https://www.dataquest.io/blog/basic-statistics-in-python-probability/>, probability refers to the likelihood of an event happening. In order to accurately measure the probability of something, such as getting heads or tails in a coin flip, we need to repeat the act of flipping the coins over many iterations where each iteration itself has its own series of iteration. The latter series of iteration is called the data and the former series of iteration is called the data set. By gathering many data sets, we can take the average of the data sets to come up with the probability of something. The more data sets we use in our calculations, the closer to an average probability we get.

According to <https://www.dataquest.io/blog/basic-statistics-in-python-probability/>, the data sets can also be graphed. The graph represents something called the normal distribution. The normal distribution roughly states that 68% of your data will be very close to the average probability, 95% will be somewhat close to the average probability and 99.7% will be a little further away from the average probability.

## Bookmarks and Review

<https://docs.python.org/3/library/statistics.html>

## Things I want to know more about

- How probability and statistics work
