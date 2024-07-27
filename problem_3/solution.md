# Solution to problem 3

Firstly, I'd ask what version of python she's using as it looks like she might be using python 2. If that was the case, I'd suggest she ports the code to python 3 (assuming this small script is not part of a larger application.)

Secondly, since the code is not very readable and doesn't contain any tests that would verify it is behaving as intended, I would steer her towards some resources she could use to help her refactor her code.

For example, these resources offer guiding principles and examples that could help someone new to python improve the readability of their code:

+ B Kirankumar (2023) [How to Writing Readable and Maintainable Python Code?](https://medium.com/@b.kiran1999kumar/a-guide-to-writing-readable-and-maintainable-python-code-28bb5dbb91ce) Medium.
+ [The Hitchhiker's Guide to Python: Code Style](https://docs.python-guide.org/writing/style/). An open source community project.

She may find that refactoring her code helps her identify the problems and leads to improved performance.

If not, then once the code is in a more readable and pythonic state, she could then consider whether taking further steps to improve its performance would be worth the additional time and effort.

Depending what IDE she is using, she might find there are profiling extensions she could explore.

Resources she might find helpful as an introduction to profiling:

+ Bartosz Zaczyński (2024) [Profiling in Python: How to Find Performance Bottlenecks](https://realpython.com/python-profiling/). RealPython.
+ Corentin Berteaux (2023) [How to use time profiling in Python to make your code faster](https://data-ai.theodo.com/blog-technique/python-profiling)