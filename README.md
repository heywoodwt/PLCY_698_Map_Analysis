# NC Coastal & Flood Hazard Mapping

Geospatial layer for the Environmental Defense Fund disaster relief analysis — mapping
flood and coastal hazard exposure across North Carolina counties in R.

Works with FEMA and NC state shapefiles covering base flood elevations, coastal barrier
resource systems, coastal transects, survey benchmarks, and county boundaries, and
renders them against the relief funding data.

## Data layers

| Layer | Source |
|-------|--------|
| `Base_Flood_Elevations__FT_` | Modeled base flood elevation in feet |
| `Coastal_Barrier_Resource_Systems` | Federally designated coastal barrier units |
| `Coastal_Transect` | Coastal analysis transects |
| `Benchmarks` | Survey control points |
| `CaldwellCounty` | County boundary |

Each layer is a standard ESRI shapefile set (`.shp`/`.dbf`/`.shx`/`.prj`).

## Running it

```r
install.packages(c("sf", "tidyverse", "tmap"))
```

Companion to [Flood_Analysis_PLCY_698](https://github.com/heywoodwt/Flood_Analysis_PLCY_698).

## License

MIT
