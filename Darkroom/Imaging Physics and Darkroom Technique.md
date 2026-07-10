# Imaging Physics and Darkroom Techniques

## Image Characteristics – Detailed Explanation

Image characteristics describe the quality of an image and determine how accurately anatomical structures or objects can be visualized. Every characteristic is related to the others. A good medical image is a balance of:

- brightness (density)
- contrast
- sharpness
- resolution
- noise

---

## 1. What Is an Image?

An image is a visual representation of an object formed when light, X-rays, or other electromagnetic radiation interacts with that object.

In medical imaging, the image represents the internal anatomy of the human body. The image is formed because different tissues absorb, transmit, reflect, or emit different amounts of radiation.

### Simple Example

Suppose you shine a flashlight on your hand:

- Skin reflects some light.
- Some light passes through thin areas.
- Bones block most light.

The resulting pattern is an image. The same principle occurs in X-ray imaging.

### Image Formation Process

Energy Source

↓

Object (Patient)

↓

Interaction with tissues

↓

Detector / Film

↓

Visible Image

### Types of Images Based on Light

Images can be classified according to how light reaches our eyes. There are three main types:

- Reflected image
- Transmitted image
- Emitted image

---

## 2. Reflected Light Image

### Definition

A reflected image is formed when light strikes an object and bounces back into our eyes. The object itself does not produce light; it only reflects incoming light.

### Examples

- Human face
- Books
- Furniture
- Printed X-ray film
- Photograph

### Formation

Light Source

↓

Object

↙ ↘

Reflected Light

↓

Eye

### Factors Affecting Reflection

- Surface texture
  - Smooth surface → regular reflection
  - Rough surface → diffuse reflection
- Color
  - White objects reflect most light
  - Black objects absorb most light

### Medical Example

When viewing an X-ray film on a lightbox, the eye sees reflected light from the film.

---

## 3. Transmitted Light Image

### Definition

A transmitted image is formed when light passes through an object. Different parts absorb different amounts of light, and the remaining transmitted light forms the image.

### Examples

- X-ray image
- CT image
- Shadow puppets
- Window glass

### Formation

Light / X-rays

↓

Patient

↓ ↓

Absorbed   Transmitted

↓

Detector

### Medical Imaging

This is the most important image type in radiology. Different tissues absorb X-rays at different rates.

| Tissue | X-ray Transmission |
|---|---|
| Air | Very high |
| Fat | High |
| Muscle | Moderate |
| Bone | Low |
| Metal | Very low |

This difference creates contrast.

---

## 4. Emitted Light Image

### Definition

An emitted image is formed when the object itself produces light. No external light source is necessary.

### Examples

- Television
- LED screen
- Fluorescent screen
- Fire
- Sun
- Digital monitor

### Medical Example

Digital radiography images displayed on a computer monitor are emitted images. The monitor emits light directly.

### Formation

Electronic Signal

↓

Display

↓

Emitted Light

↓

Eye

### Comparison of Image Types

| Image Type | Light Source | Example |
|---|---|---|
| Reflected | External | Book |
| Transmitted | Through object | X-ray |
| Emitted | Object itself | LCD monitor |

---

## 5. Noise

Noise is any unwanted random signal that reduces image quality. It makes images grainy and can hide important anatomical details.

### Why Noise Occurs

Noise can come from:

- Random photon arrival
- Electronic interference
- Film fog
- Scatter radiation
- Detector limitations

### Visual Example

Without noise:

████████████
████████████
████████████

With noise:

███▓████▒██
████▒██▓███
██▓██████▒█

The anatomical information becomes difficult to see.

### Types of Noise

The two major types are:

- Fog
- Quantum noise

#### 5.1 Fog

**Definition:** Fog is unwanted uniform darkening of the image that reduces contrast.

**Causes:**

- Film fog
  - Ageing film
  - Improper storage
  - Heat
  - Humidity
  - Radiation exposure
- Processing fog
  - High developer temperature
  - Excess development time
- Radiation fog
  - Scatter radiation

**Effect:**

- Normal image: clear black, white, and gray tones
- Fogged image: everything appears gray and differences between structures decrease

#### 5.2 Quantum Noise

**Definition:** Quantum noise occurs because X-ray photons arrive randomly. Too few photons produce a grainy image.

**Cause:**

Low exposure → few photons → statistical fluctuation → noise

**Example:**

Imagine rainfall:

- Heavy rain: every bucket gets nearly equal water
- Light rain: some buckets get many drops, others few

The variation in photon arrival is quantum noise.

**Relationship:**

- Photon number ↑ → quantum noise ↓
- Photon number ↓ → quantum noise ↑

---

## 6. Signal-to-Noise Ratio (SNR)

### Definition

SNR compares useful information (signal) to unwanted information (noise).

### Formula

SNR = Signal / Noise

### Examples

- High SNR: signal = 100, noise = 10 → SNR = 10 → excellent image
- Low SNR: signal = 20, noise = 20 → SNR = 1 → poor image

