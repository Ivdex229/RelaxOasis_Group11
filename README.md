
RelaxOasis_Group11
Programming for IoT Applications
Welcome to the RelaxOasis Group11 repository! This project focuses on developing applications for the Internet of Things (IoT) to create a relaxing and automated environment.

Contents:

LINKS.txt: Contains links to our promotional and demo videos showcasing the project.
IOT_RELAX_OASIS_GROUP_11.ppt: Our project presentation detailing the concept, implementation, and benefits of RelaxOasis.
RelaxOasis_Group11.zip: Includes all the source code for the project, along with Docker files for easy deployment.

To clone the repository:git clone https://github.com/Ivdex229/RelaxOasis_Group11.git


HOW TO RUN THE PROJECT:
Follow these steps to run the various components of the RelaxOasis project:

Run the Service Catalog Server:
cd "C:\your_path"
python service_catalog_server.py

Run the Resource Catalog Server:
cd "C:\your_path"
python resource_catalog_server.py resource_catalog_settings_1.json resource_catalog_devices_1.json

Run the Light Sensor:
cd "C:\your_path"
python sensor_light.py conf_light.json service_catalog_info.json

Run the Temperature Sensor:
cd "C:\your_path"
python sensor_temperature.py conf_temperature.json service_catalog_info.json

Run the Humidity Sensor:
cd "C:\your_path"
python sensor_humidity.py conf_humidity.json service_catalog_info.json

Run the Noise Sensor:
cd "C:\your_path"
python sensor_noise.py conf_noise.json service_catalog_info.json

Run the EVO Sensor:
cd "C:\your_path"
python sensor_evo.py conf_evo.json service_catalog_info.json resource_catalog_users.json

Run the Machine Learning Component:
cd "C:\your_path"
python ML_new.py conf_evo.json conf_ML.json

Run the Telegram Bot:
cd "C:\your_path"
python TelegramBotDefinitivo.py conf_bot_telegram.json conf_light.json conf_noise.json conf_temperature.json conf_humidity.json service_catalog_info.json

Run the ThingSpeak Adaptor:
cd "C:\your_path"
python ThingSpeakAdaptor.py conf_thinkgspeak.json service_catalog_info.json
Ensure you replace "C:\your_path" with the actual path to your project directory.
