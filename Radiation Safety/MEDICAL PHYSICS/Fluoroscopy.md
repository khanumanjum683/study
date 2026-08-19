 # Fluoroscopy

## 1. Introduction

Fluoroscopy is an X-ray imaging technique that produces real-time or near-real-time images of moving anatomy, instruments, and contrast media. It is used in gastrointestinal studies, angiography, cardiac imaging, interventional procedures, catheter placement, and surgical guidance.

The complete fluoroscopic chain is:

X-ray tube -> patient -> image receptor -> image conversion and processing -> monitor -> recording or archive

The main difficulty is that fluoroscopy must produce a useful image from relatively few X-ray photons while exposures may continue for a long time. Image intensifiers and modern digital detectors solve this problem by converting the faint transmitted X-ray pattern into a brighter electronic image.

---

## 2. Direct fluoroscopy

Direct fluoroscopy is the older method in which the transmitted X-rays fall directly on a fluorescent screen.

### Construction and working

The screen contains a fluorescent phosphor. X-rays are converted into visible light, and the observer views the faint image through a viewing system, usually after dark adaptation.

### Limitations

- low brightness
- poor contrast and spatial resolution
- considerable observer fatigue
- dark adaptation required
- relatively high patient dose for a useful image
- no convenient electronic storage or processing
- observer exposure risk if positioned near the patient

Direct fluoroscopy was largely replaced by image intensifiers and flat-panel detectors because electronic systems provide a brighter image, remote viewing, processing, and recording.

---

## 3. Image intensifier

An image intensifier is an evacuated electronic device that converts a faint X-ray image into a brighter visible-light image.

### Main parts

From the entrance side to the output side, it contains:

- protective entrance window
- input phosphor
- photocathode
- electrostatic focusing lenses
- accelerating anode
- output phosphor
- evacuated envelope

### Input phosphor

The input phosphor converts X-rays into light. Caesium iodide is commonly used in needle-like crystals. The crystals guide light toward the photocathode and reduce lateral spread, helping preserve detail.

### Photocathode

The photocathode converts the light image into an electron image. The number of emitted electrons at each point is related to the local intensity of the input X-ray image.

### Electrostatic lenses

Electrostatic fields focus the electrons so that the spatial pattern of the original image is preserved while the electron image travels toward the output phosphor.

### Accelerating anode

The anode is positive relative to the photocathode. It accelerates the electrons, increasing their energy before they strike the output phosphor.

### Output phosphor

The output phosphor converts the accelerated electron image into a bright visible-light image. The output image is small and can be coupled to a camera or electronic detector.

---

## 4. Principles of image intensification

Image intensification increases image brightness mainly through minification gain and flux gain.

### 4.1 Minification gain

The input phosphor has a much larger diameter than the output phosphor. Electrons from the large input area are focused onto the smaller output area, concentrating image information and increasing brightness.

Minification gain is approximately:

Minification gain = (input diameter / output diameter)^2

### 4.2 Flux gain

The electrons are accelerated through a high voltage. Each electron has more energy when it reaches the output phosphor and produces more light. This increase is called flux gain.

### 4.3 Brightness gain

Brightness gain is approximately:

Brightness gain = minification gain x flux gain

This makes the image bright enough for continuous viewing with a much lower dose rate than direct fluoroscopy would require.

### 4.4 Conversion and dose

The image intensifier improves the efficiency of converting transmitted X-rays into a visible image. However, lower dose operation is not guaranteed. Automatic brightness control may increase tube output when the patient is thick, when magnification is selected, or when the field is heavily attenuated.

---

## 5. Automatic brightness control

Automatic brightness control, also called automatic dose-rate control, monitors the image signal and adjusts the X-ray exposure factors to maintain a selected display brightness.

It may change:

- tube voltage
- tube current
- pulse duration
- pulse rate
- filtration

If patient thickness increases, fewer photons reach the receptor. The system may increase tube output to preserve brightness. Consequently, a stable-looking image can conceal an increase in patient dose.

The operator should therefore use appropriate collimation, filtration, pulse rate, magnification mode, and fluoroscopy time.

---

## 6. Image quality in fluoroscopy

Fluoroscopic image quality depends on the X-ray beam, patient attenuation and scatter, receptor performance, optics, display, and recording system.

### 6.1 Unsharpness

Unsharpness is the loss of definition at object boundaries. It may result from:

- focal-spot size
- geometric magnification
- patient or instrument motion
- phosphor light spread
- electron spreading
- imperfect focusing
- optical blur
- detector sampling

