# ml-repo-template
Template repository representing a simple ml repository structure with branches dealing with both r&amp;d and productization.


This branch "research_and_development" represents the iterative exploration and experimentation carried out in jupyter notebooks.

You will find all notebooks under the "notebooks" folder, having the following format:

```bash
YYYY-MM-DD-<initials>-task-subtask.ipynb
```

These notebooks' outputs should be cleared before being committed to this repository, as otherwise file size.

I would advise using the "jupytext" library to handle the autoconversion of notebooks to a notebook-compatible .py format for code commit purposes.

Combine this with DVC to version control your data and datasets outside of git and github.
