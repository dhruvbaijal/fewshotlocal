Used ResNet architecture
Added appropriate rescaling in ResNet arch (for all models)
For model 120 and 121, in pL and pCL classes in networks.py divide by sqrt of network width param from ResNet Train ntbk (sqrt 512 for 120 and sqrt 128 for 121)
Results are good!

