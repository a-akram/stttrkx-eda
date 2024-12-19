# stttrkx-eda

All notebooks that are either intended for EDA or Visualization are moved from `stttrkx` repo to `stttrkx-eda` (or `stttrkx-viz`). This is done to reduce the clutter in `stttrkx`.

The idea is to create a symlink of `stttrkx-eda` at the root of `stttrkx` so `src` becomes available for running notebooks. Hence, `src` is not copied here.

On linux, one can use `ln` command to create a symlink:

```bash
# symlink `stttrkx-eda` as `eda` at the root of `stttrkx`
cd to stttrkx/
ln -s path/to/stttrkx-eda eda
```
