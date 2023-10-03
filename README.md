# Angela Halsten 10/3/23

# Module07_Netflix
Netflix.csv filed was pulled from https://www.kaggle.com/datasets/akpmpr/updated-netflix-stock-price-all-time

Netflix_Producer.py creates messages for Netflix stocks
If the closing price for tomorrow is 125% of the today, we buy (if we were psychic)
If the openening price today is 75% of tomorrow then we would sell (again, psychic)
If volume is 50% of yesterday's, we have a low volume alert (this almost makes sense)

Netflix_close_consumer gives the Buy Netflix message
Netflix_open_consumer gives the Sell Netflix message
Netflix_volume_consumer gives the low volume message

Picture of all 4 files running
![Alt text](<Screenshot 2023-10-03 154531.png>)
Buy Netflix alert
![Alt text](<Screenshot 2023-10-03 154559.png>)
Sell Netflix Alert
![Alt text](<Screenshot 2023-10-03 154619.png>)
Low Volume Alert
![Alt text](<Screenshot 2023-10-03 154638.png>)