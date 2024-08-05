![Cover](https://github.com/user-attachments/assets/8daf6018-1204-4bac-bec7-bfe38fa229b9)
# ABSTRACT
The study focuses on the application of clustering techniques to analyze bag-of-words data derived from Disneyland guest feedback, highlighting the challenges and strategies in handling such data for meaningful insights.  

Clustering revealed top strengths such as good customer service, good food, an efficient fast pass system, and great attractions, among others. For areas of concern, the main issue, as expected, is the queuing time for rides and attractions. Other sentiments include rude staff and cast members, expensive price points, closed attractions, and small facilities. Additionally, an interesting insight that the analysis revealed is that each branch has different areas of concern to prioritize. For example, Hong Kong Disneyland seems to fail in meeting guest expectations regarding the size of their amusement park. Disneyland Paris, on the other hand, struggles with poor customer service. California, on the other hand, has some issues with its Fast Pass implementation.
# DATASET
This dataset was imported from Jojie's Public Data Repository. The dataset is named disneyland-reviews. Table 1 shows the features, corresponding to the columns of the csv file.

| Feature           | Type    | Description                                         |
|-------------------|---------|-----------------------------------------------------|
| Review_ID         | integer | Identification number of the review.                |
| Rating            | integer | Numerical rating of the review (from 1-5).          |
| Year_Month        | string  | Year and Month of the review submission (yyyy-mm format). |
| Reviewer_Location | string  | Country of origin of the reviewer.                  |
| Review_Text       | string  | Text that contains the review.                      |
| Branch            | string  | Disneyland Branch which is the subject of the review. |


# METHODOLOGY
![Method](https://github.com/user-attachments/assets/72dcf9fa-2b83-415c-8a54-22b6a91e157d)

# RESULTS
![Clusters](https://github.com/user-attachments/assets/251adb65-aceb-4530-8fcf-64f14685d25a)
![image](https://github.com/user-attachments/assets/631a31c0-f2ab-4d0b-99ab-e67e2f3e2447)
![image](https://github.com/user-attachments/assets/46caf15a-84d1-4711-81fa-bd6cb4d63d6c)

# RECOMMENDATIONS
## Disneyland California
#### Ride Times Optimization:
The sheer number of visitors in Disneyland California leads to long queues for attractions. Management may use real-time data to provide queue predictions and predict peak times.

#### Manage Fast Pass Limit:
Disneyland management should perform a balancing act on the fast pass system. Too much fast pass usage aggravates visitors who do not use them, but foregoing implementation of fast pass deprives the Fast Pass enthusiast of the convenience.

#### Queue Entertainment:
Since the problem of long queues is really a capacity, one approach is to make queue a bit less hectic. Management can deploy entertainment near queueing sites such as parades, or cast members that entertain guests that are currently queueing.

#### Improve Queueing Comfort:
The least an amusement park could to to appease queueing guests is to make queueing comfortable. There are numerous complaints that expressed discomfort specially when queueing under the sun, simple accomodations such as shades in the form of structures or perhaps more trees could be a good idea. Improved ventilation and seated queues, if feasible, can also be explored.

## Disneyland Hong Kong
#### Explore Possible Expansions
Since the main concern for Disneyland Hong Kong is the size of the amusement park as a whole, an expansion might be a good idea. Although this option is for a long term strategy, and it is highly dependent on feasibility. In the event that it is not possible, the park may opt to improve the quality of attractions instead of prospecting expansion, basically to do and offer more with the limited size of their park.

#### Reconfigure Pricing Strategy
The market of Disneyland Hong Kong might be different for its western counterparts, the amount of money their market is willing to spend lower. Disneyland Hongkong could try to re evaluate their pricing models and consider offering seasonal discounts as long as the increase in guests translate to a net increase in profits.

## Disneyland Paris
Improve Fast Pass Marketing
Disneyland Paris experiences the worst feedback in terms of long queues. Another observation is that there is not much complaints against the fast pass system and consequently Fast Pass advantage is also not the strength of Disneyland Paris. This means that despite long lines, people still forego the usage of the Fast Pass system. Marketing the Fast Pass better in ways such as increasing awareness and educating guests on how to use it can improve overall customer experience.

#### Additional Staff Training
Prominently, guests comment on Disneyland Paris' poor customer service. Management may opt to address the staff of this issue and implement additional trainings on how to effectively treat customers. This can be combined with incentivization if the budget permits, incentivize or penalize staff that are proven to be rude to staff.

#### Maintenance Optimization
Disneyland Paris has the highest proportion of reviews alluding to closed attractions. Management should try to reassess the park's maintenance plan to avoid unexpected breakdowns. Implement proper preventive maintenance to make sure that maintenance is done on off peak seasons, or better when the park is closed.

#### Customer Communication
Maintenance and refurbishments that results in the temporary closure of attractions can be communicated better to prospect guests. This can allow guests to be flexible in planning their time of visit, specially if they are looking forward to a particular attraction. This can results to better customer experience and consequently better feedback.
