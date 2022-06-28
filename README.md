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

[cpp]: https://ntopology.github.io/code-styleguide/cppguide.html
[csharp]: https://ntopology.github.io/code-styleguide/csharp-style.html
[swift]: https://ntopology.github.io/swift/
[objc]: objcguide.md
[java]: https://ntopology.github.io/code-styleguide/javaguide.html
[py]: https://ntopology.github.io/code-styleguide/pyguide.html
[r]: https://ntopology.github.io/code-styleguide/Rguide.html
[sh]: https://ntopology.github.io/code-styleguide/shellguide.html
[htmlcss]: https://ntopology.github.io/code-styleguide/htmlcssguide.html
[js]: https://ntopology.github.io/code-styleguide/jsguide.html
[ts]: https://ntopology.github.io/code-styleguide/tsguide.html
[angular]: https://ntopology.github.io/code-styleguide/angularjs-google-style.html
[cl]: https://ntopology.github.io/code-styleguide/lispguide.xml
[vim]: https://ntopology.github.io/code-styleguide/vimscriptguide.xml
[cpplint]: https://github.com/ntopology/code-code-styleguide/tree/gh-pages/cpplint
[emacs]: https://raw.githubusercontent.com/google/code-styleguide/gh-pages/google-c-style.el
[xml]: https://ntopology.github.io/code-styleguide/xmlstyle.html
[go]: https://golang.org/wiki/CodeReviewComments
[dart]: https://www.dartlang.org/guides/language/effective-dart
[ccl]: https://creativecommons.org/licenses/by/3.0/

