
# Exp 3 Experimental Verification of IV Characteristics of LED and LASER
# Fiber Optic LED Characteristics and Photo Detector Response

## 🎯 AIM
To study the characteristics of fiber optic LED and plot the graph of forward current versus optical power, and to study the photo detector response.

---

## 🧰 EQUIPMENTS REQUIRED
- Power supply  
- Patch chords  
- 1-meter fiber optic cable  
- Digital Multimeter (DMM)  

---

## 📚 THEORY

- **LEDs and LASER diodes** are commonly used sources in optical communication systems for both digital and analog transmission.
- A **linear electrical-to-optical converter** is essential for intensity modulation and high-quality analog transmission.
- LEDs exhibit a **linear optical output** with respect to forward current within a specific operating range.

---

## 🧪 PROCEDURE

1. Connect the power supply to the board.
2. Ensure all switched faults are in the ‘Off’ position.
3. Set emitter 1 block to **Digital Mode**.
4. Make the following connections:
   - Connect the bias 1 preset on comparator 1 (TP13) to emitter 1 input (TP5).
   - Turn the bias 1 preset fully counterclockwise. In subdued lighting, slowly increase the setting until LED light is just visible.
5. Connect the DMM between +12V supply and TP6 (LED cathode) to measure **forward voltage (Vf)**.
6. Measure the voltage drop across the 1KΩ resistor (R9) by connecting DMM between TP6 and TP38.  
   - **Forward current (If)** = DMM reading / 1000 (in mA)
7. Vary the bias 1 preset to adjust forward voltage (e.g., 1.3V, 1.4V, … 1.7V) and note corresponding forward current (If).
8. Record values of Vf and If, and plot the characteristic curve between them.

---

## 🔌 CONNECTION DIAGRAM
<img width="773" height="485" alt="image" src="https://github.com/user-attachments/assets/229ae738-2916-4ccb-98ea-9f10569bd4e1" />

---

## 📊 TABULATION

### LED Forward Characteristics

| Forward Voltage Vf (V) | Forward Current If (mA) |
|------------------------|-------------------------|
|           0.9mv        |            0.1mA        |
|           1.2mv        |            0.1mA        |
|           1.9mv        |            0.2mA        |
|           2.5mv        |            0.3mA        |
|           2.7mv        |            0.4mA        |
|           3.6mv        |            1.5mA        |
|           4.0mv        |            1.8mA        |
|           5.2mv        |            2.8mA        |
|           7.6mv        |            4.0mA        |
|           8.0mv        |            4.4mA        |
|          10.2mv        |            7.2mA        |
|          12.5mv        |            9.4mA        |
|            15mv        |           10.1mA        |

![WhatsApp Image 2025-11-24 at 07 58 04_224a3aad](https://github.com/user-attachments/assets/d7853789-cb2a-469a-bbcf-c9b2cbd5277e)

---

## 📈 MODEL GRAPH

![WhatsApp Image 2025-11-24 at 07 58 04_f7237c54](https://github.com/user-attachments/assets/d0daf57b-bff6-45af-9d51-432401da29e2)

---

## ✅ RESULT
- The forward voltage and current characteristics of the fiber optic LED were successfully studied.
- The photo detector response was observed and analyzed.
