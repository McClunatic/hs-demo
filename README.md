# Farm Haystack Demo

This demo uses tutorial 3 from the Haystack documentation, which you can
read more about in the
[Haystack documentation](https://haystack.deepset.ai/tutorials/without-elasticsearch).

## Environment setup

This should probably be changed, but the environment is created
in two steps:

1. Create and activate the conda environment
2. Install PyPI packages

```shell
(base) > conda env create -n haystack -f environment.yml
(base) > conda activate haystack
(haystack) > pip install -f requirements.txt
```
