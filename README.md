# py-feature-sequences

GeoJSON feature sequences for Python

## GeoJSON feature sequences

Feature sequences are described at 
https://github.com/geojson/geojson-feature-sequences.

This project aims to extract the implementation in Fiona's fio-collect
command (see 
https://github.com/Toblerity/Fiona/blob/master/fiona/fio/cat.py#L166) and 
generalize it for wider use.

## Usage

No code has been written yet, but the proposed usage is something like the
following.

```python
from geojseq import FeatureSequenceReader

for feature in FeatureSequenceReader(open('example.seq')):
    print feature
    # output: {'type': 'Feature', ...}
```
