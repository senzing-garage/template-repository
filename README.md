# template-repository

If you are beginning your journey with [Senzing],
please start with [Senzing Quick Start guides].

You are in the [Senzing Garage] where projects are "tinkered" on.
Although this GitHub repository may help you understand an approach to using Senzing,
it's not considered to be "production ready" and is not considered to be part of the Senzing product.
Heck, it may not even be appropriate for your application of Senzing!

This repository contains exemplar artifacts (files) for Senzing repositories.

GitHub provides support for these artifacts.  As an example, click on the following links on this GitHub repository:

- "Insights" tab > "[Community]" on left-hand navigation bar

## Files

Senzing community files:

1. [CHANGELOG.md]
1. [CODE_OF_CONDUCT.md]
1. [CONTRIBUTING.md]
1. [docs/]
1. .github/
    1. [CODEOWNERS]
    1. [dependabot.yml]
    1. [senzing-corporate-contributor-license-agreement]
    1. [senzing-individual-contributor-license-agreement]
    1. workflows/
1. [LICENSE]
1. [README.md]

## README.md

Although the file you are reading is a `README.md` file, this isn't the style of `README.md` for most projects.
Depending upon the type of repository, the following `README.md` templates may be more appropriate:

Examples:

  1. [template-docker/README.md]
  1. [template-go/README.md]
  1. [template-python/README.md]

## CHANGELOG.md

The contents of the [CHANGELOG]
are meant to be consumed by users of the repository.
As such, they need to know what changes affect them as users.
In general, changes that do not effect users should not be captured in CHANGELOG.md.
For this reason, automatic generation of CHANGELOG.md entries is discouraged.

The format of `CHANGELOG.md` is based on [Keep a Changelog], [markdownlint].
Also, projects adhere to [Semantic Versioning].

## CODE_OF_CONDUCT.md

The [CODE_OF_CONDUCT] file describes the social conventions among contributors to the repository.

> A *code of conduct* defines standards for how to engage in a community. It signals an inclusive environment that respects all contributions. It also outlines procedures for addressing problems between members of your project's community. For more information on why a code of conduct defines standards and expectations for how to engage in a community, see the [Open Source Guide].
>
> -- <cite>GitHub's [Adding a code of conduct to your project]</cite>

The [CODE_OF_CONDUCT] file in this repository is based on GitHub's "[Contributor Covenant]".

### How to create CODE_OF_CONDUCT.md

1. Option #1: Using GitHub's "Wizard"
    1. [github.com] > (choose repository) > Insights > Community > Code of conduct > "Add" button > "Contributor Covenant"
1. Option #2: Manual file creation
    1. See GitHub's [Adding a code of conduct to your project]
    1. Alternative `CODE_OF_CONDUCT.md` content:
        1. [Apache Software Foundation Code of Conduct]

## CONTRIBUTING.md

The
[CONTRIBUTING]
file describes the process for contributing to the repository.

> To help your project contributors do good work, you can add a file with contribution guidelines to your project repository's root. When someone opens a pull request or creates an issue, they will see a link to that file.
>
> -- <cite>GitHub's [Setting guidelines for repository contributors]</cite>

The [CONTRIBUTING] file in this repository is an example that needs to be modified to represent the requirements of the actual repository.

### How to create CONTRIBUTING.md

1. Option #1: Using GitHub's "Wizard"
    1. [github.com] > (choose repository) > Insights > Community > Contributing > "Add" button
1. Option #2: Manual file creation
    1. See GitHub's [Setting guidelines for repository contributors]

## docs

The
[docs] subdirectory may be published as [GitHub Pages].
They become visible at
[hub.senzing.com].
URLs have the format:

```console
https://hub.senzing.com/<repository-name>
```

Example:
[hub.senzing.com/sdk-components-ng]

## .github

### .github/CODEOWNERS

The
[.github/CODEOWNERS] file implements GitHub's [code owners].
The teams that may appear in a `CODEOWNERS` file can be seen at
[github.com/orgs/Senzing/teams].

### .github/dependabot.yml

