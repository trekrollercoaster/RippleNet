# RippleNet-datafile

The data files for [RippleNet](https://github.com/tezignlab/RippleNet)

### Files in the folder

- `data/`
  - `book/`
    - `BX-Book-Ratings.csv`: raw rating file of Book-Crossing dataset;
    - `item_index2entity_id.txt`: the mapping from item indices in the raw rating file to entity IDs in the KG;
    - `kg.txt`: knowledge graph file;
  - `movie/`
    - `item_index2entity_id.txt`: the mapping from item indices in the raw rating file to entity IDs in the KG;
    - `kg_part1.txt` and `kg_part2.txt`: knowledge graph file;
    - `ratrings.dat`: raw rating file of MovieLens-1M;

### How to use

```
$ git clone https://github.com/trekrollercoaster/RippleNet/tree/datafile
```

Put 'data' file under 'RippleNet' root folder.