---
title: Static Typing with Python
source_url: https://typing.python.org/en/latest/
source_type: official_documentation
mirrored_at: 2026-10-02T05:14:08+00:00
package: docs.python-practices
---

# Static Typing with Python

Source: <https://typing.python.org/en/latest/>

Official typing guide.

#Static Typing with Python¶ (https://typing.python.org/en/latest/#static-typing-with-python)

Tutorials¶ (https://typing.python.org/en/latest/#tutorials)

Using External Libraries (https://typing.python.org/en/latest/tutorials/external_libraries.html)

Guides¶ (https://typing.python.org/en/latest/#guides)

Typing Python Libraries (https://typing.python.org/en/latest/guides/libraries.html)

The Trouble (Or Lack Thereof) With Lambda (https://typing.python.org/en/latest/guides/lambda.html)

Writing and Maintaining Stub Files (https://typing.python.org/en/latest/guides/writing_stubs.html)

Modernizing Superseded Typing Features (https://typing.python.org/en/latest/guides/modernizing.html)

Unreachable Code and Exhaustiveness Checking (https://typing.python.org/en/latest/guides/unreachable.html)

Type Narrowing (https://typing.python.org/en/latest/guides/type_narrowing.html)

Reasons to avoid static type checking (https://typing.python.org/en/latest/guides/typing_anti_pitch.html)

Reference¶ (https://typing.python.org/en/latest/#reference)

Generics (https://typing.python.org/en/latest/reference/generics.html)

Protocols and structural subtyping (https://typing.python.org/en/latest/reference/protocols.html)

Typing Best Practices (https://typing.python.org/en/latest/reference/best_practices.html)

Testing and Ensuring Type Annotation Quality (https://typing.python.org/en/latest/reference/quality.html)

typing Module Documentation (https://docs.python.org/3/library/typing.html)

See also

The documentation at https://mypy.readthedocs.io/ (https://mypy.readthedocs.io/) is relatively accessible and complete.

Specification¶ (https://typing.python.org/en/latest/#specification)

Specification for the Python type system (https://typing.python.org/en/latest/spec/index.html)

The Python Type System (https://typing.python.org/en/latest/spec/type-system.html)

Meta-topics (https://typing.python.org/en/latest/spec/meta.html)

Type system concepts (https://typing.python.org/en/latest/spec/concepts.html)

Type annotations (https://typing.python.org/en/latest/spec/annotations.html)

Type forms (https://typing.python.org/en/latest/spec/type-forms.html)

Special types in annotations (https://typing.python.org/en/latest/spec/special-types.html)

Generics (https://typing.python.org/en/latest/spec/generics.html)

Type qualifiers (https://typing.python.org/en/latest/spec/qualifiers.html)

Class type assignability (https://typing.python.org/en/latest/spec/class-compat.html)

Type aliases (https://typing.python.org/en/latest/spec/aliases.html)

Literals (https://typing.python.org/en/latest/spec/literal.html)

Protocols (https://typing.python.org/en/latest/spec/protocol.html)

Callables (https://typing.python.org/en/latest/spec/callables.html)

Constructors (https://typing.python.org/en/latest/spec/constructors.html)

`Overloads` (https://typing.python.org/en/latest/spec/overload.html)

Exceptions (https://typing.python.org/en/latest/spec/exceptions.html)

Dataclasses (https://typing.python.org/en/latest/spec/dataclasses.html)

Typed dictionaries (https://typing.python.org/en/latest/spec/typeddict.html)

Tuples (https://typing.python.org/en/latest/spec/tuples.html)

Named Tuples (https://typing.python.org/en/latest/spec/namedtuples.html)

Enumerations (https://typing.python.org/en/latest/spec/enums.html)

Type narrowing (https://typing.python.org/en/latest/spec/narrowing.html)

Type checker directives (https://typing.python.org/en/latest/spec/directives.html)

Distributing type information (https://typing.python.org/en/latest/spec/distributing.html)

Historical and deprecated features (https://typing.python.org/en/latest/spec/historical.html)

Glossary (https://typing.python.org/en/latest/spec/glossary.html)

Typing PEPs¶ (https://typing.python.org/en/latest/#typing-peps)

Significant changes to the Python Type System Specification are proposed and discussed in Python Enhancement Proposals (PEPs). See https://peps.python.org/topic/typing (https://peps.python.org/topic/typing) for a list of all current and historical typing-related PEPs.

Indices and tables¶ (https://typing.python.org/en/latest/#indices-and-tables)

Index (https://typing.python.org/en/latest/genindex.html)

Search Page (https://typing.python.org/en/latest/search.html)

Discussions and Support¶ (https://typing.python.org/en/latest/#discussions-and-support)

User help forum (https://github.com/python/typing/discussions)

User chat on Gitter (http://gitter.im/python/typing)

Developer forum (https://discuss.python.org/c/typing/32)

Developer mailing list (archived) (https://mail.python.org/archives/list/typing-sig@python.org/)

Typing-related Tools¶ (https://typing.python.org/en/latest/#typing-related-tools)

Type Checkers¶ (https://typing.python.org/en/latest/#type-checkers)

mypy (http://mypy-lang.org/)

pyrefly (https://pyrefly.org/)

pyright (https://github.com/microsoft/pyright)

ty (https://docs.astral.sh/ty/)

Zuban (https://docs.zubanls.com/en/latest/)

The extent to which these adhere to the specification is monitored by a conformance test suite (https://github.com/python/typing/tree/main/conformance) (results (https://htmlpreview.github.io/?https://github.com/python/typing/blob/main/conformance/results/results.html)).

Development Environments¶ (https://typing.python.org/en/latest/#development-environments)

PyCharm (https://www.jetbrains.com/pycharm/), an IDE that supports type stubs both for type checking and code completion.

Visual Studio Code (https://code.visualstudio.com/), a code editor that supports type checking using mypy, pyrefly, pyright, ty, Zuban, or the Pylance (https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) extension.

Linters and Formatters¶ (https://typing.python.org/en/latest/#linters-and-formatters)

black (https://black.readthedocs.io/), a code formatter with support for type stub files.

flake8-pyi (https://github.com/ambv/flake8-pyi), a plugin for the flake8 (https://flake8.pycqa.org/) linter that adds support for type stubs.

ruff (https://astral.sh/ruff), a linter built for speed, with support for most of the `flake8-pyi` rules.

Type-Hint and Stub Integration¶ (https://typing.python.org/en/latest/#type-hint-and-stub-integration)

autotyping (https://github.com/JelleZijlstra/autotyping), a tool which infers simple types from their context and inserts them as inline type-hints.

merge-pyi (https://google.github.io/pytype/developers/tools.html#merge_pyi), a thin wrapper around `ApplyTypeAnnotationsVisitor` from libCST (https://libcst.readthedocs.io/en/latest/) that integrates.pyi signatures as inline type-hints in Python source code.

pyrefly infer (https://pyrefly.org/en/docs/autotype/), a sub-command of Pyrefly which inserts the types that Pyrefly infers as inline type-hints.

Table of Contents (https://typing.python.org/en/latest/#)

Static Typing with Python (https://typing.python.org/en/latest/#)

Tutorials (https://typing.python.org/en/latest/#tutorials)

Guides (https://typing.python.org/en/latest/#guides)

Reference (https://typing.python.org/en/latest/#reference)

Specification (https://typing.python.org/en/latest/#specification)

Typing PEPs (https://typing.python.org/en/latest/#typing-peps)

Indices and tables (https://typing.python.org/en/latest/#indices-and-tables)

Discussions and Support (https://typing.python.org/en/latest/#discussions-and-support)

Typing-related Tools (https://typing.python.org/en/latest/#typing-related-tools)

Type Checkers (https://typing.python.org/en/latest/#type-checkers)

Development Environments (https://typing.python.org/en/latest/#development-environments)

Linters and Formatters (https://typing.python.org/en/latest/#linters-and-formatters)

Type-Hint and Stub Integration (https://typing.python.org/en/latest/#type-hint-and-stub-integration)

Next topic

Using External Libraries (https://typing.python.org/en/latest/tutorials/external_libraries.html)

This Page

Show Source (https://typing.python.org/en/latest/_sources/index.rst.txt)

Quick search

Navigation

index (https://typing.python.org/en/latest/genindex.html)

next (https://typing.python.org/en/latest/tutorials/external_libraries.html) |

Python (https://www.python.org/)»

typing documentation (https://typing.python.org/en/latest/#)»

Static Typing with Python

 |

 Theme AutoLightDark |

© Copyright 2021, The Python Typing Team.
 This page is licensed under the Python Software Foundation License Version 2.
 Examples, recipes, and other code in the documentation are additionally licensed under the Zero Clause BSD License.

 The Python Software Foundation is a non-profit corporation. Please donate. (https://www.python.org/psf/donations/)

 Created using Sphinx (https://www.sphinx-doc.org/) 9.1.0.
