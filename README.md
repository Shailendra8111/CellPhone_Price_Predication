# OBJECTIVE
Task 1:-Prepare a complete data analysis report on the given data.

Task 2:-On the basis of the mobile Specification like Battery power, 3G enabled , wifi ,Bluetooth, Ram etc predict the Price range of the mobile.

Task 3:- Prepare the analysis report stating how model will help expanding the business by stating several factors including feature importance.

# Domain Analysis
1. In the given dataset we have the following columns: battery_power, bluetooth, clock_speed, dual_sim,            front_camera, four_g, int_memory, mobile_depth, mobile_weight, n_cores, primary_camera, pixel_height,          pixel_width, ram, screen_height, screen_width, talk_time, three_g, touch_screen, wifi,price_range.
   - Battery_power denotes the battery capacity of the device.
   - The presence of Bluetooth connectivity is indicated by the Bluetooth column.
   - Clock_speed represents the processor's execution speed for inputs.
   - Dual_sim signifies whether the device supports dual SIM cards.
   - Front_camera provides the megapixel count for the front-facing camera.
   - Four_g indicates whether the device supports 4G network connectivity.
   - Int_memory denotes the device's internal memory capacity in gigabytes.
   - Mobile_depth measures the depth dimension of the device.
   - Mobile_weight represents the total weight of the device in grams.
   - N_cores indicates the number of processor cores the device possesses.
   - Primary_camera signifies the megapixel count for the primary (rear) camera.
   - Pixel_height refers to the pixel resolution height of the device.
   - Pixel_width refers to the pixel resolution width of the device.
   - RAM represents the amount of memory in megabytes the device possesses.
   - Screen_height denotes the height of the device's screen.
   - Screen_width represents the width of the device's screen.
   - Talk_time indicates the total screen-on time the device can remain functional.
   - Three_g denotes the 3G network capability of the device.
   - Touch_screen indicates whether the device has touch capabilities.
   - Price_range, our target variable, classifies devices into Low, Medium, High, or Very High Cost categories.
   
   
2. Today's mobile phone market is highly segmented and fiercely competitive, nearing saturation. Saturation significantly impacts prices, as very high-cost phones often lack substantial innovation, while flagship killer variants fiercely challenge top-tier phones in specifications. Further down the spectrum, competition intensifies, with numerous companies offering various models at similar price points. This creates a challenging environment for both consumers and companies, as models within the same price segment often feature similar attributes, including build quality and materials used.


3. In such a market, it becomes crucial for new entrants to carefully select a market segment for their devices and tailor them with appropriate features accordingly.

4. Additionally, for a newcomer to make a notable impact in the market and garner a share of the market, they must offer something unique that existing models do not provide.

 # Univariant Analysis
1.  The market's average phone battery size stands at 1239 mAh, with a range from 501 mAh to 1998 mAh.
2.  Bluetooth connectivity is present in 50% of market phones, while the remainder lack this feature.
3.  Devices in the market exhibit an average clock speed of 1.52 GHz, with a range from 0.5 GHz to 3 GHz.
4.  Dual SIM slots are included in 51% of phones, with the rest lacking this feature.
5.  The average megapixel count for front cameras is 4.3 megapixels, ranging from 0 to 19 megapixels, with some     devices not equipped with a front camera.
6.  52% of phones in the market support 4G.
7.  Market devices have an average internal memory of 32GB, with a range from 2GB to 64GB.
8.  The average thickness of market phones is 0.5cm, ranging from 0.1cm to 1cm.
9.  The average weight of phones in the market is 140 grams, with weights ranging from 80 grams to 200 grams.
10. The average number of cores in mobile phones is 4.5, with a range from 1 to 8 cores.
11. The average megapixel count for primary cameras is 9.9 megapixels, with a range from 0 to 20 megapixels,       indicating some devices lack a primary camera.
12. Camera pixel heights in phones average at 645, ranging from 0 to 1960.
13. Camera pixel widths in phones average at 1252, ranging from 500 to 1998.
14. The average RAM of devices is 2124 Mb, ranging from 256 Mb to 3998 Mb.
15. The mean screen height of devices is 12.3 cm, with heights ranging from 5cm to 19cm.
16. The mean screen height of devices is 12.3 cm, with heights ranging from 5cm to 19cm.
17. The average battery life of phones is approximately 11 hours, with a range from 2 hours to 20 hours.
18. Touchscreen functionality is present in 50% of market devices.
19. Wifi functionality is present in 51% of market devices.
20. Market segmentation across Low, Medium, High, and Very High cost categories is evenly distributed at 25%       each.

21. # Bivariant Analysis
![Screenshot 2024-05-15 213534](https://github.com/Shailendra8111/CellPhone_Price_Predication/assets/157679339/00322206-222e-426d-9f88-a9f9d0cf9305)
![Screenshot 2024-05-15 213721](https://github.com/Shailendra8111/CellPhone_Price_Predication/assets/157679339/387d3f63-fbd4-4889-a068-9694955fdaa6)
![Screenshot 2024-05-15 213741](https://github.com/Shailendra8111/CellPhone_Price_Predication/assets/157679339/862f886b-dd4d-4233-8afe-943e1244cb2a)


# Model Classification Report
26. ![Screenshot 2024-05-15 221109](https://github.com/Shailendra8111/CellPhone_Price_Predication/assets/157679339/8265cf21-ae67-4c0e-bfdd-d1fb60484055)


# As shown in the above table the Gradient Boost Algorithm after Hyperparameter tuning gives the best accuracy of 94.82% whereas Descision Tree after hyperparametertunning gives the lowest accuracy of 88%.

# Challenges Faced 
1. Analyzing the data posed a challenge owing to the extensive array of features.
2. Addressing outliers presented a significant hurdle.
3. Achieving high accuracy with the models proved to be a challenging endeavor.
