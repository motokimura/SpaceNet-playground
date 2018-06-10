# SpaceNet-playground
Experiments to preprocess [SpaceNet](http://explore.digitalglobe.com/spacenet) satellite imagery data corpus to a format that is consumable by machine learning algorithms.

## Dependencies

- [GDAL](http://www.gdal.org/) (tested with 2.1.3)
- [libspatialindex](http://libspatialindex.github.io/) (tested with 1.8.5)
- Python packages listed in [requirements.txt](requirements.txt)

## [Demo #1] Building footprints

Download instructions for the SpaceNet building footprint dataset can be 
found [here](https://github.com/SpaceNetChallenge/utilities/tree/master/content/download_instructions) 
and [here](https://spacenetchallenge.github.io).

### Building outline

<img src="contents/building_outline.png" />

See [this notebook](src/building/plot_truth_coords.ipynb) for details.

### Building mask

<img src="contents/building_mask.png" />

See [this notebook](src/building/plot_building_mask.ipynb) for details.

### Building bounding box

*Comming soon..*

# License

[MIT License](LICENSE)
