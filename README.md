# DVTOD
# Data Collection

1)	Camera equipment: We use DJI MAVIC 2 Enterprise Advanced drone to acquire all image pairs. (a) Thermal camera: the sensor is an uncooled vanadium oxide microbolometer, image resolution is 640×512, pixel pitch is 12μm, and wavelength range is 8-14μm. (b) Visible camera: the sensor is a 1/2 inch complementary metal oxide semiconductor (CMOS), the effective pixels are 48 million, the viewing angle is 84°, the video resolution is 1920×1080, the equivalent focal length is 24 mm, and the aperture is f/ 2.8. 
2)	Data collection: The dataset contains 2179 visible-thermal image pairs and covers different objects and challenging scenes. As shown in Fig. 1, during the data collection, we set different challenging attributes to simulate the distribution of real data from the perspective of changes in illumination, severe weather, occlusion, and diversity of objects.

# Data Annotation

As shown in the top right corner of Fig. 1, when the object is in some challenging scenes, such as special material occlusion, or overexposure scenes, the image quality of the object is extremely poor or even disappears. To handle this situation, we choose the visible modality for annotation in special scenes and the thermal modality for annotation in the rest of the cases. Ultimately, a pair of images share a single label.

![Fig 1](https://github.com/VDT-2048/DVTOD/assets/101933818/2c4e2a87-4de6-48fa-88f0-c0fb40d04cfb)


# Summary

1) Visible-thermal image pairs are misaligned images acquired with drone, which provides the basis for researchers to investigate misaligned multispectral object detection methods.
2) The acquired image pairs contain more challenging attributes, such as rain, snow, fog, extreme exposure, darkness, and special material occlusion, which are more in line with the real-world data distribution.
3) The dataset is of higher quality than other dataset image pairs, with a resolution of 1920×1080 for visible images and 640×512 for thermal images. 
4) The dataset contains data at different times of the day and during all seasons of the year.

# Download the dataset and code

The dataset and code are available at:https://pan.baidu.com/s/1KMHdbwQwwY0dkEy6TkJC6A?pwd=wqnq 


# Paper
[Misaligned Visible-Thermal Object Detection A Drone-based Benchmark and Baseline.pdf](https://github.com/VDT-2048/DVTOD/files/15361460/Misaligned.Visible-Thermal.Object.Detection.A.Drone-based.Benchmark.and.Baseline.pdf)

https://ieeexplore.ieee.org/document/10522939

# Related Works of UAV RGB-T 
UAV-RGB-T-2400 https://github.com/VDT-2048/UAV-RGB-T-2400

https://ieeexplore.ieee.org/document/10315195

[2023-Modality Registration and Object Search Framework for UAV-Based Unregistered RGB-T Image Salient Object Detection.pdf](https://github.com/VDT-2048/DVTOD/files/15361992/2023-Modality.Registration.and.Object.Search.Framework.for.UAV-Based.Unregistered.RGB-T.Image.Salient.Object.Detection.pdf)

[2025-UAV applications in intelligent traffic RGBT image feature registration and complementary perception.pdf](https://github.com/user-attachments/files/18062868/2025-UAV.applications.in.intelligent.traffic.RGBT.image.feature.registration.and.complementary.perception.pdf)


# Related Survey
RGB-T Image Analysis Technology and Application: A Survey [J]. Engineering Applications of Artificial Intelligence, 2023, 120, 105919. 

https://www.sciencedirect.com/science/article/abs/pii/S0952197623001033

[2023-RGB-T Image Analysis Technology and Application A Survey.pdf](https://github.com/VDT-2048/DVTOD/files/15362195/2023-RGB-T.Image.Analysis.Technology.and.Application.A.Survey.pdf)

