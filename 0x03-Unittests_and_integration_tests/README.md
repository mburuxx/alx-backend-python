# 0x03. Unittests and Integration Tests

## Description
Repository for the project "0x03. Unittests and Integration Tests" focused on unit testing and integration testing in Python using the `unittest` framework. This project was completed as part of the ALX - Software Engineering curriculum. It spanned from May 23, 2024, 6:00 AM to May 28, 2024, 6:00 AM, with an automatic review conducted upon submission.

## Resources
- [unittest — Unit testing framework](https://docs.python.org/3/library/unittest.html)
- [unittest.mock — mock object library](https://docs.python.org/3/library/unittest.mock.html)
- [How to mock a readonly property with mock?](https://stackoverflow.com/questions/18001233/how-to-mock-a-readonly-property-with-mock)
- [parameterized](https://pypi.org/project/parameterized/)
- [Memoization](https://en.wikipedia.org/wiki/Memoization)

## Learning Objectives
By the end of this project, participants were expected to be able to explain the following concepts without external assistance:
- The difference between unit and integration tests
- Common testing patterns such as mocking, parametrizations, and fixtures

## Requirements
### General
- All files interpreted/compiled on Ubuntu 18.04 LTS using python3 (version 3.7)
- All files should end with a new line
- The first line of all files should be exactly `#!/usr/bin/env python3`
- Code should follow PEP 8 style (version 2.5)
- All files must be executable
- All modules should have documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
- All classes should have documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
- All functions (inside and outside a class) should have documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
- Documentation should be descriptive sentences explaining the purpose of modules, classes, or methods

## Tasks
1. **Parameterize a unit test**
   - Implement unit tests using `unittest.TestCase` to test functions with different inputs using `@parameterized.expand`.

2. **Mock HTTP calls**
   - Use `unittest.mock.patch` to mock HTTP requests in unit tests, ensuring external calls are not made.

3. **Parameterize and patch**
   - Utilize `@parameterized.expand` and `unittest.mock.patch` to test memoization decorators and ensure correct function behavior.

4. **Parameterize and patch as decorators**
   - Use `@patch` as decorators to mock external dependencies and test class methods that interact with them.

5. **Mocking a property**
   - Implement unit tests to mock properties using `unittest.mock.patch` and verify expected behavior of mocked properties.

6. **More patching**
   - Test class methods with multiple patched dependencies using `@patch` decorators and `unittest.mock.patch` context managers.

7. **Parameterize**
   - Parameterize unit tests using `@parameterized.expand` to test different inputs and expected outputs.

8. **Integration test: fixtures**
   - Implement integration tests using fixtures and mock external requests using `unittest.mock.patch`.

## Files
- [test_utils.py](./test_utils.py): Contains unit tests for various utility functions.
- [test_client.py](./test_client.py): Includes integration tests for client functionalities.
- [fixtures.py](./fixtures.py): Provides predefined fixtures for integration tests.

## Repository
- GitHub repository: [alx-backend-python](https://github.com/mburuxx/alx-backend-python)
- Directory: 0x03-Unittests_and_integration_tests
