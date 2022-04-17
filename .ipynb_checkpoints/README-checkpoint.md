## Nguồn dữ liệu
Dataset nhóm sử dụng 
[COVID-19 dataset
Dataset coronavirus pandemic](Link dataset: https://www.kaggle.com/datasets/georgesaavedra/covid19-dataset)

Nhóm sẽ phân tích tình hình dịch bệnh covid-19 dựa trên số ca mắc, số ca tử vong và số lượng người đã tiêm phòng vaccine và đưa ra
các nhận xét.

File dữ liệu: owid-covid-data.csv

Hình thái dữ liệu gồm: 166327 quan sát, 67 cột

## Giải thích các biến

Một số biến chính sẽ được nhóm sử dụng từ tập dataset 

### Ca mắc
|Biến                               |Mô tả
|:----------------------------------|:--------------------------------------------------------------------------|
|`total_cases`                      |Tổng số ca mắc covid 19 đã được xác nhận                                   |
|`new_cases`                        |Số ca mắc mới covid 19 đã được xác nhận                                    |
|`new_cases_smoothed`               |Số ca mắc mới covid 19 được xác nhận (7 ngày làm mới)                      |
|`total_cases_per_million`          |Tổng số ca mắc covid 19 đã được xác nhận trên 1,000,000 người              |
|`new_cases_per_million`            |Số ca mắc mới covid 19 đã được xác nhận trên 1,000,000 người               |
|`new_cases_smoothed_per_million`   |Số ca mắc mới covid 19 được xác nhận (7 ngày làm mới) trên 1,000,000 người |

### Ca tử vong
|Biến                               |Mô tả
|:----------------------------------|:----------------------------------------------------------------------------------|
|`total_deaths`                     |Tổng số ca covid 19 tử vong đã được xác nhận                                       |
|`new_deaths`                       |Số ca covid 19 tử vong mới đã được xác nhận                                        |
|`new_deaths_smoothed`              |Số ca covid 19 tử vong mới đã được xác nhận (7 ngày làm mới)                       |
|`total_deaths_per_million`         |Tổng số ca covid 19 tử vong đã được xác nhận trên 1,000,000 người                  |
|`new_deaths_per_million`           |Số ca covid 19 tử vong mới đã được xác nhận trên 1,000,000 người                   |
|`new_deaths_smoothed_per_million`  |Số ca covid 19 tử vong mới đã được xác nhận (7 ngày làm mới) trên 1,000,000 người  |

### Vaccine
|Biến                               |Mô tả
|:----------------------------------|:-----------------------------------------------|
|`total_vaccinations`               |Tổng số liều vaccine                            |
|`people_vaccinated`                |Tổng số người tiêm ít nhất một mũi vaccine      |
|`people_fully_vaccinated`          |Tổng số người tiêm đủ liều vaccine theo quy định|

### Các biến khác
|Biến                               |Mô tả
|:----------------------------------|:------------|
|`continent`                        |Châu lục     |
|`location`                         |Tên nước     |
|`date`                             |Ngày quan sát|
|`population`                       |Tổng dân số  |
|`population_density`               |Mật độ dân số|