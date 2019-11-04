# brick-examples
A collections of examples for Brick

# Changes from original
1. haystack/ghausi-improved.json
  - The original Ghausi version did not have FCU's tagged with the appropriate 'fcu' tag
  - The original Ghausi version did not have point tags on any of the 'sensor', 'cmd', or 'sp' point types
  - The original Ghausi version had 4 overlapping 'sensor' and 'cmd' points (should be mutually exclusive).  Based on all four points being related to 'Pump Speeds', the 'sensor' tag was removed and only the 'cmd' tag left
  - Tags on the entities were modified using the script [here](https://github.com/corymosiman12/building_graphs/blob/master/scripts/update_ghausi.py)
