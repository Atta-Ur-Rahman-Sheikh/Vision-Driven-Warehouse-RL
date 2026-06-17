# Vision-Driven-Warehouse-RL

Vision-Driven Deep Reinforcement Learning for Dynamic Warehouse Task and Robot Allocation (ICL 2026).

## Notebooks

| File | Purpose |
|---|---|
| `vision_warehouse_rl.ipynb` | Kaggle-ready study notebook (fixed) |
| `rl-based-warehouse-task-allocation-study.ipynb` | Same notebook (working copy) |
| `build_fixed_notebook.py` | Regenerate notebook after edits |

## Kaggle setup

1. Add dataset: [warehouse-operation-dataset](https://www.kaggle.com/datasets/srvydv1234567/warehouse-operation-dataset)
2. Upload `vision_warehouse_rl.ipynb`
3. Enable GPU (recommended for DQN training)
4. Run All -> download `vision_warehouse_rl_outputs.zip`

## Regenerate locally

```bash
python build_fixed_notebook.py
```
