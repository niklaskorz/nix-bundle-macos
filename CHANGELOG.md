# Changelog

## Unreleased

- Use nix flakes
- Write output to `$PWD/result` instead of `/Applications` or `/usr/local/`
- Remove need of sudo by adding writable flag to directories copied from nix store
- Fix `patch_strings_in_file` to work on macOS (previous variant only worked with GNU coreutils)
- Use relative paths (based on `@executable_path`) instead of absolute paths when patching nix store paths
- Sign result for local user to allow execution on Apple Silicon

## Pre-fork

- Original scripts by @ariutta
