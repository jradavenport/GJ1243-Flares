# GJ1243-Flares
This is the full catalog of 6107 flare events from 11 months of short cadence Kepler data from [Davenport et al. (2014)](http://arxiv.org/abs/1411.3723) - the largest uniform sample of flares on a single star to date.




## Catalog Info
The repository contains both the [catalog of flares](data/gj1243_master_flares.tbl) and the corresponding 11-month [light curve](data/gj1243_master_slc.dat). These are the columns saved for every flare in the catalog:

```
# ----- Columns: -----
# index of flare start in "gj1243_master_slc.dat"
# index of flare stop in "gj1243_master_slc.dat"
# t_start
# t_stop
# t_peak
# t_rise
# t_decay
# flux peak (in fractional flux units)
# Equivalent Duration (ED) in units of per seconds
# Equiv. Duration of rise (t_start to t_peak)
# Equiv. Duration of decay (t_peak to t_stop)
# Complex flag (1=classical, 2=complex) by humans
# Number of people that identified flare event exists
# Number of people that analyzed this month
# Number of flare template components fit to event (1=classical >1=complex)
```


### Citation
If you use this dataset, please cite our published paper: [Davenport et al. (2014)](http://arxiv.org/abs/1411.3723)


### See Also

- [FBEYE](https://github.com/jradavenport/FBEYE) - an IDL based flare-finding suite
- [flare-fit](https://github.com/jradavenport/flare-fit) - IDL code to deconstruct complex flare events