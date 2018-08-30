# Your First Learn Lab

## Problem Statement

Before we begin diving deep into code, it is important to make sure that we go
over the proper steps involved in completing labs on Learn. In this _lab_ (yep,
this is a lab!), we will be introducing those steps.

## Objectives

1. Introduce the concept of running tests on Learn
2. Pass the tests to confirm you are ready for future lessons

## Labs Are Lessons _with Tests_

On Learn, labs are lessons with tests. The difficulty level of labs will vary,
but they all follow the same core steps. To start any lab, if you are using the
Learn IDE, you must first either click "Open IDE" (or, if you are using your own
local set up, _fork and clone_ this repository).  This will make a personal copy
of the lab for you to work on. Once you've opened up your development
environment, follow the steps below:

1. In your terminal, type `learn` and press enter
2. Read the messages that appear in the terminal.
3. Make adjustments to your code based on the messages you've received
4. Run `learn` again to see if progress has been made
5. Repeat steps 2 through 3 until all tests pass (sometimes referred to as being _green_)
6. Once all tests pass, run `learn submit` to submit your code

Whether you are using the in-browser Learn IDE, the standalone Learn IDE or your
own local set up, these core steps will always be the same for passing labs.
Don't be alarmed if you don't understand everything that prints out in the
terminal just yet.  The main thing to look for is the breakdown of failed tests:

```sh
Your First Learn Lab
  contains a file called "-file.txt" (FAILED -1)

Failures:

  1) Your First Learn Lab
  contains a file called "-file.txt"

Each failed test will appear in order. It is recommended that you start from the
first (the top most) test failure and work your way through until all tests are
passing.

For the final step, when you run `learn submit`, the work you've completed is
sent back, learn.co is notified, registers that you've sent in your work and
marks that you have completed the lab.

## Reinforce What We Have Learned About Labs

The best way to understand the workflow described above is to apply it! There is
_one_ test in this lab.  In order to pass the test, follow the numbered steps above. The
first time you run `learn`, the test will fail, but the resulting message will
provide information about how to pass.

When you've passed the test, run `learn submit`.

## Conclusion

That's it, you're done! Again, lab difficulty will vary greatly depending on the
learning goals within them. Some will be more guided, as you are introduced to
new concepts. In these, test messages may tell you exactly what you need to do.
Some labs are built specifically to test your problem solving skills.  The test
messages in these labs may be more ambiguous, requiring you to try a variety of
possible solutions.

When you've successfully passed the tests and run `learn submit`, on learn.co,
all lights for this lesson will turn green and you can continue on with the
course.
