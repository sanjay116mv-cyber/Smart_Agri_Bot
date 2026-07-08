🤖 Smart Agribot Rover: Precision Field Monitoring System
Sustainable Agriculture Solutions | Junior Category

Team KOME | AUPET Chinmaya Vidyalaya MHS School, Tirunelveli

Project Motivation
Agriculture in the Tirunelveli district faces 20-30% yield losses due to uneven soil moisture, delayed weather detection, and the limitations of manual field scouting. The Smart Agribot Rover was developed to bridge this gap. By providing autonomous field traversal and real-time environmental analytics, this project empowers smallholder farmers with affordable, high-precision tools to respond to field conditions instantly, preventing crop failure before it starts.

How It Works
The Smart Agribot Rover functions as a mobile, solar-powered agricultural scout. It traverses the field to collect critical data directly where the crops grow.

The system utilizes a dual-layer wireless architecture. An ESP32-CAM handles video video streaming and rover navigation, allowing the user to remotely drive the bot through the field. Simultaneously, an ESP8266 system manages a suite of environmental sensors and a specialized servo-actuated soil probe. This probe is mechanically inserted into the soil to measure Volumetric Water Content, providing highly accurate data that static sensors often miss.

Core Technical Capabilities
Sensor Fusion & Predictive Analytics: The rover does not just record numbers; it analyzes them. By calculating the Vapor Pressure Deficit (VPD), the system identifies plant stress and potential disease risks. Additionally, it uses atmospheric pressure and humidity trends to predict rainfall 3–5 hours in advance.

Autonomous Actuation: Using an SG90 servo, the rover automatically deploys a V3 capacitive soil moisture sensor, ensuring accurate, repeatable, and deep-soil data collection without manual labor.

Sustainable Power Architecture: Designed for long-term field deployment, the system uses a 10W solar panel to charge a 7.4V 4000mAh Li-ion battery, managed by efficient LM2596 regulators to ensure continuous operation.

Robust Safety Features: The rover includes built-in fail-safes such as servo stall detection, overcurrent protection for motors, an emergency web-based kill switch, and an auto-return-to-charging-station mode for criticalerrors.

Performance & Impact
In field trials conducted in November 2025, the Smart Agribot successfully monitored a 2-acre plot and achieved high-accuracy rain prediction. With a total system cost of approximately ₹4,000, it provides a highly scalable and cost-effective solution that is accessible to rural farming communities.

Maintenance & Reliability
The system is built for longevity with an estimated Mean Time Between Failures (MTBF) of over 5000 hours. Daily maintenance involves cleaning solar panels and the probe tip, while weekly upkeep includes gear lubrication and battery checks. Monthly sensor recalibration and firmware updates ensure the system remains at peak performance.

Team Competencies
The project was brought to life by Team KOME, combining expertise in:

Mechanical Engineering: Chassis fabrication and custom probe mechanism design.

Electronics: Sensor integration, power distribution, and circuit reliability.

Embedded Programming: Development of ESP firmware and real-time web server dashboards.

Field Testing: Agricultural validation and data-driven performance analysis.

Mentored by Murugan V (STEM Coordinator).

Designed for sustainable, data-driven farming.# Smart_Agri_Bot