### Factors That Increase SNR

- Higher X-ray exposure
- Better detector performance
- Longer acquisition time
- Less electronic noise

### Effect

Higher SNR → cleaner image → better diagnosis

---

## 7. Contrast

### Definition

Contrast is the difference in brightness between adjacent areas of an image.

- High contrast: strong black and white separation, little gray
- Low contrast: many shades of gray

### Example

High contrast:

████░░░░
████░░░░
████░░░░

Low contrast:

████▓▒░░
██▓▒░░░░

### Factors Affecting Contrast

- Patient thickness
- kVp
- Scatter radiation
- Film characteristics
- Detector type
- Processing conditions

### Optimum Contrast

Optimum contrast is the best balance between black and white for diagnosis. It is not the maximum or minimum contrast.

- Too much contrast can lose soft tissue detail.
- Too little contrast can make structures blend together.

### Examples for Different Exams

- Chest X-ray: moderate contrast
- Bone X-ray: high contrast
- Mammography: very low contrast

---

## 8. Sharpness

### Definition

Sharpness is the ability to display edges clearly.

- Sharp image: crisp edges
- Blurred image: fuzzy edges

### Causes of Blur

- Patient movement
- Tube movement
- Large focal spot
- Detector movement
- Poor focus

### Types of Blur

- Motion blur
- Geometric blur
- Detector blur

### Improving Sharpness

- Use a small focal spot
- Use a short exposure time
- Position the patient carefully
- Use a high-resolution detector

---

## 9. Resolution

### Definition

Resolution is the ability to distinguish two closely spaced structures.

### Example

Good resolution:

|| ||

Poor resolution:

████

### Types of Resolution

- Spatial resolution: ability to see small objects, measured in line pairs/mm
- Contrast resolution: ability to distinguish objects with similar densities, important in CT and MRI
- Temporal resolution: ability to image moving structures, important in cardiac CT and fluoroscopy

### Factors Affecting Resolution

- Pixel size
- Detector quality
- Motion
- Magnification
- Focal spot size
- Sampling frequency

---

## 10. Relationship Between Image Characteristics

### How They Interconnect

- Noise affects SNR
- SNR affects image clarity
- Contrast affects tissue visibility
- Sharpness improves edge definition
- Resolution determines the detail that can be distinguished

### Correlation Table

| Characteristic | Affects | Explanation |
|---|---|---|
| Noise ↑ | SNR ↓ | More unwanted signal reduces image clarity |
| SNR ↑ | Image quality ↑ | A stronger useful signal compared to noise produces clearer images |
| Contrast ↑ | Visibility ↑ | Differences between tissues become easier to detect |
| Optimum contrast | Diagnostic accuracy ↑ | Best level depends on anatomy and imaging task |
| Sharpness ↑ | Resolution ↑ | Clearer edges help distinguish fine details |
| Resolution ↑ | Small structures visible | High resolution allows separation of closely spaced objects |
| Motion ↑ | Sharpness ↓ / Resolution ↓ | Motion blur softens edges and reduces detail |
| Quantum noise ↑ | Contrast perception ↓ | Graininess can mask low-contrast structures |

### Image Quality Flow

X-ray / Light Source

↓

Patient or Object

↓

Reflection / Transmission / Emission

↓

Detector or Film

↓

Image Produced

├─ Noise (Fog + Quantum Noise)
├─ Signal (Useful Information)

↓

Signal-to-Noise Ratio (SNR)

↓

Contrast

↓

Sharpness

↓

Resolution

↓

Final Diagnostic Image Quality

---

## Key Takeaway

These concepts are tightly interconnected. Noise reduces the visibility of useful information and lowers SNR. A higher SNR supports better contrast perception. Appropriate contrast makes anatomical differences visible without losing detail. Sharpness preserves edge clarity, while resolution determines how well tiny or closely spaced structures can be separated. Together, these characteristics determine whether an image is of sufficient quality for accurate diagnosis.

Fog is unwanted uniform darkening of the image.

It reduces image contrast.

Causes

Film fog

Ageing film
Improper storage
Heat
Humidity
Radiation exposure

Processing fog

High developer temperature
Excess development time

Radiation fog

Scatter radiation

Effect

Normal Image

Black
White
Gray

Fogged Image

Everything becomes gray.

Difference between structures decreases.

B. Quantum Noise
Definition

Quantum noise occurs because X-ray photons arrive randomly.

Too few photons produce a grainy image.

Cause

Low exposure

↓

Few photons

↓

Statistical fluctuation

↓

Noise

Example

Imagine rain.

Heavy rain

Every bucket gets nearly equal water.

Light rain

Some buckets receive many drops.

Others receive few.

Variation increases.

This variation is quantum noise.

Relationship

Photon number ↑

↓

Quantum noise ↓

Photon number ↓

↓

Quantum noise ↑

