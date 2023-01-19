# vkbconfig
My VKB configuration for a Gunfighter Mk III MCGU grip with T-Rudder Mk IV and differential braking

This configuration, built with VKB Device Config v0.92.51 (NJoy firmware v2.12.0), assumes that you want to use the bottom handle as a brake lever to activate the brakes, and that the level is assigned to axis 8 on the grip, with the rudder pedals on axis 7.

The MCGU is set up with a single virtual controller, in addition to the physical controller.

![image](https://user-images.githubusercontent.com/123090510/213490501-32c8664f-c45c-4836-b614-9d95258cc946.png)

When the brake lever is pulled, the input of the lever and the rudder is combined on virtual axes 9 & 10

![image](https://user-images.githubusercontent.com/123090510/213490105-8e2a2511-136a-4c1b-9411-053a8c8efdb0.png)

Those two virtual axes are mapped to a second virtual controller that should appear in your sim. Axis 9 appears as the Rot X input, and Axis 10 appears as the Rot Y input.

The MCG Brake is not enabled, and the brake lever axis is hidden so that only the virtual brake input appears in the simulator.

![image](https://user-images.githubusercontent.com/123090510/213489872-2c356e0a-95fc-42d9-9477-96e340278535.png)

Differential braking works by applying both brakes when the lever is pulled, and then releasing the opposing brake when the rudder is pushed in one direction. For example, if the rudder is pushed to the right, the left brake is released. This means that you want to configure your sim to use the opposite axis for the brakes and the rudder.

![image](https://user-images.githubusercontent.com/123090510/213489680-e6903345-a2c4-48a9-bb28-4a4cf8a3f42e.png)

