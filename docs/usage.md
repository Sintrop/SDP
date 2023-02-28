Usage
=====

Installation
------------

To use sintrop, first install it using pip:

```console
(.venv) $ pip install sintrop
```

Creating recipes
----------------

To retrieve a list of random ingredients, you can use the
`sintrop.get_random_ingredients()` function:

::: sintrop.get_random_ingredients
    options:
      show_root_heading: true

<br>

The `kind` parameter should be either `"meat"`, `"fish"`, or `"veggies"`.
Otherwise, [`get_random_ingredients`][sintrop.get_random_ingredients] will raise an exception [`sintrop.InvalidKindError`](/api#sintrop.InvalidKindError).

For example:

```python
>>> import sintrop
>>> sintrop.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
```
