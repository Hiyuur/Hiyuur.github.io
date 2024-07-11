# DroneSwarms
DroneSwarms is a object detection dataset for anti-UAV with the smallest average size currently.

## Description
DroneSwarms consists of 9,109 images and 242,218 annotated UAV instances, with 2,532 used for testing and 6,577 used for training. On average, each image contains 26.59 drone instances. The images are in the size of 1920 × 1080, manually labeled with high precision. DroneSwarms encompasses a variety of outdoor settings such as urban environments, mountainous terrain, and skies, among others. Unlike existing anti-UAV datasets, DroneSwarms contains 241,249 tiny objects with size of 32 pixels or below, accounting for approximately 99.60%, and the average size is only about 7.9 pixels. The drones are dispersed across the entirety of the image. Therefore, DroneSwarms can be used to comprehensively evaluate methods for tiny object detection .

## Download

## More Details

### Absolute Size Distribution
Almost all instances in DroneSwarms are tiny objects. In DroneSwarms, there are 241,249 tiny objects with a pixel area below 32 x 32, accounting for approximately 99.60%.
The average absolute size of objects in DroneSwarms is only 7.9 pixels. The information content contained in these tiny drones is minimal, and imaging blur often occurs, making feature extraction very challenging. Differentiating from the background is difficult when these tiny drones appear in front of ground and building backgrounds. Additionally, due to lighting angles, tiny drones under cloud cover are also hard to distinguish from the background in terms of color. The relative pixel areas of these tiny drones compared to the entire image are extremely small, resulting in a severe imbalance between foreground and background. Therefore, we propose the DroneSwarms as a challenging dataset for tiny object detection.
![absolute size distribution](/figures/size_.png)

### Spatial Distribution
Significantly, the drone objects do not exhibit concentration around the image center; instead, their positions are extensively scattered. On average, each image in the DroneSwarms dataset contains 26.59 drone objects. Detecting densely packed tiny drones in neighboring regions poses a significant challenge within this context.
![spatial distribution](/figures/position_.png)

### Image Background
DroneSwarms encompasses a variety of outdoor settings such as urban environments, mountainous terrain, and skies, among others. Furthermore, DroneSwarms also encompasses different lighting conditions based on various times and weather conditions, such as clear skies, overcast weather, dusk, and backlighting. Moreover, the drones showcase a variety of postures like takeoff, hovering, cruising, and landing, allowing them to appear in different sizes and angles within the same background.
![examples](/figures/examples.png)
