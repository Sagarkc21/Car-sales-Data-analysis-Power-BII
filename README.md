# Car-sales-Data-analysis-Power-BII
This is the project for power bi dashboard data analyzing using power bi

Things I learned from this projets:
 1.Time Intelligence function- Build date table separately:
 2. Learned to create the filters, charts, Navigation to different dashboard, and gain some business knowledge.
 -------For using the time intelligence function the date must be continious form.

 Some of the importanct formula that i leared are

  1.a   Total Sales =
SUM(car_data[Sales])

1.b YTD sales Year to date sales:

Sales YTD =
TOTALYTD(
    [Total Sales],
    'Calendar'[Date]
)

1.c Month to date sales =
TOTALMTD(
    [Total Sales],
    'Calendar'[Date]
)

1.d Sales LY last year =
CALCULATE(
    [Total Sales],
    SAMEPERIODLASTYEAR('Calendar'[Date])
)

Note : This is the guided project that i have completed via https://www.youtube.com/watch?v=uPkemycepLc&t=4889s 


