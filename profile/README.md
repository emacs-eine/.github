EINE (EINE Is NOT Emacs!) is a collection of software that does not use Emacs in the traditional way (such as code libraries or editor tools).
Instead, it treats Emacs Lisp as a general-purpose programming language, and the software built with it can be used for regular development tasks,
just like other languages (e.g. [Python][], [Java][], [Rust][], and [C][]).

Currently, most packages are hosted on [EINE Elpa][]. However, in most cases you don’t need to worry about where these packages are hosted,
since they are not designed to be used directly in your Emacs configuration.

We use [Eask][] as the package manager because it supports global, local, and configuration-space installations.
This allows you to use these tools outside of your Emacs setup, preventing pollution of your Emacs configuration (usually `.emacs.d`).

---

To learn more about using Eask as a code launcher and runtime environment, check out the following articles:

- [Treat Emacs as an Elisp Runtime using Eask](https://www.jcs-profile.com/posts/editor/elisp-runtime/)
- [How to build your own ELPA with Eask?](https://www.jcs-profile.com/posts/editor/build-elpa/)

> [!NOTE]
>
> *📝 The entire EINE project is still in its early stages and largely experimental.
> Some tools may be incomplete, unstable, or lack long-term guarantees, so EINE should
> currently be considered a playground for exploration rather than a production-ready ecosystem.*
 

<!-- Links -->

[C]: https://en.wikipedia.org/wiki/C_(programming_language)
[Rust]: https://rust-lang.org/
[Java]: https://www.java.com/
[Python]: https://www.python.org/

[JCS-ELPA]: https://jcs-emacs.github.io/jcs-elpa/
[EINE Elpa]: https://github.com/emacs-eine/elpa/
[Eask]: https://emacs-eask.github.io/
