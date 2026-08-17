# Interactions of X-Rays, Gamma Rays and Beta Rays with Matter

## 1. Introduction

When ionizing radiation passes through matter, it interacts with atoms and molecules in the material. These interactions determine how much radiation is transmitted, absorbed, scattered, or attenuated. This is central to radiology, radiation protection, shielding, and the biological effects of radiation.

The most important radiations in this context are:

- X-rays
- gamma rays
- beta rays

Each interacts with matter in characteristic ways, but all follow the same general principle: radiation loses energy as it passes through matter, and the amount of attenuation depends on beam energy, material density, atomic number, and thickness.

This topic includes:

- transmission through matter
- exponential attenuation law
- half-value layer (HVL)
- linear attenuation coefficient
- interaction mechanisms
- classical scattering
- Compton scattering
- photoelectric absorption
- pair production
- practical aspects of radiation absorption and transmission through body tissue

These are all closely related because they describe different aspects of the same physical process: the progressive removal of photons or particles from a beam as they traverse matter.

---

## 2. Transmission through matter

Transmission means the fraction of radiation that passes through a material without being absorbed or scattered out of the beam.

When a beam of X-rays or gamma rays passes through tissue, some photons are absorbed, some are scattered, and the rest emerge from the other side.

The transmitted intensity depends on:

- initial intensity
- beam energy
- thickness of the absorber
- density of the material
- atomic number of the material
- attenuation properties of the material

### 2.1 Transmission and attenuation

Transmission is the opposite of attenuation.

- attenuation = reduction in intensity due to absorption and scattering
- transmission = the surviving radiation after attenuation

If a beam enters a material with intensity I0 and emerges with intensity I, then the degree of attenuation is determined by how much energy is removed from the beam.

---

## 3. Law of exponential attenuation

The attenuation of a narrow, monoenergetic beam through a uniform material follows an exponential law.

I = I0 e^{-μx}

where:

- I0 = initial beam intensity
- I = transmitted intensity after thickness x
- μ = linear attenuation coefficient
- x = thickness of absorber

This law is fundamental because it shows that radiation intensity decreases exponentially as it passes through matter.

### 3.1 Meaning of the law

The beam does not lose radiation in a linear way. Instead, a constant fraction of the remaining photons is removed per unit thickness.

This means:

- first centimeter removes a certain fraction of the beam
- second centimeter removes the same fraction of what remains
- the intensity falls exponentially rather than linearly

### 3.2 Why the law is important

It explains:

- why thicker materials reduce transmission more than thinner ones
- why shielding works
- why radiation dose falls with thickness
- why tissue attenuation is different for different energies

### 3.3 Example

If a beam passes through 1 cm of material and loses 50% of its intensity, then a second 1 cm may lose another 50% of the remainder, leaving 25% total. This is exponential behavior.

---

## 4. Half value layer (HVL)

The half-value layer is the thickness of a material required to reduce the intensity of a beam to one-half of its original value.

### 4.1 Definition

When I = I0/2,

I0/2 = I0 e^{-μx}

So:

1/2 = e^{-μx}

Taking natural logarithms:

x = 0.693 / μ

This thickness is the half-value layer:

HVL = 0.693 / μ

### 4.2 Meaning

The HVL measures the penetrating power of a beam.

- higher HVL = more penetrating beam
- lower HVL = less penetrating beam

### 4.3 Importance in radiology and shielding

The HVL is used to:

- describe beam quality
- compare beam penetration
- choose filters and shielding materials
- determine required thickness of protective materials

### 4.4 Example in practice

A 100 kVp X-ray beam may have a certain HVL in aluminium. If the HVL is 2 mm Al, then a 2 mm layer reduces the beam to half its intensity. Another 2 mm reduces it to one quarter, and so on.

---

## 5. Linear attenuation coefficient

The linear attenuation coefficient μ is the measure of how strongly a material attenuates a beam per unit thickness.

### 5.1 Definition

In the attenuation equation:

I = I0 e^{-μx}

μ is the linear attenuation coefficient.

### 5.2 Units

The linear attenuation coefficient is measured in cm^-1 or m^-1.

### 5.3 Interpretation

Larger μ means stronger attenuation.

This depends on:

- beam energy
- material density
- atomic number
- interaction probability in that material

### 5.4 Dependence on photon energy

For X-rays and gamma rays, μ generally decreases as the beam energy increases up to a certain point, but the exact behavior depends on the interaction mechanisms.

This is crucial because low-energy photons are attenuated more strongly than high-energy photons.

### 5.5 Mass attenuation coefficient

Sometimes the attenuation is described as mass attenuation coefficient μ/ρ, where ρ is density.

This allows comparison of different materials independent of density.

---

## 6. Interaction of radiation with matter

