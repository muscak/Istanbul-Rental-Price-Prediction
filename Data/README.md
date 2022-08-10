[Kaggle Link](https://www.kaggle.com/datasets/mgunerengineer/istanbul-rent-flat-data)

1. 'Unnamed: 0' is index and should be removed.
2. 'title' is the title of the ad shown on sahibinden.com.
3. 'area' is the size of the apartment in square meter.
4. 'numberOfRooms' is the number of rooms in the apartment. It's in x+y format where x is the number of bedrooms and y is the number of living room. It has 26 unique value and the most used is 2+1.
5. 'price' is the monthly rental fee in Turkish Liras (TL). It is in object format which should be fixed to numerical.
6. 'town' is the place of the flat in Istanbul. It has 131 unique values and most of the flats for rent are in Halkali.
7. 'district' is the place of the flat in that 'town'. This feature has almost 1000 missing values.
