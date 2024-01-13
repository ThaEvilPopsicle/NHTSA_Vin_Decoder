# NHTSA Vin Decoder
Vin Decoder that utilizes the NHTSA Vehicle API to return Vin information in batch. You can find more information on the API here: https://vpic.nhtsa.dot.gov/api/.

Code will pass vins in groups of 10 to the Vehicle API and will concatenate the results into an object. From there you can export to a file or write to Snowflake with the code provided. 


