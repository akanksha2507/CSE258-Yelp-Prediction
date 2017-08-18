# CSE-258-Yelp-prediction
Can you figure out which restaurant a user is likely to go to next? In this prediction task, we assume reviewing the restaurant to be akin to going to a restaurant.

#### File descriptions
1. YelpDataPreprocessing.ipynb : manages all data preprocessing and generated the required JSON subset of data

Useful files generated as a part of pre-processing:
1. yelp_restaurant_data.json : subset of yelp_academic_dataset_business.json pertaining to restaurants. (size: 56 Mb)
2. yelp_user_review_data: subset of yelp_academic_dataset_review.json pertaining to reviews of restaurants. (size: 2.0 Gb)
3. yelp_user_data: data from yelp_academic_dataset_user.json without the social circle information. (size: 138 Mb) Useful if you don't need the social circle details, file size reduced from 1.1Gb to 138 Mb)
4. yelp_restaurant_Ui.json: constructs the set of users who have reviewed each restaurant (size: 65 Mb)
5. yelp_user_Iu.json: constructs the set of restaurants reviewed by each user (size: 83 Mb)
6. yelp_user_IuVegas.json : specific to Vegas data