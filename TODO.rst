TODO
====

In development branch:

* Figure out a way to suppress center alignment of images in reST output.
* Add a unit test for the change made in 7ea8e7180c41.  This is with regard
  to not requiring spec tests when running tests from a downloaded sdist.
* Turn the benchmarking script at pystache/tests/benchmark.py into a command
  in pystache/commands, or make it a subcommand of one of the existing
  commands (i.e. using a command argument).
* Provide support for logging in at least one of the commands.
* Combine pystache-test with the main command.
