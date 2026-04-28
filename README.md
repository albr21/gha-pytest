# gha-pytest

A GitHub Action to run pytest, generating test summary and coverage report.
Working only on Linux based environment.

## Usage

```yaml
steps:
  - name: Run pytest
    uses: albr21/gha-pytest@1.0.0
    with:
      source-dir: src
      min-coverage: '80'
```

## Contributing

Check out the [CONTRIBUTING](CONTRIBUTING.md) file for guidelines on how to contribute to this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
