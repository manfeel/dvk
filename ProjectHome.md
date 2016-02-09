The goal of this project is to isolate Dalvik Virtual Machine's build artifacts (with dependencies) from rest of the Android stack.

The approach is to create a minimal set of Shell scripts, with necessary patch files, that can be run just like "repo" and "make" to get, build, deploy, test and run only Dalvik.

This project might be useful to you, if you:
  * are trying to port onto another CPU architecture
  * are trying to port onto another libc library, like glibc
  * are just interested in understanding Dalvik and its dependencies
  * have some innovative use in your mind

(and)

  * you do not want to work with the entire Android stack i.e. get, build, run the entire stack.

[List of active TODO Items for the project](ToDoList.md)