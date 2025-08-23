# Public-Transit-Delay-Prediction-System
ML project to predict bus/metro delays using traffic, weather, time, distance &amp; passenger data. Supports classification (delay/no delay) &amp; regression (delay duration) with Logistic Regression &amp; Gradient Boosting to improve scheduling &amp; commuter experience.                                                    .

| Column Name             | Description                                                                      |
| ----------------------- | -------------------------------------------------------------------------------- |
| **trip\_id**            | Unique identifier for each trip (1 → n).                                         |
| **route\_id**           | Bus/train route ID (random between 1–50).                                        |
| **time\_of\_day**       | Time category when trip started (`Morning`, `Afternoon`, `Evening`, `Night`).    |
| **day\_of\_week**       | Day on which the trip occurred (`Mon–Sun`).                                      |
| **traffic\_level**      | Traffic conditions during the trip (`Low`, `Medium`, `High`).                    |
| **weather**             | Weather condition (`Clear`, `Rain`, `Snow`, `Fog`).                              |
| **scheduled\_duration** | Scheduled trip duration in minutes (10–90).                                      |
| **distance\_km**        | Trip distance in kilometers (2–30).                                              |
| **num\_passengers**     | Number of passengers onboard (10–120).                                           |
| **delay\_minutes**      | Actual delay in minutes (calculated, clipped 0–60).                              |
| **delay\_flag**         | **Target column** → Binary indicator (1 if delayed more than 5 minutes, else 0). |

