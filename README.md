# ECE444-F2020-Lab6
Lab6
This is a copy of https://github.com/mjhea0/flaskr-tdd
 
Pros:
The unit tests will be written before the code. This means the code will be written in a very modular manner. This means each function executes a very specific task.

This also makes code very documented. Other programmers will be able to easily know what each piece of code is responsible for in the program. 

Revisions and Reviews become much easier. As all the developers are easily able to understand the code and be confident any change is not going to break the program. The unit test will ensure that the core functionality of the code is never lost.

The unit test securing the core functionality will also ensure that code changes by any new developers or students can never cause defects. Also, new features can be added safely knowing that the code works properly. 

Cons: 
The unit tests are written first meaning if there is a poor planning process then they will need to re-written. As the tests need to be written before the code the programmers much spend considerable amount of time on these tests slowing down the start of the project.

As code changes the unit test will need to change and constantly updated. This means coverage for corner cases and failures. 

In a team setting all the members must write proper unit test or the coverage will inadequate. This will lead to TDD failing.
