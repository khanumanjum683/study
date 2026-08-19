# X-Ray Circuits

## 1. Introduction

An X-ray machine is an electrical device that converts mains electricity into a controlled high-voltage supply for the X-ray tube and a controlled low-voltage supply for the filament circuit. The X-ray machine must provide a stable, accurate, and safe output of tube voltage and tube current so that the produced X-ray beam meets diagnostic requirements.

For this reason, X-ray circuits include:

- transformers for voltage conversion
- rectifiers for converting AC to DC
- control circuits for kV and mA selection
- filters and stabilizers to smooth output
- compensators for fluctuations in mains voltage and frequency
- filament circuits for electron emission

These parts all work together to maintain correct X-ray production. They are not isolated subsystems; they form a connected power-control system that determines the final X-ray beam quality and intensity.

---

## 2. Principle of transformers

A transformer is a static electromagnetic device that transfers electrical energy from one circuit to another through mutual induction.

### 2.1 Basic construction

A transformer has:

- primary winding
- secondary winding
- laminated iron core

When alternating current flows in the primary winding, it produces a changing magnetic flux in the core, which induces a voltage in the secondary winding.

### 2.2 Voltage ratio

The induced voltage is proportional to the number of turns:

Vs / Vp = Ns / Np

where:

- Vp = primary voltage
- Vs = secondary voltage
- Np = number of turns in primary winding
- Ns = number of turns in secondary winding

This means:

- more turns in the secondary than primary → step-up transformer
- fewer turns in the secondary than primary → step-down transformer

### 2.3 Current relationship

For an ideal transformer:

VpIp = VsIs

Thus, when voltage is stepped up, current is stepped down, and vice versa.

### 2.4 Why transformers are essential in X-ray circuits

X-ray tubes require a very high voltage to accelerate electrons toward the target, while the filament requires a lower voltage for heating. Therefore, different transformer stages are used to produce:

- high-tension (HT) voltage for the anode-cathode tube potential
- low-voltage supply for the filament heater

### 2.5 Transformer losses

Real transformers are not perfectly efficient. Power losses occur due to:

- copper loss in winding resistance
- eddy current loss in the core
- hysteresis loss in the core
- leakage flux

### 2.6 Efficiency of transformer

Transformer efficiency is:

η = output power / input power × 100%

A well-designed transformer may have high efficiency, but losses still produce heat and reduce output.

### 2.7 Sources of power loss

- copper loss: I²R loss in windings
- eddy current loss: induced currents in the core
- hysteresis loss: energy lost in repeatedly magnetizing and demagnetizing the core
- leakage: magnetic flux not effectively coupled between windings

### 2.8 Design features to reduce losses

- laminated core to reduce eddy currents
- soft iron or silicon steel to reduce hysteresis
- proper winding design to reduce leakage flux
- efficient cooling

---

## 3. H.T. generators for X-ray machines

The X-ray tube needs a high-tension voltage, often tens to hundreds of kilovolts, to accelerate electrons and generate X-rays. This is provided by the high-tension generator.

### 3.1 Function of the HT generator

The HT generator converts the mains voltage into a high-voltage DC or pulsating DC supply for the X-ray tube.

### 3.2 High voltage transformer

The high-voltage transformer is a step-up transformer whose secondary voltage may be several tens of kilovolts. Its output is usually AC, which is then rectified.

### 3.3 Rectification of HT supply

The secondary output is rectified so that the X-ray tube receives the required polarity for electron flow from cathode to anode.

### 3.4 Relationship to X-ray output

The quality and intensity of the X-ray beam depend on the high-tension voltage and current. In general:

- higher kV → more penetrating beam
- higher mA → more photons produced

The HT generator is therefore central to tube operation.

---

## 4. High-frequency circuits

In modern X-ray machines, high-frequency generators are often used instead of traditional 50/60 Hz mains-frequency systems.

### 4.1 Principle

The mains AC is first converted to a high-frequency AC signal, often several kHz to tens of kHz, then transformed and rectified. This is done using inverter circuits and switching devices.

### 4.2 Advantages of high-frequency circuits

- smaller and lighter transformer
- better control over output
- improved waveform regulation
- lower ripple
- higher efficiency
- better kV and mA stability

### 4.3 Why they are used in X-ray units

High-frequency generators allow precise control of tube voltage and current, making modern imaging systems more stable and efficient.

### 4.4 Relationship to power supply quality

Because the output is more stable, the X-ray beam is more reproducible, and patient dose control improves.

---

## 5. Self-rectifier half-wave rectifier

A self-rectifying circuit uses the X-ray tube itself as the rectifying element.

### 5.1 Principle