Motion unsharpness is particularly important in fluoroscopy. Short exposure pulses and an adequate frame rate help freeze moving anatomy.

### 6.2 Noise

Noise is random variation that obscures small differences in the image. Quantum noise is important because fluoroscopy often uses a limited number of photons per frame.

Noise increases with:

- lower dose per frame
- thick patients
- smaller fields or magnification modes if output is not increased
- reduced photon transmission

Noise can be reduced by increasing photon number, frame averaging, recursive processing, or spatial filtering, but increasing exposure has a patient-dose cost.

### 6.3 Spatial resolution

Spatial resolution is the ability to distinguish small, closely spaced objects. It is affected by:

- focal-spot size
- input phosphor structure
- electron focusing
- output phosphor
- optical coupling
- camera or digital detector sampling
- display matrix

Magnification mode can improve resolution by using a smaller central portion of the input phosphor, but automatic brightness control may increase dose.

### 6.4 Contrast resolution

Contrast resolution is the ability to distinguish objects with small differences in signal. It is affected by subject contrast, scatter, noise, detector efficiency, processing, and display settings.

Collimation reduces scatter production, while grids, air gaps, and image processing reduce the effect of scatter on the displayed image.

### 6.5 Distortion

Distortion occurs when the displayed image does not preserve the true shape or position of the object.

Important forms include:

- pincushion distortion: magnification is greater near the edges
- S-distortion: magnetic fields deflect the electron image
- vignetting: brightness decreases toward the edge

Distortion is related to the curved input surface, electron trajectories, focusing fields, and external magnetic fields.

---

## 7. Spectral emission and gas spots

### 7.1 Spectral emission

The input phosphor emits light after absorbing X-rays, and the photocathode must be sensitive to that light. The output phosphor emits light that must match the response of the optical lens, television camera, CCD/CMOS sensor, or other recording device.

Efficient operation requires good spectral matching between:

- input phosphor emission
- photocathode sensitivity
- output phosphor emission
- optical and camera response

Poor matching reduces brightness and may reduce contrast or recording efficiency.

### 7.2 Gas spots

Gas spots are localized bright artifacts caused by gas contamination or gas release inside the image-intensifier envelope. They remain fixed relative to the intensifier and may appear as bright spots or irregular regions even when the patient image changes.

Gas spots are different from quantum noise because they are stationary and persistent. They may indicate deterioration of vacuum integrity or internal damage. Quality-control assessment is required, and severe defects may require servicing or replacement.

---

## 8. Multi-field image intensifiers

A multi-field image intensifier has selectable input field sizes, commonly large, medium, and small.

### 8.1 Principle of field selection

The focusing voltages are changed so that electrons from a selected portion of the input phosphor are directed to the output phosphor. The output image remains approximately the same size, so a smaller selected input area appears magnified.

### 8.2 Large field

The large field provides:

- broad anatomical coverage
- a large field of view
- lower geometric magnification

It usually provides less detail than a smaller magnification field.

### 8.3 Small field or magnification mode

The small field uses the central part of the input phosphor and magnifies it to the output. It provides:

- improved spatial resolution
- better visibility of small structures

Limitations include:

- reduced field of view
- greater image noise if photon statistics are poor
- increased dose because automatic brightness control may raise output

### 8.4 Relationship between field, resolution, and dose

Selecting a smaller field improves resolution but may increase patient dose. This is a direct example of the balance between diagnostic detail and radiation protection.

---

## 9. Lens system and image distribution

### 9.1 Electrostatic lens system

The electrostatic lens system uses electric fields to focus electrons from the photocathode onto the output phosphor. Correct focusing maintains image sharpness and uniformity.

Incorrect focusing can cause blur, non-uniform brightness, and loss of resolution.

### 9.2 Optical coupling

The output image can be coupled to the viewing and recording system by:

- optical lenses
- fibre-optic bundles
- mirrors
- television cameras
- CCD or CMOS sensors
- digital flat-panel or camera systems

Every conversion stage can affect brightness, resolution, noise, lag, and distortion.

### 9.3 Image distribution

The signal may be distributed to:

- an operator monitor
- a second procedure-room monitor
- a recording device
- a digital acquisition computer
- a hospital archive or network

Beam splitters or electronic distribution circuits allow simultaneous viewing and recording. The distribution system must preserve adequate signal quality at each destination.

---

## 10. Viewing fluoroscopic images

The output image is displayed on a monitor after optical or electronic conversion.

Important display requirements include:

- adequate brightness
- adequate contrast
- sufficient spatial resolution
- appropriate refresh rate
- low display noise
- stable calibration

