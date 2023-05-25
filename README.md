# Controller Area Network Dataset Library
A Python library for downloading and accessing 6 CAN datasets after preprocessing easily.
## Installation
You can install the library using pip:
```c
pip install Candataloader==1.1.2
```
Make sure you have Python 3.6 or higher installed.
## Usage
Import the `download_dataset` function from the library and use it to download datasets.
```c
from Candataloader.download import download_dataset
download_dataset('dataset_name')
```
6 datasets with dataset_name and corresponding file as follows: 

|dataset_name   |file   |
|---|---|
|Survival   |Survival Analysis Dataset for automobile IDS.csv|
|ROAD   |ROAD.csv|
|OTIDS   |OTIDS.csv|
|Car Hacking  |Car Hacking.csv|
|Automotive   |autoCAN_Prototype.csv|
|SynCAN   |SynCAN.csv|
The dataset will be downloaded to the current directory.
## Reference
The datasets are processed from the following sources:
[Automotive Controller Area Network (CAN) Bus Intrusion Dataset v2](https://data.4tu.nl/articles/dataset/Automotive_Controller_Area_Network_CAN_Bus_Intrusion_Dataset/12696950/2)
[Survival Analysis Dataset for automobile IDS](https://ocslab.hksecurity.net/Datasets/survival-ids)
[Real ORNL Automotive Dynamometer (ROAD) CAN Intrusion Dataset](https://0xsam.com/road/)
[CAN Dataset for intrusion detection (OTIDS)](https://ocslab.hksecurity.net/Dataset/CAN-intrusion-dataset)
[Car-Hacking Dataset for the intrusion detection](https://ocslab.hksecurity.net/Datasets/car-hacking-dataset)
[SynCAN dataset](https://github.com/etas/SynCAN)
## License
This project is licensed under the MIT License.
## Contact
If you have any questions or feedback, feel free to reach out to us at phongletien18@gmail.com.