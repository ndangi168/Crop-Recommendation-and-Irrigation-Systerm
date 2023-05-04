# Crop-Recommendation-and-Irrigation-System-Using-Machine-Learning-Integrated-IoT-devices

## Abstract—
In agriculture, timely and efficient irrigation is crucial to achieve maximum crop yield. However, traditional methods of irrigation are often inefficient and wasteful, leading to water scarcity and abbreviated crop productivity. To address these issues, we propose a perspicacious irrigation system that integrates IoT contrivances and machine learning algorithms to recommend the most felicitous crop for a given region and provide optimal irrigation predicated on authentic-time weather conditions and soil moisture levels. The system accumulates data on soil nutrients, temperature, and sultriness utilizing IoT sensors and uses XGBoost, a popular machine learning algorithm, to recommend the most remuneratively lucrative crop predicated on historical data. The system additionally incorporates authentic-time weather data from APIs and water level sensors to provide customized irrigation for each crop. Our system aims to improve crop productivity, minimize water waste, and avail farmers make data-driven decisions to maximize their profits.
Keywords— Crop recommendation, Irrigation scheduling, Soil moisture sensors, Machine learning, Environmental conditions, Water conservation, Crop database, Weather data, Sustainable farming, Food security

## I. INTRODUCTION
India has a vast agricultural sector, with more than 1.6 million square kilometers of land area dedicated to cultivation, making it the second-largest in the world. Given that a significant proportion of the country's population is involved in agriculture, the economy is heavily dependent on this sector. India has the potential to become a superpower in the field of agriculture, which can promote rural development and reduce poverty.
Small farms dominate the agricultural landscape in India, with more than 75% of land holdings being less than 5 acres. The majority of crops rely on rainfall for nourishment, as only around 45% of the land is irrigated. Roughly 55% of India's population is estimated to depend on farming for their livelihood.
Unfortunately, there is no universal system in place to assist farmers in agriculture. India has a rich collection of agricultural data from the past, which can be utilized for recommendations using Machine Learning, Data Mining techniques and algorithms to recommend suitable crops, irrigation and predictions.
Agricultural practices today have undergone significant changes compared to those of past decades, largely due to advancements in technology. This includes the use of sensors, devices, machines, andinformation technology. Contemporary agriculture relies on sophisticated technologies such as robots, temperature and moisture sensors, GPS technology, aerial images, and various complex Internet of Things (IoT) devices. The implementation of these advanced devices in agriculture enables farmers and businesses to increase profitability, efficiency, safety, and environmental sustainability. The emergence of digital agriculture and its related technologies has created numerous opportunities for data collection. Remote sensors, cameras, and other connected devices can gather data on a 24-hour basis across an entire farm or land. This information can be used to monitor plant health, soil conditions, temperature, humidity, and more. The amount of data generated by these sensors is immense, providing farmers with a better understanding of their situation on the ground through advanced technology that can inform them more accurately and quickly. Indian agriculture is the backbone of the country's economy, employing millions of people and contributing significantly to the country's GDP. However, traditional farming practices often lead to suboptimal crop yield and inefficient irrigation, resulting in lower profits for farmers. To address these challenges, this paper proposes a Crop Recommendation and Irrigation System that leverages IoT contrivances and machine learning algorithms.
In this paper, we propose a Crop recommendation and irrigation system using IOT devices with integrated machine learning algorithms, specifically the Extreme Gradient Boosting (XGBoost) algorithm, and a weather API to forecast rain. Agriculture is a crucial sector of any country's economy, but farmers face several challenges such as unpredictable weather, inadequate irrigation, and pests and diseases. These challenges often lead to lower crop yields and reduced profits. The proposed system provides farmers with real-time data about the farm environment, crop growth, and soil moisture, enabling them to make data-driven decisions about irrigation and crop management.
The system utilizes IOT devices such as soil moisture sensors, temperature sensors, water level sensor, humidity sensors, and a weather API to collect real-time data. Adscititious, the system integrates a weather API to forecast rain, which avails optimize the irrigation system and preserve electrical energy and dihydrogen monoxide. The system provides farmers with recommendations about irrigation, crop management, and soil health, availing them to optimize crop yield and abbreviate dihydrogen monoxide utilization. The XGboost algorithm is used to analyze the collected data and provide recommendations to farmers on irrigation and crop management. The system also provides alerts to farmers when rain is detected, helping them to optimize irrigation and reduce water usage.
The system's accuracy was tested against manual recommendations, and it showed an improved accuracy rate.
The Crop recommendation and irrigation system using IOT devices with integrated machine learning algorithms presented in this paper has the potential to revolutionize the agricultural sector by providing farmers with real-time data-driven recommendations for irrigation and crop management.
Overall, the system offers a cost-effective and efficient solution to address the challenges faced by farmers and has the potential to revolutionize the agriculture sector.

## II. PROPOSED METHODOLOGY  
The proposed method for the Crop recommendation and irrigation system using IOT devices with integrated Machine learning involves the collection of soil parameters such as NPK levels, humidity, temperature, and soil moisture using sensors. These sensor values are transmitted to the Arduino microcontroller, which serves as a central control unit for the system, which is connected to a relay module. Arduino which serves as a central control unit for the system. The Arduino board communicates with a relay module, which acts as an interface between the sensors and the machine learning model. The relay module is responsible for executing the crop recommendation part of our system, which is done using a Machine Learning model trained on historical crop yield data. The model makes use of the collected sensor data to suggest the best- suited crop for the current season.
The machine learning model, which uses the XGBoost algorithm, recommends the most suitable crop based on the collected soil data. The recommended crop information is then sent to the cloud for further processing. The machine learning algorithm is then applied to the collected data to recommend suitable crops for the given soil parameters.
The recommended crop data is sent to the cloud, where it is processed and returned to the relay module. Based on the recommended crop, the system determines the irrigation requirements for each stage of crop growth. To determine the irrigation requirements, our system makes use of weather APIs, such as Meteum AI, to obtain the necessary weather data. This information is then combined with the sensor data collected by the IoT devices to determine the optimal irrigation schedule and volume of water required. The weather API is used to collect real-time weather data, which is used along with the sensor data to determine if irrigation is required and the amount of water required for the crop. The irrigation process is then initiated using a motor, which is controlled by the relay module. This allows for precise control over the amount and timing of the irrigation, resulting in optimal water usage and crop yield.
The irrigation is carried out using a motor controlled by the relay module, which provides precise amounts of water to the crops at different growth stages. This system ensures that the crops receive optimal irrigation, leading to improved yields and reduced water wastage. The proposed method provides an efficient and effective solution to optimize crop growth and ensure maximum yield, thereby contributing to the improvement of agriculture in India.
The technical details of each device used is give as follows:
# Crop-Recommendation-and-Irrigation-Systerm
