# GroupedNMS-
Often you want to run NMS over some pairs of classes, but not others which you expect to overlap. 

```python
predictions = grouped_nms(
  predictions,
  groups=[
  ['car','van','lorry'],
  ['dog','cat'],
])
```
