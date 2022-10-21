# LSE_DA_NHS_analysis

Assignment activity 2

The actual_duration data set has 137,783 rows and 8 columns.

Based on the shape and null value counts, it appears that there are no missing or null values.

The actual_duration data set consist of 2 data types: object ('sub_icb_location_code', 'sub_icb_location_ons_code', 'sub_icb_location_name', 'icb_ons_code', 'region_ons_code', 'appointment_date', 'actual_duration') and integer.('count_of_appointments')

The appointments_regional data set has 596,821 rows and 7 columns.
Based on the shape and null value counts, it appears that there are no missing or null values.

The appointments_regional data set consist of 2 data types: object ('icb_ons_code', 'appointment_month', 'appointment_status', 'hcp_type', 'appointment_mode', 'time_between_book_and_appointment') and integer.('count_of_appointments')

The national_categories data set has 817,394 rows and 8 columns.

Based on the shape and null value counts, it appears that there are no missing or null values.

The appointments_regional data set consist of 3 data types:-

1) object: 'appointment_date', 'icb_ons_code', 'sub_icb_location_name', 'service_setting', 'context_type', 'national_category', 'appointment_month'

2) integer: 'count_of_appointments'

3) datetime64[ns]: 'appointment_date'

How many locations are there in the data set?

The number of locations in the data set is: 106.

What are the five locations with the highest number of records?

The 5 locations with the highest number of records are: 

NHS North West London ICB - W2U3Z              13007

NHS Kent and Medway ICB - 91Q                  12637

NHS Devon ICB - 15N                            12526

NHS Hampshire and Isle Of Wight ICB - D9Y0V    12171

NHS North East London ICB - A3A8R              11837

How many service settings, context types, national categories, and appointment statuses are there?

 There are 5 service settings.

 There are 3 context types.
 
 There are 18 national categories.

 There are 3 appointment statuses.




