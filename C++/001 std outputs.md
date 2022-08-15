**Standard output stream (cout):** `cout` is the instance of the `ostream` class. `cout` is used to produce output on the standard output device which is usually the display screen. The data needed to be displayed on the screen is inserted in the standard output stream (`cout`) using the insertion operator (`<<`).

**Un-buffered standard error stream (cerr):** `cerr` is the standard error stream which is used to output the errors. This is also an instance of the `ostream` class. As `cerr` is **un-buffered** so it is used when we need to display the error message immediately. It does not have any buffer to store the error message and display later.

**Buffered standard error stream (clog):** This is also an instance of `ostream` class and used to display errors but unlike `cerr` the error is first inserted into a **buffer** and is stored in the buffer until it is not fully filled.

further reading : [basic-input-output-c](http://www.geeksforgeeks.org/basic-input-output-c/)