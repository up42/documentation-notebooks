---
name: Bug report
about: Create a report to help us improve
title: "[BUG]"
labels: ''
assignees: ''

---

## Title

{A summarized description of the issue using key terms related to the problem.}

## Summary

{If the title is insufficient, provide a more detailed explanation of the bug here. Keep it concise (3-4 sentences) and describe the bug's impact  and what actions were taken.}

## Environment

{Details about the environment where the bug occurred. This may include the Python version, the SDK version, any dependencies or tools used in your notebooks.}

* Python version: {e.g. 3.8.5}
* SDK version: {e.g. 1.2.3}
* Installed dependencies and versions: {e.g. requests 2.25.1, numpy 1.19.2}
* Jupyter notebook version: {e.g. 6.1.5}
* Operating system: {e.g. macOS 11.2, Windows 10, Linux Ubuntu 20.04}

## Steps to reproduce

{An ordered list detailing the steps that lead to encountering the bug. Include any observations such as incorrect output, errors, or unexpected behavior when running the notebook. If the bug is related to specific API calls or methods, include that information.}

1. Opened the notebook `{name_of_notebook}.ipynb` and run the cells up until cell 13.
1. Called the method `{name_of_method}` with the following parameters: `{list_of_parameters}`.
1. Encountered unexpected behavior.

## Behavior

### Observed

{Describe the observed outcome, including any error messages or logs, and how the bug manifests in the notebook. If it’s an issue with a method, include the error output or traceback, if available.}

### Expected

{Describe what should have happened when following the steps above. If an error occurred, mention the correct expected behavior or output.}

## Proof 

{Provide relevant logs, error messages, screenshots, or malformed output. If there's a Python traceback, include it to help diagnose the problem.}

## Test data

{If the bug only occurs with specific input data, provide a sample of that data. If needed, redact any sensitive information, but make sure the data still causes the bug to occur.}

Example test data:
```
search_parameters = catalog.construct_search_parameters(
    collections=["phr"],
    geometry=geometry,
    max_cloudcover=20,
)
```
