---
layout: post
title:  "ClearLinux for C++"
date:   2019-12-31 09:56:17 -0600
categories: C++ programming Docker
---
My favorite Linux distribution is [ClearLinux][clearlinux].
Most of what I am doing on Linux is programming in C++.
Having the latest g++ and clang compilers is nice.
ClearLinux does a great job providing up to date compilers and libraries.

One thing you have to do with ClearLinux is install the developer tools.
Let's use Docker to install the tools.

{% highlight shell %}
FROM clearlinux:base
RUN swupd bundle-add editors dev-utils c-basic \
    devpkg-curl devpkg-boost devpkg-googletest
{% endhighlight %}

Here is an incomplete summary of what is installed
- cmake, ninja and GNU make
- g++ and clang
- gdb and lldb
- valgrind and clang-tidy
- vi and emacs
- Boost libraries, cURL libraries and GoogleTest libraries

The docker image is around 2GB.
Here's the command to run it right off hub.docker.com.

{% highlight shell %}
docker run -it -v $PWD:/workspace snoe925/clearlinux-cpp:latest
{% endhighlight %}

The /workspace path is used to match VSCode's preferences.

[clearlinux]: https://clearlinux.org/
[docker]: https://www.docker.com/
[ninja]: https://ninja-build.org/
[cmake]: https://cmake.org
[valgrind]: https://valgrind.org/