The frame rate determines temporal resolution. Higher frame rates show motion more smoothly but may increase patient dose. Lower frame rates reduce dose but may make fast motion appear discontinuous.

Image-processing tools may include:

- last-image hold
- frame averaging
- recursive noise reduction
- edge enhancement
- window and level adjustment
- subtraction processing

Last-image hold is particularly useful because the last frame can be viewed without continued X-ray exposure.

---

## 11. Recording fluoroscopic images

Recording allows images to be reviewed, documented, taught, measured, and archived.

### Film and photospot recording

Older systems used film or a photospot camera to record selected high-detail images. These systems could provide good detail but required processing and sometimes relatively high exposure.

### Cine recording

Cine systems record a rapid sequence of images. They are useful for cardiac and vascular studies but may produce high patient dose because of high frame rates and exposure requirements.

### Digital recording

Modern systems record digital frames and sequences. Digital recording provides:

- immediate review
- image processing
- frame selection
- subtraction techniques
- storage and network transmission
- dose and procedure documentation

The recorded image is not necessarily identical to the live image because recording may involve different resolution, compression, processing, or frame selection.

---

## 12. Radiation protection in fluoroscopy

Fluoroscopy may involve prolonged or repeated exposures. Protection requires:

- minimizing fluoroscopy time
- using pulsed fluoroscopy
- selecting the lowest suitable frame rate
- using last-image hold
- tight collimation
- appropriate filtration
- limiting magnification mode
- keeping the receptor close to the patient when possible
- keeping the X-ray tube as far from the patient as practical
- using protective barriers and personal shielding

Magnification and automatic brightness control are closely related to dose. A smaller intensifier field may improve resolution, but the system may increase tube output to maintain image brightness.

---

## 13. How all topics are co-related

The complete fluoroscopic process is:

1. The X-ray tube produces a selected spectrum and intensity.
2. The patient attenuates the beam and produces primary and scattered radiation.
3. The input phosphor converts transmitted X-rays into light.
4. The photocathode converts the light image into an electron image.
5. Electrostatic lenses focus and distribute the electrons.
6. Electron acceleration and minification produce brightness gain.
7. The output phosphor converts the electron image into visible light.
8. Optical or electronic systems send the image to monitors and recorders.
9. Multi-field selection changes field of view, resolution, and dose.
10. Processing and display determine the final visible image.

Direct fluoroscopy forms a faint image directly on a fluorescent screen. Image intensification increases brightness and permits remote viewing, processing, and recording. The receptor, lens system, field selection, monitor, and recording system together determine unsharpness, noise, resolution, distortion, and temporal performance.

Therefore, image quality and radiation dose cannot be considered separately. Increasing frame rate, magnification, or automatic brightness may improve the displayed image but can increase exposure. Collimation, filtration, pulsed operation, and last-image hold help maintain diagnostic quality with less dose.

---

## 14. Final summary

Fluoroscopy produces moving X-ray images. Direct fluoroscopy uses a fluorescent screen but has poor brightness and high dose requirements. An image intensifier improves brightness by converting X-rays to light, light to electrons, accelerating and focusing the electrons, and converting them back to light at a small output phosphor.

Brightness gain results from minification gain and flux gain. Multi-field intensifiers provide different fields and magnification modes, improving resolution but potentially increasing dose through automatic brightness control. Image quality is influenced by unsharpness, noise, resolution, contrast, distortion, spectral matching, gas spots, lens focusing, and display performance.

The image can be viewed on monitors and recorded by photospot, cine, or digital systems. Last-image hold, pulsed fluoroscopy, collimation, filtration, and appropriate field selection help reduce dose. All topics are co-related as one chain from X-ray production to patient interaction, image intensification, optical distribution, viewing, recording, and radiation protection.

## 15. Short exam-oriented conclusion

Fluoroscopy is real-time X-ray imaging. Direct fluoroscopy views a fluorescent screen directly, whereas an image intensifier produces a brighter image through input-phosphor conversion, photocathode emission, electrostatic focusing, electron acceleration, and output-phosphor conversion. Brightness gain is produced by minification and flux gain. Image quality depends on unsharpness, noise, resolution, contrast, distortion, spectral emission, gas spots, optical distribution, and display performance. Multi-field intensifiers provide different fields and magnification modes, but smaller fields may increase dose through automatic brightness control. Images are viewed on monitors and recorded by film, cine, or digital systems. These components are related as one imaging chain whose final balance determines diagnostic quality and patient dose.
