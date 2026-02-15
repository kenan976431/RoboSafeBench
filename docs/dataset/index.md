# Dataset

## Overview

The dataset contains...

## Statistics

- Trajectories: 100,000+
- Objects: 200+
- Tasks: 80+

## Download

```bash
# Download dataset
robosafe download --split train
```

## Data Format

```python
episode = {
    "rgb": np.array(...),
    "actions": np.array(...),
    "states": np.array(...)
}
```