The
[dependabot.yml] file is configuration for [GitHub's dependabot].

### .github/senzing-corporate-contributor-license-agreement.pdf

The Senzing, INC. Software Grant and Corporate Contributor License Agreement (CCLA),
[senzing-corporate-contributor-license-agreement.pdf],
is the standard agreement for a corporation's contribution to a Senzing repository.

#### How to create .github/senzing-corporate-contributor-license-agreement.pdf

1. Make a `.github` directory in the repository
1. Copy [senzing-corporate-contributor-license-agreement.pdf] into the new `.github` directory
1. *DO NOT* modify the contents of [senzing-corporate-contributor-license-agreement.pdf] without legal approval.
1. Reference `senzing-corporate-contributor-license-agreement.pdf` in [CONTRIBUTING.md]

### .github/senzing-individual-contributor-license-agreement.pdf

The Individual Contributor License Agreement (ICLA),
[senzing-individual-contributor-license-agreement.pdf],
is the standard agreement for an individual's contribution to a Senzing repository.
*Note:* if an individual is contributing on behalf of a company, the
[senzing-corporate-contributor-license-agreement]
must also be submitted and accepted.

#### How to create .github/senzing-individual-contributor-license-agreement.pdf

1. Make a `.github` directory in the repository
1. Copy [senzing-individual-contributor-license-agreement.pdf] into the new `.github` directory
1. *DO NOT* modify the contents of [senzing-individual-contributor-license-agreement.pdf] without legal approval.
1. Reference `senzing-individual-contributor-license-agreement.pdf` in [CONTRIBUTING.md]

### .github/workflows

## LICENSE

The `LICENSE` file describes the terms and conditions under which the code in the repository can be used.
The recommended license file is "[Apache License 2.0]".
A comparison of licenses can be found at [choosealicense.com].

The [LICENSE file] in this repository is based on "[Apache License 2.0]".

### How to create LICENSE

1. Option #1: Using GitHub's "Wizard"
    1. When [creating a new repository], in the "Add a license:" drop-down, choose "Apache License 2.0"
1. Option #2: Manual file creation
    1. See GitHub's [Adding a license to a repository]

[.github/CODEOWNERS]: .github/CODEOWNERS
[Adding a code of conduct to your project]: https://help.github.com/articles/adding-a-code-of-conduct-to-your-project/
[Adding a license to a repository]: https://help.github.com/articles/adding-a-license-to-a-repository/
[Apache License 2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[Apache Software Foundation Code of Conduct]: https://www.apache.org/foundation/policies/conduct.html
[CHANGELOG.md]: #changelogmd
[CHANGELOG]: CHANGELOG.md
[choosealicense.com]: https://choosealicense.com/licenses/
[code owners]: https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/about-code-owners
[CODE_OF_CONDUCT.md]: #code_of_conductmd
[CODE_OF_CONDUCT]: CODE_OF_CONDUCT.md
[CODEOWNERS]: #githubcodeowners
[Community]: https://github.com/senzing-factory/template-repository/community
[CONTRIBUTING.md]: #contributingmd
[CONTRIBUTING]: CONTRIBUTING.md
[Contributor Covenant]: https://www.contributor-covenant.org/version/1/4/code-of-conduct.html
[creating a new repository]: https://github.com/new
[dependabot.yml]: #githubdependabotyml
[docs]: docs
[docs/]: #docs
[GitHub Pages]: https://pages.github.com/
[github.com]: https://github.com/
[github.com/orgs/Senzing/teams]: https://github.com/orgs/Senzing/teams
[GitHub's dependabot]: https://docs.github.com/en/code-security/dependabot
[hub.senzing.com]: https://hub.senzing.com/
[hub.senzing.com/sdk-components-ng]: https://hub.senzing.com/sdk-components-ng/
[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[LICENSE file]: LICENSE
[LICENSE]: #license
[markdownlint]: https://dlaa.me/markdownlint/
[Open Source Guide]: https://opensource.guide/code-of-conduct/
[README.md]: #readmemd
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
[Senzing Garage]: https://github.com/senzing-garage
[Senzing Quick Start guides]: https://docs.senzing.com/quickstart/
[senzing-corporate-contributor-license-agreement.pdf]: .github/senzing-corporate-contributor-license-agreement.pdf
[senzing-corporate-contributor-license-agreement]: #githubsenzing-corporate-contributor-license-agreementpdf
[senzing-individual-contributor-license-agreement.pdf]: .github/senzing-individual-contributor-license-agreement.pdf
[senzing-individual-contributor-license-agreement]: #githubsenzing-individual-contributor-license-agreementpdf
[Senzing]: https://senzing.com/
[Setting guidelines for repository contributors]: https://help.github.com/articles/setting-guidelines-for-repository-contributors/
[template-docker/README.md]: https://github.com/senzing-garage/template-docker/blob/main/README.md
[template-go/README.md]: https://github.com/senzing-garage/template-go/blob/main/README.md
[template-python/README.md]: https://github.com/senzing-garage/template-python/blob/main/README.md
