# Core API

## robosafe.load_dataset

```python
def load_dataset(split: str) -> Dataset:
    """
    Load dataset.
    
    Args:
        split: Dataset split ("train", "val", "test")
    
    Returns:
        Dataset object
    """
```

## robosafe.train

```python
def train(dataset: Dataset, config: Config) -> Model:
    """Train a model."""
```
