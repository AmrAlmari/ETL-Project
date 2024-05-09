# ETL-Project


## 1 - Extract

- Scrapes data from [Auction Export](https://www.auctionexport.com).
- Extracts the following fields of interest:
    - Vin_no
    - Make
    - Model
    - Year
    - Mileage
    - Exterior_Color
    - Drivetrain
    - Engine
    - Transmission
    - Sale_Doc
    - Keys	
    - Lot_no	
    - Time_Left	
    - Sale_End_Date	
    - Location

## 2 - Transform

- Cleans and transforms the extracted data.
- Integrates the transformed data.

## 3 - Load

- Creates a MySQL database and respective tables to match the columns of the final pandas DataFrame.
