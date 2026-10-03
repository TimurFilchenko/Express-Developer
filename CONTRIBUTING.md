# Contributing to Express Developer

Thank you for your interest in contributing to Express Developer.

Express Developer is an open-source reference for developers. Contributions help keep the documentation accurate, clear, useful, and up to date.

## How You Can Contribute

You can contribute in many ways:

- fix incorrect information;
- update outdated documentation;
- improve code examples;
- fix broken links;
- correct typos and grammar;
- improve explanations;
- suggest new topics;
- improve navigation;
- improve the project structure;
- report bugs.

Every useful contribution is welcome.

## Before You Start

Before making changes, check the existing documentation and project structure.

Make sure your changes:

- are relevant to the project;
- keep the documentation concise;
- use clear and understandable language;
- contain technically correct information;
- follow the existing project structure;
- do not introduce unnecessary dependencies.

## Documentation Guidelines

Documentation pages should remain short and focused.

A typical page should contain:

1. A short explanation.
2. Syntax, when necessary.
3. A simple code example.
4. An additional example, when useful.
5. An important note or tip, when necessary.
6. A short summary.

Avoid unnecessary text, repetition, and overly complicated explanations.

The goal is simple:

> Explain the topic clearly without making the page unnecessarily long.

## Code Examples

Code examples should be:

- correct;
- simple;
- readable;
- relevant to the topic;
- easy to copy and test.

Avoid adding complicated examples when a simpler example explains the concept sufficiently.

## Updating Existing Pages

When updating documentation, check the entire page instead of changing only one sentence.

Make sure that:

- the explanation is still correct;
- code examples still work;
- links still work;
- terminology is consistent;
- outdated information is removed or updated;
- the page remains concise.

## Project Structure

Each technology has its own directory inside `docs/`.

For example:

```text
docs/
└── csharp/
    ├── index.html
    ├── variables/
    │   └── index.html
    ├── data-types/
    │   └── index.html
    └── classes/
        └── index.html
```

Do not move or rename existing directories without a good reason.

Shared styles, scripts, and icons belong in `assets/`.

```text
assets/
├── css/
│   └── style.css
├── js/
│   └── main.js
└── icons/
```

## HTML Guidelines

Documentation pages should follow the existing project design.

Use:

- Noto Sans for regular text;
- JetBrains Mono for code;
- the existing dark interface;
- the existing muted blue link color;
- Prism.js for syntax highlighting;
- the existing page structure and spacing.

Every documentation page should contain:

```html
<meta name="robots" content="index, follow">
```

The favicon should use:

```html
<link rel="icon" href="/favicon.ico">
```

Do not introduce a completely different visual style for individual technologies.

## Links

Internal links should point to the relevant documentation pages.

Use descriptive link text.

Links should follow the existing visual style and should not have underlines.

## Icons

Use the existing icons from:

```text
assets/icons/
```

Do not create duplicate icons inside individual technology directories unless there is a specific project-wide reason to do so.

## Pull Requests

To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Check your changes locally.
5. Commit your changes.
6. Push the branch to your fork.
7. Open a Pull Request.

Keep Pull Requests focused.

A Pull Request that fixes one documentation issue is usually better than one that changes unrelated parts of the project.

## Pull Request Description

Describe what you changed and why.

For example:

```text
Updated the C# variables documentation.

- Corrected the explanation of variable declarations.
- Added an example using string.
- Fixed an internal link.
```

If your Pull Request fixes an Issue, mention the Issue number when appropriate.

## Review

Pull Requests may be reviewed before they are merged.

Reviewers may ask for:

- corrections;
- clearer explanations;
- simpler examples;
- updated information;
- structural changes.

Please keep discussions focused on improving the project.

## Issues

Use Issues to report:

- incorrect documentation;
- outdated information;
- broken links;
- bugs;
- missing topics;
- suggestions for improvements.

When reporting a documentation problem, include the page and explain what needs to be changed.

## Reporting a Documentation Error

A useful report can look like this:

```text
Page:
docs/csharp/variables/

Problem:
The explanation of the variable declaration is outdated.

Suggested change:
Update the explanation and add a current example.
```

## Keeping the Project Free and Ad-Free

Express Developer is a free and ad-free project.

Contributions should not introduce advertising, tracking scripts, or unrelated commercial content into the documentation.

## Dependencies

Avoid adding dependencies unless they are necessary for the project.

If a dependency is required, explain its purpose in the Pull Request.

## Security

Never commit:

- passwords;
- API keys;
- access tokens;
- private credentials;
- personal private information;
- secret configuration files.

If you accidentally expose a secret, remove it from the repository and report the issue immediately.

## License

By contributing to Express Developer, you agree that your contributions will be distributed under the project's MIT License.

See `LICENSE` for the full license text.

## Final Note

Express Developer is built by the community.

Whether you fix a typo, update an example, correct outdated information, or improve an entire documentation section, your contribution helps make the reference better.

Thank you for contributing to Express Developer.
