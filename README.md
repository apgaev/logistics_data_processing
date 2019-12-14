# logistics_data_processing
Data processing R Shiny app for further machine learning algorithms application

It is consisted of modules that handle:
- cargo type (transfers everything that was written by logisticians into groups defined by user using mostly gsub and grepl functions)
- vehicle type (copy of the module represented above with another specifics)
- counterparties (adjusts filters for deliveries made by certain companies)
- addresses (changes addresses written by logisticians with all possible grammar mistakes into defined coordinates)
