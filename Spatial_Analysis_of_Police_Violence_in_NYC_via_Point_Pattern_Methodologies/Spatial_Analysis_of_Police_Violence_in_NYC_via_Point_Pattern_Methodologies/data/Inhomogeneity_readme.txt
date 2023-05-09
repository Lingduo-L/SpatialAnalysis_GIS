Kernel_by_rate: The kernel result from the NYC_case_per_pop, selecting the "population_filled" as the population field.
Kernel_pop: Kernel result created from the NYC_census_point, selecting the "population_filled" as the population field.
Kernel_pop_den: Kernel result created from the NYC_census_point, selecting the "pop_den_filled" as the population field.
Usage: Kernel_pop and Kernel_pop_den are kernel density results created using population data and population density, respectively. They can be compared to the FE kernel after division to determine which is more suitable.
NYC_case_per_pop: Data obtained by spatially joining the FE case to the census tract, converting polygon to point, and deleting points with a count of 0.
NYC_census_point: The result of converting the NYC_census_tract polygon to points.