The X-ray tube conducts current only when the anode is positive relative to the cathode. During the reverse half-cycle, no current flows.

### 5.2 Half-wave operation

The tube acts like a diode and only allows one half of the AC waveform to pass.

### 5.3 Output waveform

The output is pulsating DC with large gaps between pulses. The tube gets current only during one half-cycle.

### 5.4 Advantages

- simple circuit
- fewer components
- convenient in some old systems

### 5.5 Disadvantages

- inefficient use of supply
- high ripple
- lower average output
- more variable tube voltage

### 5.6 Relation to X-ray production

Because the X-ray tube is used as the rectifier, the beam output is not smooth and may vary significantly during the cycle.

---

## 6. Bridge rectifier

A bridge rectifier uses four diodes connected in a bridge arrangement to convert AC to DC.

### 6.1 Operation

During one half-cycle, one pair of diodes conducts; during the other half-cycle, the other pair conducts. The output polarity remains constant.

### 6.2 Output waveform

The output is full-wave pulsating DC, which is smoother than half-wave rectification.

### 6.3 Advantages

- more efficient than half-wave
- higher average DC voltage
- lower ripple
- easier filtering
- can use the full AC cycle

### 6.4 Use in X-ray circuits

Bridge rectification is widely used because it gives a more stable high-voltage supply for X-ray generation.

---

## 7. Three-phase rectifier circuits

Three-phase rectifiers are used in high-power imaging systems because they provide more continuous and smoother DC output than single-phase rectifiers.

### 7.1 Why three-phase power is useful

A three-phase AC supply has three overlapping sinusoidal voltages. This means the rectified output has less ripple and more consistent power delivery.

### 7.2 Advantages over single-phase systems

- smoother DC output
- lower ripple
- higher effective power output
- improved tube loading
- more stable X-ray output

### 7.3 Application in X-ray machines

Modern CT and large radiographic systems often use three-phase rectifier circuits or high-frequency multiphase systems because of their superior power and stability.

### 7.4 Relationship to beam quality

A smoother and more stable voltage produces more stable X-ray output and better reproducibility of exposure.

---

## 8. Capacitance filter, control, and stabilizing equipment

After rectification, the output is still pulsating. To produce a more uniform DC supply, filters are used.

### 8.1 Capacitor filter

A capacitor connected across the output stores charge during peaks and releases it between peaks, reducing ripple.

#### Effect

- smooths the rectified waveform
- reduces ripple
- improves DC stability

### 8.2 Filter circuits

Common filter arrangements include:

- capacitor input filter
- LC filter
- π-filter

### 8.3 Stabilizing equipment

Voltage stabilization is required because fluctuations in the mains power supply can change the output of the X-ray machine. Stabilization is necessary for:

- consistent kV output
- consistent tube current
- reproducible exposure
- patient safety

### 8.4 Relationship to X-ray output

If the supply voltage varies, the tube voltage and beam intensity also vary. Stable circuits ensure that the X-ray beam remains accurate and reproducible.

---

## 9. Main voltage compensators and main resistance compensators

Electrical power supplies often vary with mains voltage and load. X-ray circuits compensate for these changes.

### 9.1 Main voltage compensator

This compensates for fluctuations in the incoming mains voltage.

#### Why needed

If the mains voltage falls or rises, the tube voltage and filament current may change, altering the X-ray output. Compensation ensures that exposure parameters remain stable.

### 9.2 Main resistance compensator

This compensates for the effect of circuit or transformer resistance, which can cause voltage drop under load.

#### Effect

When equipment draws more current, the voltage at the X-ray tube may fall. The compensator modifies the circuit to maintain the selected output.

### 9.3 Importance in X-ray imaging

These compensators are important because any voltage drift can alter:

- beam quality
- patient dose
- image density
- reproducibility of exposures

---

## 10. Compensation for frequency variation

The X-ray setting depends not only on voltage but also on the frequency of the AC supply.

### 10.1 Why frequency matters

In AC supply systems, frequency affects transformer operation and rectifier behavior.

If the frequency varies, the output may alter because:

- transformer inductive reactance changes
- voltage regulation changes
- ripple patterns shift

### 10.2 Compensation methods

Frequency compensators may be included in the control system to maintain stable tube output even when mains frequency changes. In modern systems, increasing use of high-frequency inverters reduces dependence on mains frequency variation.

### 10.3 Relevance to modern X-ray units

Modern high-frequency X-ray generators are much less sensitive to mains frequency fluctuations than older systems.

---

## 11. Control of tube voltage, including kV compensator

The tube voltage is the accelerating potential between cathode and anode. It determines the maximum energy of the X-ray photons and therefore the penetrating ability of the beam.

