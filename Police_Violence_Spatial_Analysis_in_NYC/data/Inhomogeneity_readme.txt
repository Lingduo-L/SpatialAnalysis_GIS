Kernel_by_rate: the kernel result from the NYC_case_per_pop, selecting the "population_filled" as the population field
Kernel_pop: kernel result created from the NYC_census_point, selecting the "population_filled" as the population field
Kernel_pop_den: kernel result created from the NYC census_point, selecting the "pop_den_filled" as the population field
用法：Kernel_pop和Kernel_pop_den分别用人口数据和人口密度做的kernel density, 可以和FE的kernel相除之后比较哪个更合适。
NYC_case_per_pop: 将FE case spatial join到census tract上，面专点，再删除count=0的点得到的数据
NYC_census_point: 将NYC_census_tract面专点得到的结果