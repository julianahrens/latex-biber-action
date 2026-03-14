# Latex Biber Action

This action prints helps you to compile latex by using biber.

## Archival Notice

> [!IMPORTANT]
> This repository is no longer actively maintained and is considered **archived**.  
> For compiling LaTeX documents in GitHub Actions, it is recommended to use the "LaTeX Compilation" GitHub Action instead: <https://github.com/marketplace/actions/latex-compilation>.

## Inputs

### `filename`

**Required** The name of the file to compile

### `output-directory`

**Required** The name of the output dir

## Example usage
```yaml
uses: actions/latex-biber-action@v2
with:
  filename: 'main'
  output-directory: 'out'
```
