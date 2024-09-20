# IoT-based-Smart-Menstrual-Cup
An innovative project designed to track menstrual flow using IoT-based sensors and provide real-time health data to users via a mobile app. This project leverages data analysis and smart technology to offer insights into menstrual health.
Problem Statement & Objective
Problem Statement: Menstruators face several challenges related to tracking and understanding their menstrual health. The lack of real-time data on menstrual flow can lead to difficulties in detecting abnormalities, managing hygiene, and making informed decisions about personal health. Traditional methods for tracking menstrual flow, such as manually recording data, are often inaccurate and inconvenient, leading to gaps in understanding one’s menstrual cycle. Additionally, many menstruators lack access to personalized health insights, which can hinder the early detection of potential health issues like irregular cycles, heavy bleeding, or other conditions that require medical attention.

Objective: The objective of this project is to develop an IoT-enabled Smart Menstrual Cup that provides real-time monitoring of menstrual flow. By integrating sensors into the menstrual cup, this smart device will measure key health metrics such as flow rate and volume. The data collected will be transmitted to a mobile application, where users can visualize their menstrual patterns, receive notifications, and gain personalized health insights. The aim is to empower menstruators with accurate, real-time information, enhancing their ability to manage menstrual health and detect potential issues early. This innovative solution combines the benefits of IoT technology with data-driven insights to improve menstrual care and overall well-being.

Hardware Components
Menstrual Cup:

The menstrual cup serves as the physical base of the device. It is fitted with advanced sensors that monitor various parameters such as flow rate, volume, and duration of menstruation. The cup is designed to be comfortable and safe for daily use while seamlessly integrating the IoT technology for tracking menstrual data.
Sensors Used:

Capacitor Sensors: These sensors measure the rate at which menstrual fluid is collected in the cup, providing real-time data on menstrual flow.

#For future Scope

Pressure Sensors: Used to detect changes in pressure within the cup, helping estimate the volume of menstrual fluid and ensure that the cup does not overflow.
Temperature Sensors (Optional): Can be added to monitor body temperature, giving additional insights into the user’s health during menstruation.
Capacitive Sensors: These sensors can detect fluid levels within the cup and signal when it’s time for the user to empty the cup.
Microcontroller:

The microcontroller acts as the brain of the system, processing the data received from the sensors and preparing it for transmission. Popular options include:
Arduino: Ideal for its ease of use and compatibility with various sensors, providing basic control over the sensors and data collection.
Raspberry Pi: A more powerful option, offering greater processing capabilities and flexibility for advanced features like local data storage and initial data analysis.
Bluetooth/Wi-Fi Module:

For wireless communication between the menstrual cup and the mobile app Kamakhya, a Bluetooth or Wi-Fi module is essential. It enables the transmission of sensor data to the app for real-time monitoring and visualization.
Bluetooth Module: Ensures a low-power, close-range connection between the menstrual cup and the mobile device.
Wi-Fi Module (Optional): Can be used for cloud-based data storage and analytics, allowing the user to access their menstrual data from any location.
These hardware components work together to form a complete, smart menstrual health solution, providing real-time insights into menstrual flow through the Kamakhya mobile app.

Dashboard for Data Visualization
The Kamakhya mobile app integrates a user-friendly dashboard designed to present real-time and historical data on menstrual flow, offering valuable insights through intuitive charts and graphs. This dashboard is built using data visualization tools like Power BI and Tableau, ensuring that users can easily interpret the data collected from the IoT-enabled smart menstrual cup. Here’s how the dashboard is structured:

Home Screen:

The dashboard's home screen provides an overview of the user's menstrual cycle, highlighting key metrics such as:
Current Day’s Flow: Displays the real-time flow rate and volume of menstrual fluid collected so far.
Cycle Duration: Tracks how long the current cycle has lasted and estimates the remaining days based on previous cycles.
Charts and Graphs:

Flow Rate Over Time (Line Chart):
A dynamic line chart visualizes the flow rate throughout the day, helping the user track peak flow hours and overall consistency.
Daily Flow Volume (Bar Chart):
This chart shows the total volume of menstrual fluid collected each day, allowing the user to understand daily variations in flow.
Cycle Trends (Historical Data):
A time-series graph displays data across multiple cycles, helping users spot patterns such as heavy flow days, light days, and any irregularities.
Health Insights:

