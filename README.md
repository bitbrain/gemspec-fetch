# 💎 Gemspec Fetch

Github Action that fetches metadata from any .gemspec file

## Usage

```yml
- name: 💎 Extract gemspec info
  id: gemspec_fetch
  uses: bitbrain/gemspec-fetch@1.0
  with:
  specfile: rubygem.gemspec
```
and then access the following outputs:
```
${{ steps.gemspec_fetch.outputs.name }}
${{ steps.gemspec_fetch.outputs.version }}
${{ steps.gemspec_fetch.outputs.description }}
${{ steps.gemspec_fetch.outputs.homepage }}
${{ steps.gemspec_fetch.outputs.summary }}
```