### 11.1 Importance of kV control

Tube voltage controls:

- beam quality
- penetration through the patient
- radiographic contrast
- scatter level
- patient dose

### 11.2 kV compensator

A kV compensator adjusts the applied voltage to maintain the selected kV despite mains fluctuations or load changes.

#### Example

If the mains voltage dips, the actual kV may fall below the selected value. The compensator corrects this so the X-ray tube still sees the intended potential.

### 11.3 High-tension selector switch

This device allows the operator or automatic system to select the desired tube voltage range. It changes taps in a transformer or the voltage-control circuitry so that a selected kV is applied to the X-ray tube.

### 11.4 Relationship to X-ray quality

The selected kV directly affects the beam spectrum. Higher kV gives higher photon energy and greater penetration, while lower kV gives a lower-energy beam and better soft-tissue contrast but poorer penetration.

---

## 12. Filament circuit

The filament circuit heats the cathode filament so that electrons are emitted by thermionic emission.

### 12.1 Purpose of the filament circuit

It provides a low-voltage, high-current supply to the filament.

### 12.2 Effect on tube current

The filament temperature controls the number of electrons released from the cathode. More heating means more emitted electrons, which leads to a higher tube current (mA).

### 12.3 Why filament stabilization matters

Small variations in filament supply can produce large variations in tube current. Therefore, filament current must be controlled precisely.

### 12.4 Practical protection

Filament circuits are designed to prevent excessive heating and to maintain a stable emission rate.

---

## 13. Control of tube current and space charge compensation

Tube current, usually expressed as mA, determines the number of electrons crossing the tube and therefore the number of X-ray photons produced.

### 13.1 Tube current regulation

The tube current depends on:

- filament temperature
- tube voltage
- space charge conditions

### 13.2 Space charge region

Near the cathode, electrons accumulate as a space charge. This cloud can limit electron flow, especially at lower tube voltages.

### 13.3 Space charge compensation

At low kV, the space charge effect can reduce tube current. Compensation circuits modify the filament current or kV selection so that the desired tube current is maintained.

### 13.4 Why it matters

Tube current controls exposure intensity. If it is unstable, the X-ray output and image density become inconsistent.

### 13.5 Relationship with filament circuit

The filament circuit and space charge compensation are closely related because both control the electron emission and the resulting tube current.

---

## 14. How all these topics are interrelated

These X-ray circuit elements are not separate topics; they form one electrical system that generates and controls the X-ray beam.

### A coherent chain is:

1. Mains AC enters the circuit.
2. transformers convert voltage to the required levels.
3. rectifiers convert AC to DC for the X-ray tube.
4. filters smooth the waveform.
5. compensators stabilize voltage and current against mains variation.
6. kV selector and kV compensators set tube voltage.
7. filament circuit controls electron emission and therefore tube current.
8. space charge compensation ensures stable current at lower voltages.
9. the X-ray tube produces the X-ray beam with controlled quality and intensity.

This shows how transformer action, rectification, stabilization, and control all work together to produce a clinically useful X-ray beam.

---

## 15. Final summary

X-ray circuits are designed to convert the incoming mains supply into a suitable high-voltage, low-current supply for the X-ray tube and a controlled low-voltage supply for the filament. Transformers provide the necessary voltage conversion and are subject to losses from copper resistance, hysteresis, and eddy currents. High-tension generators supply the large tube voltage required for X-ray production, while rectifiers convert AC to the pulsating or smoothed DC needed by the X-ray tube. Self-rectifier, bridge, and three-phase rectifier circuits differ in efficiency and output smoothness, with three-phase and high-frequency systems offering better performance.

Capacitance filters reduce ripple, while voltage and frequency compensators maintain stable tube output when the mains varies. The kV selector and kV compensator set and stabilize tube voltage, while the filament circuit and space charge compensation regulate tube current. These elements are all interrelated because they jointly determine the beam quality and intensity, and therefore the image quality, exposure dose, and reliability of the X-ray system.

---

## 16. Short exam-oriented conclusion

X-ray circuits use transformers to increase mains voltage to the high tension needed by the X-ray tube and to provide the lower filament supply. Rectification converts AC to DC, and half-wave, bridge, and three-phase rectifiers differ in output smoothness and efficiency. Filters and stabilizers reduce ripple and maintain constant output despite mains fluctuations. The kV selector and kV compensator control tube voltage, while the filament circuit and space charge compensation control tube current. High-frequency generators improve performance by providing more stable and efficient power conversion. All these components are interrelated because together they control the X-ray beam’s energy, intensity, and reproducibility, which determine image quality and patient dose.
