# UFO
## Project Overview
The purpose of this analysis was to create a website presenting data about UFO spotting and to allow users easy filtering.

## Results
At the beginning, the website displays whole table with all availble UFO sightings.  
[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/web-overview.png]

By putiigng the filtering criteria in left column "Filter search" one can provide custom input data to narrow down the presented tabel. 
Filtering criteria should be provided in here:
[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/graph1.png]

One can put multiple criteria at ones, like date of the sighting:
[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/putting_date.png]

.... state.....

[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/putting_state.png]

.... and for instance shape.

[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/putting_shape.png]

After hitting enter the table will be filtered based on provided cirteria like this:

[!image https://github.com/beata-malachowska/UFO/blob/main/static/images/filtered_table.png]

###Summary 
Two drawback: users don't know from which criteria then can choose from and they can't search through last two columns.
Solutions: drop-down list should be available with filtering criteria instead of direct input; "Duration" column should be cleaned and for "Comments" column regex search should be made available. 
