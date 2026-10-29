# Exploration-of-AI-Use-Case-Case-study-on-self-driving-cars

# AIM

To study the application of Artificial Intelligence (AI) in self-driving cars and understand how AI technologies help vehicles perceive their surroundings, make decisions, and navigate safely without continuous human control.

# THEORY

Self-driving cars, also known as autonomous vehicles, use Artificial Intelligence (AI), sensors, computing systems, and control engineering to perform some or all driving tasks. Unlike a conventional vehicle that relies on a human driver to observe the road and make decisions, an autonomous vehicle continuously collects information about its surroundings, interprets that information, plans an appropriate action, and controls the vehicle. This process repeats as traffic and road conditions change.

**1. Environmental perception:** The vehicle first gathers information using sensors. Cameras capture images of the road, traffic lights, signs, lane markings, pedestrians, and other vehicles. Radar measures the distance and relative speed of objects and can work in conditions where visibility is reduced. LiDAR uses laser pulses to estimate distances and build a three-dimensional representation of nearby objects. Ultrasonic sensors may assist with short-range detection, particularly during parking. Each sensor has strengths and limitations, so a vehicle may use several types together.

**2. Computer vision and object detection:** AI-based computer vision analyses camera images to identify and classify objects such as cars, cyclists, pedestrians, traffic signs, and road boundaries. Machine-learning models are trained on large collections of labelled data so they can recognize patterns in new images. The system may also estimate the position, size, and movement of detected objects. Accurate detection is essential because a missed pedestrian or incorrectly identified traffic signal can lead to an unsafe decision.

**3. Sensor fusion:** Data from cameras, radar, LiDAR, and other sensors are combined through a process called sensor fusion. For example, a camera may identify an object as a car, while radar estimates its distance and relative speed. Combining these measurements can provide a more complete and reliable understanding than relying on a single sensor. The system must also account for differences in sensor timing, position, accuracy, and operating conditions.

**4. Localization and mapping:** The vehicle needs to estimate its own position and orientation on the road. It can use satellite navigation, inertial measurement sensors, wheel-speed measurements, and information from cameras or LiDAR. Maps may provide details about road geometry, junctions, and lane layouts. Since satellite positioning can be inaccurate in tunnels or between tall buildings, the vehicle may combine several sources to maintain a more dependable estimate of its location.

**5. Prediction and decision-making:** Detecting an object is not enough; the vehicle must estimate what that object may do next. Prediction algorithms analyse the movement and context of nearby road users. For instance, the system may estimate whether a pedestrian is likely to cross the road or whether a vehicle in the next lane may merge. AI and rule-based decision systems use this information, along with traffic rules and safety constraints, to choose an appropriate action such as slowing down, yielding, changing lanes, or stopping.

**6. Path planning:** Once the system has selected a driving manoeuvre, path-planning algorithms calculate a safe and practical path toward the destination. The planned path must account for lane boundaries, obstacles, other road users, road curvature, speed limits, and available space. The system may continuously revise its path when a new obstacle appears or traffic conditions change.

**7. Vehicle control:** The planned path is converted into commands for steering, acceleration, and braking. Control algorithms compare the vehicle's actual movement with the desired path and adjust the commands to reduce the difference. Feedback from sensors allows the controller to correct its actions continuously. For example, if the vehicle begins to drift away from the centre of its lane, the controller can adjust steering to bring it back toward the planned path.

**8. Continuous feedback and safety:** Autonomous driving is a continuous cycle of sensing, perception, prediction, planning, and control. The vehicle checks new sensor data after each action and updates its decisions as the environment changes. Safety engineering may include redundant sensors or computing components, fault detection, emergency braking, and a controlled response when the system cannot operate reliably. The actual capabilities vary by vehicle and automation level. AI does not make a vehicle infallible, and safe deployment requires extensive testing under varied road, weather, and traffic conditions.

In summary, AI helps a self-driving car interpret complex surroundings and make decisions, while sensors provide measurements and control systems execute the resulting actions. These components must work together in real time for the vehicle to navigate safely and consistently.

# RESULT

The study explains how AI, sensor technologies, computer vision, sensor fusion, localization, prediction, path planning, and feedback control work together in self-driving cars. Their safe operation depends on accurate perception, sound decisions, reliable control, and appropriate safety systems.
