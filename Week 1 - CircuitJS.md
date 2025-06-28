# My Circuit Learning Log

## 🔹 Week 1 - CircuitJS


- Started learning **CircuitJS** using the [Spoken Tutorial](https://spoken-tutorial.org/tutorial-search/?search_foss=CircuitJS&search_language) platform, as recommended by our HOD sir.
- Learned how to create a basic **LED blinking circuit** using simulation.

### ⚙️1) Topic: Series and Parallel Resistance

**Learning Objectives:**
1. Understand how to connect resistors in **series** and **parallel** circuits.
2. Observe how **voltage** and **current** behave in each configuration.

**Experiment Setup:**
- **Circuit Description:**
  ![image](https://github.com/user-attachments/assets/4a3602d8-9faf-4f09-b096-1f98d45b817b)
  
  Three resistors — **10kΩ**, **20kΩ**, and **30kΩ** — were connected in **series** with a **100V DC source** and an **ammeter**.

**Observations:**
- The **current (I)** through each resistor is the same: **1.667 mA**
- The **voltage (V)** across each resistor is different:
  - 30kΩ → **50V**
  - 20kΩ → **33.3V**
  - 10kΩ → **16.7V**

> 💡 *Note: You can view voltage and current values in CircuitJS by clicking on each component.*

### ⚙️2) Topic:Voltage Divider circuit

**Learning Objectives:**
- the input voltage divides among the components in the circuit to manage the output voltage of the circuit by changing the values of resistors

 **Experiment Setup:**  dc v= 12v 
analog output from draw section and place between r1 and r2 by right click on analog ouptu click on "Show Voltage" and two resistors are connected as shown 
 

  ![image](https://github.com/user-attachments/assets/f1ea478e-b692-4e27-978f-2110e621f9db)
 

**Observations:**
- power supply of 12 volt will be same if both resistor value is equal but in our setupt R1 is 3k  ( Vd=9v) and R2 is 1k ( Vd= 3v)

  
-**Circuit Description:**
  
![image](https://github.com/user-attachments/assets/77b91143-4665-4f8b-8912-b075dd304fbd)


### ⚙️3)LCR Circuit
**Learning Objectives:** -checks waveforms of I & V   for LCR Components 
**Experiment Setup:**- add resisitor ,ac power supply from passive components add inductor & capacitor make circuit as per diagram ,click on each component each time and view in new scope option and observe the waveforms

 **Circuit Description:**-
![image](https://github.com/user-attachments/assets/b07195c7-a3ee-4141-8305-ee8918c6121d)

**observations:**
from the sinewaves we understand that :
 - resistor have unity power factor
 - capacitor have leading power factor 
 - inductor have leading power factor

###  ⚙️4)Wheatstone Bridge 
**Learning objectives**
- check how wheatstone bridge is used to measure unknown resisitance in the circuit
- check the balance condition
  
**Experiment Setup:** draw circuit as per the circuit diagram
  -![image](https://github.com/user-attachments/assets/f087ec40-7d42-476b-99aa-50f34fc9d19d)


 **Circuit Description:**-
 ![image](https://github.com/user-attachments/assets/974e1755-6c6b-4a6b-bc1d-3f7e15499e91)


 **observations:**
  - 1.if all resistors are of same value then it is balance condition and ammeter will not deflect(ckt js not have galvonometer ) i.s. Ratio of resisitance is P/Q = R/S
-  2. if resistance inbalance then ammeter will deflects
 -  3. we can measure unkown resistance by  formula

### ⚙️ 5) Silicon Diode Characteristics

The process of applying an external voltage to a p-n junction of a diode is called **biasing** — which includes both **forward bias** and **reverse bias**.

---

#### 🔬 Experiment Setup:

1. **Add Components**:
   - Go to `Draw` → Add **Variable Voltage**.
   - From `Edit`, set:
     - **Min voltage** = 0V
     - **Max voltage** = 2V
   - Add a **Diode**, **Ammeter**, **Resistor (Ω)**, and **Ground**.

2. **Wiring**:
   - Connect the components to form a basic diode circuit.

3. **Scope Setup**:
   - Use the **right slider** to vary the voltage.
   - Right-click the **diode** → `View in New Scope`.
   - Enlarge the scope window.
   - Click the **Settings icon** (bottom left).
   - Select `X-Y Plots` → Check `Show V vs I` → Click **OK**.

   - The graph will display:
     - **Voltage (V)** on the X-axis (green line)
     - **Current (I)** on the Y-axis (yellow line)

   ![image](https://github.com/user-attachments/assets/1c6d5270-5f29-45ee-b725-256b32d09361)

---

#### 📊 Observations:

- The **knee voltage** (threshold for forward conduction) is approximately **0.7V**, as seen on the ammeter.

![image](https://github.com/user-attachments/assets/879ddd68-2d08-4493-8376-30e384954a62)

---

### 📘 Diode Characteristics Summary

- **Forward bias**: Diode conducts current, allowing electricity to pass through.
- **Reverse bias**: Diode blocks current, allowing only minimal leakage current to pass.

---



      





- Understood the concept of current flow through a resistor.
- Simulated logic gates such as AND and OR using CircuitJS.
- Explored some ready-made circuits such as potentiometer, rectifiers, multivibrators (astable, bistable, monostable), and transistors.
- Observed their working and waveform characteristics by varying simulation speed and current flow.