Radiation interacts with matter through different processes. The dominant interaction depends on:

- type of radiation
- energy of the radiation
- atomic number of the material
- density of the material

### 6.1 X-rays and gamma rays

These are photons and interact mainly by:

- classical scattering
- Compton scattering
- photoelectric absorption
- pair production (for high-energy photons)

### 6.2 Beta rays

Beta particles are electrons or positrons. Their interactions include:

- ionization
- excitation
- bremsstrahlung
- annihilation (for positrons)

Although beta particles are not photons, their attenuation in matter is also exponential, though their behavior differs from X-rays and gamma rays.

---

## 7. Classical scattering

Classical scattering, also called coherent or Rayleigh scattering, occurs when an incoming photon interacts with the whole atom and causes the atom to oscillate. The photon is scattered without losing significant energy.

### 7.1 Characteristics

- low-energy photon interaction
- no energy transfer to electrons in a significant way
- scattering occurs with little change in wavelength
- more important at low photon energies

### 7.2 Role in radiology

Classical scattering is generally less important in diagnostic radiology because high-energy photons are more likely to undergo Compton scattering or photoelectric absorption.

### 7.3 Why it matters

It contributes to small-angle scattering and can affect image quality at lower energies, but it is much less dominant than Compton scattering in most diagnostic beams.

---

## 8. Compton scattering

Compton scattering is the most important interaction for diagnostic X-ray energies in soft tissue.

### 8.1 Process

A photon collides with a loosely bound or free electron. The electron is ejected, and the photon is scattered with reduced energy and changed direction.

### 8.2 Result

- photon loses part of its energy
- electron is displaced from the atom
- scattered photon may continue in a different direction

### 8.3 Why it is important

Compton scattering is important because it:

- contributes to scattered radiation
- reduces image contrast
- increases occupational exposure
- reduces image quality if not controlled

### 8.4 Dependence on photon energy and material

Compton scattering depends largely on electron density rather than atomic number. In soft tissue, this is why it becomes a major interaction process over a broad range of diagnostic energies.

### 8.5 Clinical importance

In body tissue, scattered photons can reach the detector in unwanted directions or irradiate staff. This is why collimation, grids, and protective shielding are used.

---

## 9. Photoelectric absorption

Photoelectric absorption is another major interaction of X-rays and gamma rays with matter, especially at lower photon energies and in materials with high atomic number.

### 9.1 Process

A photon transfers all of its energy to an inner-shell electron, which is ejected from the atom. The atom becomes ionized and the vacancy is filled by outer-shell electrons, producing characteristic radiation or Auger electrons.

### 9.2 Dependence on atomic number

The probability of photoelectric absorption is strongly dependent on the atomic number Z of the absorber.

It approximately follows:

P ∝ Z^3 / E^3

This very strong dependence on Z is why bone (high Z) absorbs X-rays much more than soft tissue (lower Z).

### 9.3 Dependence on energy

As photon energy increases, the probability of photoelectric absorption decreases sharply.

Thus, low-energy photons are preferentially absorbed by bone and other high-Z tissues.

### 9.4 Importance in imaging

This effect is essential for radiographic contrast, because different tissues absorb X-rays differently. It gives contrast between:

- bone and soft tissue
- metal and tissue
- contrast agents and surrounding tissue

### 9.5 Biological significance

Photoelectric effect contributes to patient dose because energy is absorbed in tissue. This is why low-energy beams may increase dose in superficial tissues if not filtered properly.

---

## 10. Pair production

Pair production occurs at high photon energies, usually above 1.02 MeV.

### 10.1 Process

A photon interacts with the electric field of a nucleus and is converted into an electron-positron pair.

The process requires the energy of the photon to exceed the rest mass energy of the electron-positron pair:

2mec^2 ≈ 1.02 MeV

### 10.2 Importance

This interaction is not significant in ordinary diagnostic radiology because diagnostic X-ray energies are much lower than 1 MeV. However, it is important in:

- high-energy radiotherapy
- linear accelerators
- radiation therapy beams
- high-energy physics

### 10.3 Result

After pair production, the electron and positron lose energy by ionization and excitation, and the positron eventually annihilates with an electron, producing two 511 keV gamma photons.

---

## 11. Beta rays and their interaction with matter

Beta radiation consists of electrons or positrons ejected from the nucleus.

### 11.1 Beta-minus particles

These are electrons. They are lighter than alpha particles and have greater penetration, but lower ionization power than alpha.

### 11.2 Beta-plus particles

These are positrons. They can annihilate with electrons and produce gamma photons.

### 11.3 Interaction with matter

Beta particles lose energy mainly by:

- ionization
- excitation
- bremsstrahlung

They are more penetrating than alpha particles but less penetrating than gamma rays.

### 11.4 Practical importance

