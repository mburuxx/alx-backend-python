# 0x02. Python - Async Comprehension

## Description
Repository for the project "0x02. Python - Async Comprehension" which focuses on asynchronous programming in Python, specifically using async generators and comprehensions.

This project was part of the curriculum at ALX - Software Engineering. It was completed over a 24-hour period from May 7, 2024, 6:00 AM to May 8, 2024, 6:00 AM. An automatic review was conducted upon project submission.

## Resources
- [PEP 530 – Asynchronous Comprehensions](https://www.python.org/dev/peps/pep-0530/)
- [What’s New in Python: Asynchronous Comprehensions / Generators](https://docs.python.org/3/whatsnew/3.6.html#asynchronous-generators)
- [Type-hints for generators](https://docs.python.org/3/library/typing.html#typing.Generator)

## Learning Objectives
By the end of this project, participants were expected to be able to explain the following concepts without external assistance:
- How to write an asynchronous generator
- How to use async comprehensions
- How to type-annotate generators

## Requirements
### General
- Allowed editors: vi, vim, emacs
- All files interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/env python3`
- Code should follow PEP 8 style (version 2.5.x)
- Length of files tested using `wc`
- All modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All functions should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'`)
- Documentation should be descriptive sentences explaining the purpose of modules, classes, or methods
- Functions and coroutines must be type-annotated

## Tasks
1. **Async Generator**
   - Write a coroutine `async_generator` that yields 10 random numbers asynchronously.

2. **Async Comprehensions**
   - Implement a coroutine `async_comprehension` that collects 10 random numbers using async comprehensions.

3. **Run time for four parallel comprehensions**
   - Write a coroutine `measure_runtime` that measures the total runtime of executing `async_comprehension` four times in parallel using `asyncio.gather`.

## Files
- [0-async_generator.py](./0-async_generator.py)
- [1-async_comprehension.py](./1-async_comprehension.py)
- [2-measure_runtime.py](./2-measure_runtime.py)

## Repository
- GitHub repository: [alx-backend-python](https://github.com/mburuxx/alx-backend-python)
- Directory: 0x02-python_async_comprehension
