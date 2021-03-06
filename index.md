---
title: Elixir, Ruby, C, Common Lisp, UNIX
---

## 1 [Hosting](/hosting)

Dedicated hardware, OpenBSD, nginx hosting.
We host your Elixir, Ruby, Common Lisp, C/C++ project.

## 2 Development
Commercial and open-source development targeting BSD, Linux, Windows.

We can deliver small websites rapidly and large scale web applications
on time and budget using Elixir/Phoenix.

### 2.1 [Elixir / Phoenix](/elixir)

We recommend [Elixir](/elixir) and Phoenix for website development.

### 2.2 C
[C](https://en.wikipedia.org/wiki/C_(programming_language))
is probably the true reason for the success of
[UNIX](https://en.wikipedia.org/wiki/Unix)
as an operating system.

#### 2.2.1 Rtbuf
[![{rtbuf}](https://avatars0.githubusercontent.com/u/61788641?s=96)](https://rtbuf.kmx.io/)

[Rtbuf](https://rtbuf.kmx.io/)
is BSD licensed ANSI C for realtime signal processing.

It seems that these last years most programming action happens in
high level programming languages which rely on garbage collectors
to free memory. The problem of a GC is that it induces latency because
while the program is stopped collecting free memory it stops other
processing so real-time applications are not possible with most modern
programming languages. Multi-processor safe and real-time garbage
collectors are not open source and very expensive pieces of software.

A possible solution to handle real time computation on a garbage
collected platform is to offload real-time computations to a C server
running rtbuf which has no garbage collector and is highly portable.

Possible applications include audio and video applications, games
and experimental setups.

Current audience is developers. Status : alpha.

See the project page on Github :
[https://github.com/rtbuf/rtbuf](https://github.com/rtbuf/rtbuf)

#### 2.2.2 git-auth
[git-auth](https://github.com/kmx-io/git-auth)
is a restricted shell for your git user on your server.

It sends commands through
[git-shell](https://git-scm.com/docs/git-shell).

It supports rule matching to allow git commands
based on an environment variable set in authorized_keys file.

#### 2.2.3 facts_db
[facts_db](https://github.com/facts-db/facts_db)
is a graph database in C99.

With facts_db you can structure NULL terminated strings into a graph.
Join queries are considered the norm in a graph database and are as fast
as normal queries. facts_db is small footprint, open-source and
portable.

### 2.3 C++

### 2.4 Common Lisp
[Common Lisp](https://cliki.net/)
is one of the few programming languages still in use after
20 years of existence.

It has the best object model around (CLOS), compiles to native
code and supports multiple paradigms thanks to macros which make
the compiler itself programmable.

Its weights are an archaic namespace, lack of non-blocking semantics
for streams, and loads of misconceptions forwarded by non-lispers.
However the standard is stable and there are many compilers so the
notion of bitrot has almost disappeared.

The open-source (and free) native compilers are quite young and the
open source community is on the rise. The party is just starting now.

#### 2.4.1 [cl-facts](https://github.com/facts-db/cl-facts)
[![(facts)](/img/cl-facts.96.png)](https://github.com/facts-db/cl-facts)

[facts-db](https://github.com/facts-db) is a very fast, concurrent,
in-memory, graph database (triple store) implemented in various languages.
With facts-db you can represent and structure any kind of data without
a schema. Join queries are considered the norm in a graph database and are
as fast as normal queries. facts-db is small footprint and a good middle
ground between low level and high level database management system.
There is much room for improvement but we consider it production ready.

[cl-facts](https://github.com/facts-db/cl-facts) is a Common Lisp
implementation of facts-db available under the ISC license.

#### 2.4.2 cffi-posix
[![(cffi-posix)](https://avatars3.githubusercontent.com/u/28656020?s=96)](https://github.com/cffi-posix)

[cffi-posix](https://github.com/cffi-posix)
is an open-source project to portably and regularly expose the
[POSIX](http://pubs.opengroup.org/onlinepubs/9699919799/)
API to Common Lisp programs using
[CFFI](https://common-lisp.net/project/cffi/)

#### 2.4.3 cl-stream
[cl-stream](https://github.com/cl-stream)
is an experimental project to replace Common Lisp streams with
streams supporting any type of data and non-blocking semantics,
following principles found in
[SICP](https://github.com/sarabander/sicp-pdf/blob/master/sicp.pdf)

Includes a standard library of stream classes to be re-used
easily.

cl-stream streams are compatible with
[cffi-epoll](https://github.com/cffi-posix/cffi-epoll)
and
[cffi-kqueue](https://github.com/cffi-posix/cffi-kqueue)
. See
[Thot](https://github.com/RailsOnLisp/thot)
for an example usage.

#### 2.4.4 adams
[![(adams)](https://avatars1.githubusercontent.com/u/38501850?s=96)](https://github.com/cl-adams/adams)

[Adams](https://github.com/cl-adams/adams)
is a UNIX system administrator written in Common Lisp.
It produces commands for the shell (/bin/sh) for local or
remote hosts using
<a href="https://www.openssh.com/" target="_blank">SSH</a>
in order to retrieve and modify a UNIX system status.

Currently it allows automated administration of users, groups and
packages on Linux and OpenBSD without any additional requirement
or installation on the target machines.

#### 2.4.5 Thot
[![Thot](https://repository-images.githubusercontent.com/86985450/bb450a80-61f4-11ea-8007-754183b76786)](https://github.com/RailsOnLisp/thot)

[Thot](https://github.com/RailsOnLisp/thot)
Threaded HTTP server supporting epoll and kqueue in Common Lisp.

#### 2.4.6 RailsOnLisp
[![ROL](https://avatars2.githubusercontent.com/u/11281575?s=96)](https://github.com/RailsOnLisp)

[RailsOnLisp](https://github.com/RailsOnLisp)
Common Lisp MVC web development framework very much
inspired by [RubyOnRails](https://rubyonrails.org/).

The goal is to give Ruby programmers an insight into Common Lisp
through the Rails API and principles.


### 2.5 Ruby
[Ruby](https://www.ruby-lang.org/) is nice.


## 3 Talks

<https://github.com/thodg/slides>

## 4 Contact

### 4.1 [Our team](/team/)

We are available for free-lance contracting.
If you need to outsource hosting, maintenance, or development please get in touch.

Contact us with your project details and budget at contact@kmx.io.


## 5 [Links](/links)

-----

&copy; 2018-2020 Thomas de Grivel <thoxdg@gmail.com>