Beta emitters are used in nuclear medicine and research. Their radiation danger depends on whether they are external or internal sources.

- external beta radiation is less penetrating and may be stopped by a few millimeters of plastic or tissue
- internal beta emitters can be dangerous because they irradiate tissue continuously from inside the body

---

## 12. Practical aspects of radiation absorption and transmission through body tissue

Body tissue is a complex absorber. The attenuation of X-rays or gamma rays through the body depends on several factors.

### 12.1 Body tissues have different densities and atomic numbers

Examples:

- air: low density, low attenuation
- fat: low density
- muscle: moderate density
- bone: high density and higher atomic number

This difference leads to contrast in radiographic images.

### 12.2 Soft tissue attenuation

In soft tissue, Compton scattering is often the dominant interaction in diagnostic energy ranges. This is because soft tissue has relatively low atomic number and a moderate electron density.

### 12.3 Bone attenuation

Bone absorbs more radiation than soft tissue because it has higher density and higher effective atomic number. This leads to greater photoelectric absorption and therefore stronger attenuation.

### 12.4 Beam energy and tissue penetration

High-energy photons pass through tissue more easily than low-energy photons. This is why higher kVp beams are used for thick body parts and lower energy beams are used when skin dose must be reduced.

### 12.5 Patient dose and image formation

The same attenuation mechanisms determine both image contrast and patient dose:

- some photons must be absorbed to form image contrast
- too much absorption contributes to dose
- too much scatter reduces image quality

This is why radiographic technique must be balanced.

### 12.6 Shielding and protection

The attenuation law and HVL are used to calculate how much shielding is required. Materials such as lead, concrete, and steel reduce beam intensity by absorbing photons through photoelectric and Compton processes.

### 12.7 Practical clinical significance

For patient safety:

- use the lowest dose consistent with image quality
- use proper filtration
- use shielding where appropriate
- consider body habitus and organ sensitivity

This makes the physics of attenuation directly relevant to radiological protection.

---

## 13. How all these topics are related

The concepts in this topic are all parts of the same process: as radiation passes through matter, its intensity decreases and its energy is redistributed through absorption and scattering.

### The chain is as follows:

1. A beam of X-rays, gamma rays, or beta particles enters matter.
2. The photons or particles interact with atoms and electrons.
3. Depending on energy and material, interactions occur by:
   - coherent scattering
   - Compton scattering
   - photoelectric absorption
   - pair production (at high energy)
   - ionization and excitation (for beta particles)
4. These interactions remove photons or energy from the beam.
5. The reduction in intensity follows the exponential attenuation law.
6. The thickness required to reduce intensity by half is the half-value layer.
7. The value μ describes how much attenuation occurs per unit thickness.
8. The attenuation and transmission characteristics determine dose, shielding, and image quality.

### Example

A diagnostic X-ray beam passes through soft tissue and bone. The low-energy photons are attenuated strongly by photoelectric absorption in bone, while the higher-energy photons are more likely to pass through. Compton scatter also contributes to reducing contrast if not controlled. The result is differential attenuation, which creates the image, but also exposes tissue to dose.

This shows how attenuation physics directly affects both imaging and radiation safety.

---

## 14. Final summary

The interaction of X-rays, gamma rays, and beta rays with matter is governed by the same principle: radiation loses intensity as it passes through material because of absorption and scattering. This is described by the exponential attenuation law, I = I0 e^{-μx}, and quantified by the linear attenuation coefficient μ and the half-value layer HVL. The probability and type of interaction depend on the radiation energy and the material, with photoelectric absorption dominating at low photon energy in high-Z materials, Compton scattering dominating in soft tissue at diagnostic energies, and pair production occurring at very high energies. Beta particles interact mainly by ionization, excitation, bremsstrahlung, and annihilation. In body tissue, these interactions determine patient dose, image contrast, shielding, and the safety of radiological procedures.

These topics are all closely related because they are different ways of describing how radiation is attenuated and transmitted through matter. That is the foundation of medical imaging, radiation protection, and dosimetry.

---

## 15. Short exam-oriented conclusion

X-rays, gamma rays, and beta rays interact with matter by different mechanisms, but all cause attenuation of the beam as it passes through material. The reduction in intensity follows the exponential attenuation law, I = I0 e^{-μx}, where μ is the linear attenuation coefficient. The half-value layer is the thickness that reduces beam intensity to half, and it is a practical measure of beam penetrability. The main photon interactions are classical scattering, Compton scattering, photoelectric absorption, and pair production, while beta particles interact mainly by ionization and excitation. In body tissue, these interactions determine absorption, transmission, image contrast, and patient dose. Therefore, transmission, attenuation, HVL, coefficients, and interaction mechanisms are all directly related and form the basic physics of radiation absorption in matter.
