# Invocation

jupyter allows you to pass options to the underlying implementation. This is an example from my work at Mayo where I had large notebooks that wouldn't get saved without increasing the `max_body_size` and `max_buffer_size` values.

```
jupyter notebook --NotebookApp.iopub_data_rate_limit=100000000 --NotebookApp.tornado_settings="{'max_body_size': 104857600, 'max_buffer_size': 104857600}" ~/git_repos/cra-data-review/python/pkg_cra/notebooks/
```

# Version Control
By default notebooks have the output in base64 encoded blobs which can make merging and diffing difficult. Some ideas here:

[Jupyter Notebook Best Practices for Data Science](https://www.svds.com/jupyter-notebook-best-practices-for-data-science/)
