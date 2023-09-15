# ENVNoise
This is a non-working plugin for QGIS:

*Implementation of International Standard ISO 9613-2 “Acoustics – Attenuation of sound during propagation outdoors – Part 2: General method of calculation”*

It is an QGIS Python Toolbox (Python and Numpy packages). To use it you QGIS Desktop software >= #.0. 

In ENVNoise Python Toolbox there are # tools:




1. Create Project - define project folder. Toolbox will optionally generate a template for model features (buildings, point sources, calculation areas, etc.)




2. Import Data - give a paths to project features. Optionally you can only update some of them.




3. Run Project - start calculations. You can choose calculation type: Receiver or Grid. Furthermore, you have a lot of settings, so if you know *ISO 9613-2 Standard* you can get into depth. If not just leave defaults.




* Calculation Settings




* Environment Settings

![environment](https://user-images.githubusercontent.com/23641410/29656672-6ac6b83a-88b5-11e7-925f-06dc1481fa82.PNG)


* Model Settings

![model-settings](https://user-images.githubusercontent.com/23641410/29656668-6ab7d694-88b5-11e7-93c1-e6b4641b3cac.PNG)


Using other interpolation tools you can prepare maps with noise level areas like below:

![results-map](https://user-images.githubusercontent.com/23641410/29657974-9facd5f8-88b9-11e7-8b91-74be8a7b0e88.PNG)
