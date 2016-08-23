# wb_shortcuts
Script for common short wb_command sequences

The design of wb_command is to have each command do a small, self-contained bit
of computation or conversion, to increase the flexibility available when
writing scripts.  However, this can be awkward to use for common tasks that
involve a few steps (but aren't long enough to deserve a pipeline script), as
these are frequently typed directly onto the command line.

This script takes a middle ground between the step-at-a-time nature of
wb_command and the full-processing-stream nature of pipelines, to make certain
command line tasks easier.  It has simpler command line structure than
wb_command, with fewer options, and focuses on narrower, more common use cases,
at the expense of flexibility.
