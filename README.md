# .github

Organization-wide files for [octobit-dev](https://github.com/octobit-dev).

- `profile/README.md`: the organization profile shown on github.com/octobit-dev.
- `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`: default community health files. GitHub shows them in every repository of the organization that has no file of its own with the same name.
- `.github/ISSUE_TEMPLATE/` and `.github/pull_request_template.md`: default issue and pull request templates.
- `.github/workflows/`: CI for this repository. Reusable workflows for other repositories will live here too.

A repository overrides a default by adding its own file. For issue templates the override is all or nothing: a repository with its own `.github/ISSUE_TEMPLATE/` folder gets none of the defaults.

## License

Licensed under either of [Apache License, Version 2.0](LICENSE-APACHE) or [MIT license](LICENSE-MIT) at your option.

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in the work by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
