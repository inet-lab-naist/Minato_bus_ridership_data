# Bus Ridership Data
## About
This data is collected by the docor system operated by Minato Kanko Bus Inc.
For more information on the docor system, see [this Paper](https://ieeexplore.ieee.org/abstract/document/9221027).
This data is available in monthly CSV for each inbound and outbound route.

Each route directory includes files, `2021/**.csv` or `2022/**.csv` as **monthly data files** and `bus_stops.csv` as **bus stop data file**.
Each file information is described as follows.

### Monthly data files
Each file contains data for each month.
Each file includes `date`, `boarding_count`, `alighting_count`, `passenger_count`, `service_number`, and `bus_stop_id` columns.
- `date`: collected date
- `boarding_count`: the number of boarding passengers
- `alighting_count`: the number of alighting passengers
- `passenger_count`: the number of passengers on the bus at the time of bus stop departure
- `service_number`: bus service number
- `bus_stop_id`: bus identification number (This column is linked to the `bus_stop_id` column in the bus stop data file.)

### Bus stop data file
This file includes `bus_stop_id`, `bus_stop_name`, `bus_stop_name_ja`, and `bus_stop_order` columns.
- `bus_stop_id`: bus identification number (This column is linked to the `bus_stop_id` column in the monthly data file.)
- `bus_stop_name`: bus stop name in English notation
- `bus_stop_name_ja`: bus stop name in Japanese notation
- `bus_stop_order`: bus arrival order in this route

## Contact
If you would like to know more, please contact [inet-lab](https://inet-lab.naist.jp/en/).