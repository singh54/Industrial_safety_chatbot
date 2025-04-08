# Project Name
> Design a ML/DL based chatbot utility which can help the professionals to highlight the safety risk as per the incident description.







## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The database comes from one of the biggest industries in Brazil and the world. Industries and companies around the globe urgently need to understand why employees still suffer injuries and accidents in plants. Sometimes, they also die in such an environment.

- To help professionals before going to work to understand the safety risk on particular task.
- Identify the risk level in industry with the help of work description.
- This database is basically records of accidents from 12 different plants in 03 different countries where every line in the data is an occurrence of an accident.
- Columns description:
- Data: timestamp or time/date information
- Countries: which country the accident occurred (anonymised)
- Local: the city where the manufacturing plant is located (anonymised)
- Industry sector: which sector the plant belongs to
- Accident level: from I to VI, it registers how severe was the accident (I means not severe but VI means very severe)
- Potential Accident Level: Depending on the Accident Level, the database also registers how severe the accident could have been (due to other factors involved in the accident)
- Genre: if the person is male of female
- Employee or Third Party: if the injured person is an employee or a third party
- Critical Risk: some description of the risk involved in the accident
- Description: Detailed description of how the accident happened.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Gradient Boosting emerged as the best performer, achieving a test accuracy of 92.03% with perfect training accuracy (95%). This highlights its strong ability to handle the increased dataset size and complexity augmentation introduced.
- Address class imbalance using oversampling, undersampling, or class weights.
- Validate the quality and representativeness of embeddings and categorical features.
- Evaluate the model on more granular metrics per class to better understand its performance.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Colab Notebook
- Pandas and Numpy
- Natural language processing
- words embeddings
- Chatbot GUI library

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...Industrial safety



## Contact
Created by [@singh54] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