6. Signal-to-Noise Ratio (SNR)

One of the most important image quality measures.

Definition

SNR compares useful information (signal) to unwanted information (noise).

Formula
SNR=
Noise
Signal
	​

High SNR

Signal = 100

Noise = 10

SNR = 10

Excellent image

Low SNR

Signal = 20

Noise = 20

SNR = 1

Poor image

Factors Increasing SNR

Increase X-ray exposure

Better detector

Longer acquisition

Less electronic noise

Effect

Higher SNR

↓

Cleaner image

↓

Better diagnosis

7. Contrast
Definition

Contrast is the difference in brightness between adjacent areas of an image.

High contrast

Black and white

Little gray

Low contrast

Many shades of gray

Formula

Contrast depends on

Difference in intensity

High Contrast Example
████░░░░
████░░░░
████░░░░
Low Contrast
████▓▒░░
██▓▒░░░░

Everything appears similar.

Factors Affecting Contrast

Patient thickness

kVp

Scatter radiation

Film characteristics

Detector

Processing

High vs Low Contrast

High contrast

Advantages

Bone imaging
Detect fractures

Disadvantages

Soft tissues difficult.

Low contrast

Advantages

Soft tissue visualization

Disadvantages

Bones less obvious.

8. Optimum Contrast
Definition

Optimum contrast means the best balance between black and white for diagnosis.

Not maximum contrast.

Not minimum contrast.

Why?

Too much contrast

Loss of soft tissue detail.

Too little contrast

Structures blend together.

Example

Chest X-ray requires moderate contrast.

Bone X-ray requires high contrast.

Mammography requires very low contrast.

Different examinations require different optimum contrast.

9. Sharpness
Definition

Sharpness is the ability to display edges clearly.

Sharp image

Edges are crisp.

Blurred image

Edges are fuzzy.

Causes of Blur

Patient movement

Tube movement

Large focal spot

Detector movement

Poor focus

Types

Motion blur

Geometric blur

Detector blur

Factors Improving Sharpness

Small focal spot

Short exposure time

Good positioning

High-resolution detector

10. Resolution

Resolution tells how well two close objects can be seen separately.

Definition

Resolution is the ability to distinguish two closely spaced structures.

Example
|| ||

Good resolution

Two separate lines.

Poor resolution

████

Both merge together.

Types
Spatial Resolution

Ability to see small objects.

Measured in

Line pairs/mm

Higher line pairs

↓

Better resolution

Contrast Resolution

Ability to distinguish objects having similar densities.

Very important in CT and MRI.

Temporal Resolution

Ability to image moving structures.

Important in

Cardiac CT
Fluoroscopy
Factors Affecting Resolution

Pixel size

Detector

Motion

Magnification

Focal spot size

Sampling frequency

Relationship Between All Image Characteristics
               IMAGE QUALITY
                     │
     ┌───────────────┼───────────────┐
     │               │               │
 Contrast        Resolution       Noise
     │               │               │
     │               │               │
 Sharpness       Spatial Detail     SNR
     │               │               │
     └───────────────┼───────────────┘
                     │
            Diagnostic Accuracy
How They Are Correlated
Characteristic	Affects	Explanation
Noise ↑	SNR ↓	More unwanted signal reduces image clarity.
SNR ↑	Image quality ↑	A stronger useful signal compared to noise produces clearer images.
Contrast ↑	Visibility ↑	Differences between tissues become easier to detect. Excessive contrast, however, can hide subtle soft-tissue differences.
Optimum contrast	Diagnostic accuracy ↑	The best contrast level depends on the anatomy and imaging task.
Sharpness ↑	Resolution ↑	Clearer edges help distinguish fine details.
Resolution ↑	Small structures visible	High resolution allows separation of closely spaced objects.
Motion ↑	Sharpness ↓ and Resolution ↓	Motion blur softens edges and reduces the ability to resolve details.
Quantum noise ↑	Contrast perception ↓	Graininess can mask low-contrast structures, making them harder to detect.
Overall Flow of Image Formation and Quality
X-ray / Light Source
          │
          ▼
Patient or Object
          │
          ▼
Reflection / Transmission / Emission
          │
          ▼
Detector or Film
          │
          ▼
Image Produced
          │
          ├── Noise (Fog + Quantum Noise)
          ├── Signal (Useful Information)
          │
          ▼
Signal-to-Noise Ratio (SNR)
          │
          ▼
Contrast
          │
          ▼
Sharpness
          │
          ▼
Resolution
          │
          ▼
Final Diagnostic Image Quality
Key takeaway

These concepts are tightly interconnected. Noise reduces the visibility of useful information and lowers SNR. A higher SNR supports better contrast perception. Appropriate (optimum) contrast makes anatomical differences visible without losing detail. Sharpness preserves edge clarity, while resolution determines how well tiny or closely spaced structures can be separated. Together, these characteristics determine whether an image is of sufficient quality for accurate diagnosis.