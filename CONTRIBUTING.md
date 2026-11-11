# Contributing

This guide applies to every repository of this account that has no `CONTRIBUTING.md` of its own.

1. For anything bigger than a small fix, open an issue first so we can agree on the approach.
2. Create a branch from `main` and open a pull request against `main`. Direct pushes to `main` aren't accepted.
3. Write the pull request title as a [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) (`feat:`, `fix:`, `docs:`, `chore:`, `refactor:`). Pull requests are squash-merged, so the title becomes the commit message.
4. Link the issue in the description: `Closes #N` if the pull request finishes it, `Refs #N` if it covers only part of it.
5. Wait for the checks to pass and say how you tested the change.
6. Never commit secrets or personal data. Use made-up example data such as `example.org`.

Contributions written with AI tools are welcome. Name the tool in a `Co-Authored-By:` trailer.
