# nTopology Style Guides

We have decided to use the Google Style Guide as a base for our own. Our focus
is on the C++ styleguide.

Not all of Google's opinions or patterns will be followed. This should not
be assumed to be a 1:1 and should be read independently. In several areas we
differ significantly.

The first step is to go through the StyleGuide and make sure that all sections
are updated to reflect generally the expectations at nTopology. These will be
taken as guidelines rather than policies for the time being. The StyleGuide
internally does contain policies and should not be confused with this one.

As we build up this document, we may declare some of the content to be a policy
in itself and will be clearly marked as such.

*When this line is removed, the StyleGuide will be considered up to date with
nTopology expectations*

## Internal Contribution

Please open PRs for contributions, specially for those that present significant
changes to guidelines or policies.

## Attribution

We attribute the bulk of work for this StyleGuide to Google, and maintain
the original license unchanged.

# Google Style Guides

Every major open-source project has its own style guide: a set of conventions
(sometimes arbitrary) about how to write code for that project. It is much
easier to understand a large codebase when all the code in it is in a
consistent style.

“Style” covers a lot of ground, from “use camelCase for variable names” to
“never use global variables” to “never use exceptions.” This project
([google/styleguide](https://github.com/google/styleguide)) links to the
style guidelines we use for Google code. If you are modifying a project that
originated at Google, you may be pointed to this page to see the style guides
that apply to that project.

This project holds several guides. We will link the specific ones we use
at nTopology as a list:
[C++ Style Guide][cpp]

This project also contains [cpplint][cpplint], a tool to assist with style
guide compliance, and [google-c-style.el][emacs], an Emacs settings file for
Google style. The linter is not (yet) modified to work for `nTopology`

If your project requires that you create a new XML document format, the [XML
Document Format Style Guide][xml] may be helpful. In addition to actual style
rules, it also contains advice on designing your own vs. adapting an existing
format, on XML instance document formatting, and on elements vs. attributes.

The style guides in this project are licensed under the CC-By 3.0 License,
which encourages you to share these documents.
See [https://creativecommons.org/licenses/by/3.0/][ccl] for more details.

## Contributing

This styleguide is treated as internal to nTopology. While public, 
**External contributions are not accepted.** 
Pull requests are regularly closed without comment.

<a rel="license" href="https://creativecommons.org/licenses/by/3.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/3.0/88x31.png" /></a>

[cpp]: https://google.github.io/styleguide/cppguide.html
[csharp]: https://google.github.io/styleguide/csharp-style.html
[swift]: https://google.github.io/swift/
[objc]: objcguide.md
[java]: https://google.github.io/styleguide/javaguide.html
[py]: https://google.github.io/styleguide/pyguide.html
[r]: https://google.github.io/styleguide/Rguide.html
[sh]: https://google.github.io/styleguide/shellguide.html
[htmlcss]: https://google.github.io/styleguide/htmlcssguide.html
[js]: https://google.github.io/styleguide/jsguide.html
[ts]: https://google.github.io/styleguide/tsguide.html
[angular]: https://google.github.io/styleguide/angularjs-google-style.html
[cl]: https://google.github.io/styleguide/lispguide.xml
[vim]: https://google.github.io/styleguide/vimscriptguide.xml
[cpplint]: https://github.com/google/styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/styleguide/gh-pages/google-c-style.el
[xml]: https://google.github.io/styleguide/xmlstyle.html
[go]: https://golang.org/wiki/CodeReviewComments
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/

