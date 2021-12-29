# Personalized Finance Projections
I'm obsessed with optimizing my finances, so I developed this tool to *roughly* estimate my finances for the rest of my life. This is a very detailed simulation with several parameters, however one should always be skeptical when predicting the future.

User defined parameters exist in lines 12-42, and are clearly denoted in comments by:
```python3
#
# START USER EDITABLE SECTION
#
...
#
# END USER EDITABLE SECTION
#
```

**Disclaimers:** This model does not take taxes into account - it wasn't worth my time to investigate and gather 50 state tax rates & build them into a dynamic model. Especially since tax brackets are always changing. For best results input your **post tax salary**. This model also does not take into account the cost of children - but it wouldn't be hard to implement if that's something you're interested in.

Nothing in this program is intended as financial advice, and simulation results are not guaranteed to be accurate. Do your own research, be smart with your money.

Finally, I want to state for the record that the pre-inputted parameters are not representative of my personal information. I just picked some numbers that I though would be generally applicable towards a computer science audience.

**Usage:** This model really helps visualize the power of early investing, and can help you estimate when retirement might be possible. I have also used this model to estimate how much savings I'll need based on a variable income (i.e. going to graduate school).

I highly recommend using the .ipynb version, as the inline graphics are much easier to read. However, I did include a working .py version.

**Requirements:**
 - numpy
 - matplotlib

## **Visuals:**
![img-1](https://github.com/nbonnie/Personalized_Finance_Projections/blob/main/plots/Figure_1.png?raw=true)
![img-2](https://github.com/nbonnie/Personalized_Finance_Projections/blob/main/plots/Figure_2.png?raw=true)
![img-3](https://github.com/nbonnie/Personalized_Finance_Projections/blob/main/plots/Figure_3.png?raw=true)
![img-4](https://github.com/nbonnie/Personalized_Finance_Projections/blob/main/plots/Figure_4.png?raw=true)
![img-5](https://github.com/nbonnie/Personalized_Finance_Projections/blob/main/plots/Figure_5.png?raw=true)