# Transformer_less_power_supply
- It converts 230V AC input into a regulated 12V DC output at 200mA using capacitor impedance, without a
transformer. This technology allows for customization of output voltages and current ratings.
- The advantages of this power supply over transformer-based power supplies include being lightweight, costeffective, and compact.
  
![IMG_1262](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/d6385fe4-8041-4676-a1d5-0294341b2887)
![IMG_1227](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/99bfec08-6bdb-4842-a802-0c8f715e6cc8)

### Methodology

- The basic working principle of the transformerless power supply is a voltage divider circuit that converts single-phase AC high voltage to a desired low DC voltage without any use of transformer and inductor. The whole concept of this power supply involves Rectification, voltage division, regulation, and inrush limiting. The basic circuit of the transformerless power supply is shown below.
![transformerless power supply-edited](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/87d36941-a6cd-4bfb-bdcf-e36d7b48b4a1)

#### Capacitive Voltage Dividers for Efficient Voltage Reduction

- In some applications, capacitors are employed as key elements in voltage dividers, offering advantages over resistors. Unlike resistors, capacitors do not possess resistance to AC voltages but exhibit a property called capacitive reactance (Xc), which regulates the flow of alternating current.
- One notable feature of capacitive voltage dividers is their efficiency. Unlike resistive dividers that dissipate energy as heat, capacitors are more energy-efficient, resulting in lower power loss. This energy efficiency is a result of capacitors storing and releasing energy in the form of an electrical field, rather than converting it into heat.
- To accommodate the voltage levels commonly found in mains electricity, X-rated capacitors are often employed in capacitive voltage dividers. These capacitors are designed to handle voltages such as 230V, 600V, or 400V, making them suitable for various applications.

#### Smoothing and Voltage Regulation
- The capacitor absorbs a portion of the input AC voltage, while the remaining AC voltage is rectified by a diode bridge. This rectification process results in a lower DC voltage with significant ripple. To reduce this ripple, a large capacitor is employed. Additionally, a zener diode can be used to regulate the smoothed voltage to the desired level.

- In our circuit, the components are configured to produce a 12V DC voltage with a current of 200mA. However, it can be customized to accommodate different voltage and current values.

  ### Schematic of the Power Supply.
  ![Screenshot (285)](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/98046f4f-d170-40f5-9a4d-4eae6ec1bbf1)

- Here is the small, lightweight, cost-effective, and power-efficient 12V, 200mA power supply.
  
![IMG_1224](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/6106263e-e0b8-477e-90d4-c00242a334ae)
![IMG_1226](https://github.com/FernandopulleNK/Transformer_less_power_supply/assets/128304706/491b125b-c999-45ab-954c-49e293cabc15)
