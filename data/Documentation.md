Here we include three versions of the data: raw, processed and external/third party if possible.

**Raw**: Data gathered from Kaggle pulled directly from NASA's data repo

**Processed**: Final data for modeling - cleaning, transformations, and the like done

**External**: If possible, this will be examined down the line from a third party to compare the data's integrity against an outside source

## Data Dictionary

| Variable name | Variable description | Notes | Imputation |
|---------------|----------------------|-------|------------|
| a (AU) | Semi-major axis of the orbit in AU | AU = Astronomical unit is a unit of length equal to 149,597,870.7KM | None |
| e | Eccentricity of the orbit | How circular orbit is (0 is a circle, higher values are less circular) | None |
| i (deg) | Inclination of the orbit with respect to the ecliptic plane and the equinox of J2000 (J2000-Ecliptic) in degrees | Measures the tilt of the Earth's orbit around the sun | None |
| w (deg) | Argument of perihelion (J2000-Ecliptic) in degrees | rotation angle around focus of the sun's closest point to the earth's orbit | None |
| Node (deg) | Longitude of the ascending node (J2000-Ecliptic) in degrees |  | None |
| M (deg) | Mean anomoly at epoch in degrees |  | None |
| q (AU) | Perihelion distance of the orbit in AU |  | None |
| Q (AU) | Aphelion distance of the orbit in AU |  | None |
| P (yr) | Orbital period in Julian years |  | None |
| H (mag) | Absolute V-magnitude |  | None |
| MOID (AU) | the minimum distance between the osculating orbits of the NEO and the Earth |  | None |
| class | asteroid orbit classification |  | None |
