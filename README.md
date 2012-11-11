# lein-midje-lazytest

A meta-package that brings lein-midje and lazytest together.

## Usage

Leiningen startup time is a real hurt for TDD. Marick's midje is a
good testing framework that supports both Clojure tests and Midje tests on
top of lazytest.

Now all you have to do is:
  - Add `[lein-midje-lazytest "0.1.0"]` to `~/.lein/profiles.clj`

And run lein-midje as a watcher process that reloads any changed test files:

```bash
$ lein midje --lazytest
```

## License

Copyright © 2012 Hoang Minh Thang

Distributed under the Eclipse Public License, the same as Clojure.