Heatmaps: Visualize flow intensity by hour or day, helping users detect patterns like heavier flow during the mornings or evenings.
Cycle Predictions: Using historical data, the app predicts the expected start and end dates of upcoming cycles, as well as expected flow intensity.
Alerts and Notifications:

Overflow Alerts: The dashboard provides real-time notifications if the cup is nearing capacity, helping users manage hygiene efficiently.
Irregular Cycle Detection: If the app detects deviations from typical flow patterns, such as unusually heavy or light periods, it alerts the user to consider consulting a healthcare provider.
Data Export and Sharing:

The app includes a feature that allows users to export their data in formats like CSV or PDF. This can be shared with healthcare professionals for further analysis.
Customizable Insights:

Users can customize their dashboard to prioritize the information most relevant to them. For example, they can choose to view a specific cycle’s data or compare trends over a set period.
By leveraging Power BI and Tableau, the Kamakhya app offers detailed visualizations that empower users to monitor their menstrual health more effectively, providing actionable insights through interactive dashboards.

Future Scope and Enhancements
The IoT-Enabled Smart Menstrual Cup project has the potential for significant advancements in both hardware and software, ensuring a more comprehensive solution for menstrual health management. Below are some possible future upgrades:

1. More Advanced Sensors:
Biochemical Sensors: Future versions of the cup could integrate biochemical sensors to detect hormone levels (e.g., estrogen, progesterone) in the menstrual fluid. This could provide deeper insights into reproductive health, including ovulation tracking and detection of hormonal imbalances.
pH and Microbial Sensors: Incorporating sensors to monitor pH levels and detect microbial presence could help identify infections or potential imbalances in vaginal health.
Temperature and Humidity Sensors: Additional sensors could monitor changes in body temperature or the environment inside the cup, providing further data on overall menstrual health and potentially detecting early signs of infection or inflammation.
2. Improved Mobile App Features:
Symptom Tracking: Enhance the app to allow users to log symptoms such as cramps, headaches, or mood changes. This data can be correlated with the menstrual flow patterns to offer personalized health advice.
AI-Driven Health Insights: Use AI and machine learning algorithms to provide more accurate health predictions and personalized recommendations, such as diet or lifestyle changes to ease period-related symptoms.
Integration with Wearables: Sync the app with wearable devices (e.g., fitness trackers) to provide a holistic view of the user’s overall health, such as sleep patterns, activity levels, and menstrual health, in one interface.
3. Better Predictive Models:
Cycle Irregularity Detection: Future iterations could incorporate more sophisticated machine learning models that better predict cycle irregularities based on historical data. This could help detect early signs of conditions such as polycystic ovary syndrome (PCOS) or endometriosis.
Predictive Analytics for Fertility: Improve predictive models to offer fertility insights based on patterns in menstrual flow, hormone data, and body temperature, which could help users understand their ovulation cycle more accurately.
Menstrual Health Risk Assessment: Develop algorithms that assess the risk of menstrual health issues, such as heavy menstrual bleeding (menorrhagia) or conditions like fibroids, based on long-term trends in menstrual flow.
4. Cloud-Based Data Storage and Analytics:
Personalized Health Dashboard: Cloud integration could allow users to store data securely and access it across multiple devices. Users could also share this data with healthcare professionals, enabling more personalized healthcare recommendations.
Aggregated Data for Research: Anonymized menstrual data from multiple users could be aggregated and analyzed for research purposes, helping to advance scientific understanding of menstrual health and related conditions.
5. Sustainability and Eco-Friendly Design:
Reusable and Eco-Friendly Materials: Future designs could focus on making the cup more sustainable by using fully biodegradable materials or improving the durability of the current product for longer usage.
Energy-Efficient Hardware: Introduce energy-efficient hardware components, such as low-power sensors and more efficient microcontrollers, to extend battery life and reduce the environmental impact of the device.
6. Global Accessibility and Localization:
Multilingual Support: Add multilingual support to the mobile app, making it accessible to users across different regions and languages.
Affordable Versions for Developing Countries: Develop cost-effective versions of the device to make it more affordable and accessible in developing countries, where menstrual health products and education are often lacking.
By implementing these upgrades, the IoT-Enabled Smart Menstrual Cup could offer a more comprehensive, personalized, and accessible solution for menstrual health management, driving the future of FemTech innovation.













