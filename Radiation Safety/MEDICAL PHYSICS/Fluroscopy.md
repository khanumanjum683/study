 # Fluoroscopy

## 1. Introduction

Fluoroscopy is an X-ray imaging method that produces images continuously or as a sequence of frames while the patient or an instrument is moving. It is used to observe motion, guide procedures, and visualize the passage of contrast media.

Fluoroscopy differs from ordinary radiography mainly because it provides real-time or near-real-time images. This requires an imaging receptor that is much more sensitive than a conventional screen-film system and an electronic or digital system for viewing and recording the image.

The complete fluoroscopic chain is:

X-ray tube → patient and contrast medium → image receptor → light/electronic signal → viewing system → recording or display

Historically, the receptor was viewed directly through a fluorescent screen. Modern systems use an image intensifier or a flat-panel detector, followed by optical or electronic image processing.

---

## 2. Direct fluoroscopy

Direct fluoroscopy is the older method in which X-rays emerging from the patient strike a fluorescent screen and produce visible light directly.

### 2.1 Construction

A direct fluoroscopic system contains:

- X-ray tube
- patient table or support
- fluorescent screen, often using a phosphor such as zinc cadmium sulfide
- protective viewing arrangement

### 2.2 Working

X-rays pass through the patient and interact with the fluorescent screen. The screen converts X-ray energy into visible light. The observer views the faint image through a dark-adapted optical system.

### 2.3 Limitations

- very low light output
- poor image brightness
- poor contrast and spatial resolution
- requires dark adaptation
- high patient dose for a usable image
- the observer cannot be close to the patient without radiation exposure
- no convenient electronic storage or processing

Direct fluoroscopy was largely replaced by image intensifiers and digital detectors because modern systems provide a brighter image with lower dose and allow monitoring and recording.

---

## 3. Image intensifier

An image intensifier is an evacuated electronic device that converts a relatively faint X-ray image into a much brighter visible-light image.

### 3.1 Main components

From the X-ray entrance side to the optical output side, an image intensifier contains:

- protective metal or aluminium entrance window
- input phosphor
- photocathode
- electrostatic focusing lenses
- accelerating anode
- output phosphor
- evacuated glass or metal envelope

### 3.2 Input phosphor

The input phosphor converts incident X-rays into light. Caesium iodide is commonly used because it can be manufactured as needle-like crystals that guide light toward the photocathode and reduce lateral light spread.

### 3.3 Photocathode

The photocathode converts the light image from the input phosphor into an electron image. Its light emission is proportional to the local intensity of the input image.

### 3.4 Electrostatic focusing system

Electrostatic lenses focus the emitted electrons so that the spatial pattern of the X-ray image is preserved as the electron image travels toward the output phosphor.

### 3.5 Accelerating anode

The anode is maintained at a high positive potential relative to the photocathode. It accelerates the electrons toward the output phosphor.

### 3.6 Output phosphor

The output phosphor converts the accelerated electron image into a bright visible-light image. Zinc cadmium sulfide was historically used and produces light that can be efficiently coupled to a camera or television system.

---

## 4. Principles of image intensification

Image intensification increases brightness through two main mechanisms:

1. minification gain
2. flux gain

### 4.1 Minification gain

The input phosphor is much larger than the output phosphor. Electrons from a large input area are focused onto a much smaller output area. The same general image information is concentrated into a smaller area, increasing brightness.

Minification gain is approximately:

Minification gain = (input diameter / output diameter)^2

### 4.2 Flux gain

The electrons emitted at the photocathode are accelerated through a high voltage. Each electron gains kinetic energy and produces more light when it strikes the output phosphor. This increase in light output is called flux gain.

### 4.3 Brightness gain

Brightness gain is approximately:

Brightness gain = minification gain × flux gain

This allows a useful image to be viewed with much less light than direct fluoroscopy would require.

### 4.4 Dose reduction

Because the image intensifier produces a brighter image, the fluoroscopic system can operate at a lower dose rate than a direct screen system. Automatic brightness control adjusts the X-ray factors to maintain image brightness as patient thickness changes.

Dose reduction is not automatic in every situation. If the patient becomes thicker or the image becomes harder to penetrate, automatic brightness control may increase kVp, mA, pulse width, or another exposure factor.

---

## 5. Automatic brightness control

Automatic brightness control, also called automatic dose-rate control in many systems, monitors the image signal and changes the X-ray output to maintain a target brightness or detector exposure.

It may adjust:

- tube voltage
- tube current
- pulse duration
- pulse frequency
- filtration

When the patient becomes thicker, more radiation is absorbed and fewer photons reach the receptor. The system responds by increasing tube output. This maintains the displayed image but can increase patient dose.

Thus, image intensification and automatic brightness control are related: intensification improves signal efficiency, while automatic control compensates for changing attenuation.

---

## 6. Image quality in fluoroscopy

Fluoroscopic image quality depends on the X-ray beam, the patient, the image intensifier or detector, the optics, the display, and the recording system.

Important characteristics include:

- unsharpness
- noise
- spatial resolution
- contrast resolution
- distortion
- temporal resolution

### 6.1 Unsharpness

Unsharpness is the lack of sharp boundaries in the image. Sources include:

- focal-spot size
- patient movement
- image-intensifier electron spreading
- light spreading in phosphors
- optical misalignment
- geometric magnification

Motion unsharpness is particularly important in fluoroscopy because anatomy and instruments may move during exposure. Short pulses and adequate frame rates help reduce it.

### 6.2 Noise

Noise is random variation that obscures detail. Quantum noise is important in fluoroscopy because images may be produced with relatively few X-ray photons per frame.

Noise increases when:

- dose per frame is reduced
- frame rate is reduced without adequate signal
- the patient is thick
- the field is magnified

Noise can be reduced by increasing photon number, using frame averaging, or applying image-processing algorithms, but increasing radiation exposure has a dose cost.

### 6.3 Spatial resolution

Spatial resolution is the ability to distinguish small, closely spaced structures.

It is affected by:

- focal-spot size
- input phosphor structure
- electron focusing
- output phosphor resolution
- television camera or digital detector sampling
- display matrix and magnification mode

Magnification modes can improve resolution by using a smaller portion of the input field, but they generally increase patient dose through automatic brightness control.

### 6.4 Contrast resolution

Contrast resolution is the ability to distinguish objects with small differences in signal. It depends on:

- subject contrast
- scatter
- quantum noise
- detector efficiency
- image processing
- display settings

Collimation, appropriate filtration, contrast media, and scatter reduction improve the useful contrast signal.

### 6.5 Distortion

Distortion occurs when the displayed image does not preserve the exact shape or position of the object.

Types include:

- pincushion distortion
- S-distortion
- vignetting or brightness non-uniformity

Distortion is related to the curved input surface, electron focusing, magnetic fields, and geometry of the image intensifier.

---

## 7. Spectral emission and gas spots

### 7.1 Spectral emission

The output phosphor emits visible light when struck by electrons. The colour or wavelength of the emitted light is selected to match the optical coupling and camera response.

The input phosphor also has a characteristic light-emission spectrum. Efficient image intensifier design requires good matching between:

- input phosphor emission
- photocathode sensitivity
- output phosphor emission
- optical lens or camera response

Poor spectral matching reduces conversion efficiency and image brightness.

### 7.2 Gas spots

Gas spots are localized bright areas or artifacts caused by gas contamination or gas release inside the image intensifier. Gas ions or contamination can produce abnormal light emission and may create a persistent bright spot or irregular area on the displayed image.

Gas spots are different from ordinary quantum noise because they remain fixed relative to the intensifier and may be visible even when the image changes.

### 7.3 Detection and significance

Gas spots may indicate loss of vacuum integrity or internal deterioration. They can reduce diagnostic confidence and require quality-control assessment or service replacement if severe.

---

## 8. Multi-field image intensifiers

A multi-field image intensifier has more than one selectable input field size. Common modes include large, medium, and small fields.

### 8.1 How field selection works

The electrostatic focusing voltages are changed so that electrons from a selected portion of the input phosphor are directed to the output phosphor. The output image size remains approximately constant while the active input area changes.

### 8.2 Large field mode

The large field uses most of the input phosphor.

Advantages:

- broad anatomical coverage
- lower magnification
- larger field of view

It may provide lower spatial resolution than a smaller field mode.

### 8.3 Small field or magnification mode

The small field uses a smaller central portion of the input phosphor and magnifies it to the output phosphor.

Advantages:

- improved spatial resolution
- better visibility of small structures

Limitations:

- reduced field of view
- increased patient dose because automatic brightness control may raise output
- more visible noise if photon statistics are not adequate

### 8.4 Relationship to dose and resolution

Selecting a smaller field improves resolution through electronic magnification, but the system may need to increase X-ray output to preserve brightness. Therefore, improved detail may come with increased dose.

---

## 9. Lens system and image distribution

### 9.1 Electrostatic lenses

Electrostatic fields inside the image intensifier focus electrons emitted from the photocathode. Correct focusing preserves the spatial distribution of the input image as it travels to the output phosphor.

If focusing is incorrect, the image may become blurred, distorted, or non-uniform.

### 9.2 Optical coupling

The output phosphor image is coupled to the viewing and recording system through:

- optical lenses
- fibre-optic bundles
- mirrors
- television cameras
- charge-coupled devices or complementary metal-oxide-semiconductor sensors

### 9.3 Image distribution

The image may be distributed to several destinations:

- a fluoroscopic monitor
- a second monitor for the operator
- a recording camera
- a digital acquisition computer
- a network or archive system

Beam splitters or electronic distribution systems may send the signal to more than one display. Each additional optical or electronic stage can affect brightness, resolution, noise, and lag.

### 9.4 Optical distortion and vignetting

The curved input surface and electron trajectories can cause pincushion distortion. Magnetic fields near the intensifier can cause S-distortion. Brightness may fall near the edges, producing vignetting.

Modern digital correction can reduce the visible effect, but calibration and quality control remain important.

---

## 10. Viewing fluoroscopic images

The output image is usually viewed on a monitor after conversion by a television camera or digital detector.

### 10.1 Monitor requirements

A suitable display should provide:

- adequate brightness and contrast
- sufficient spatial resolution
- low display noise
- appropriate refresh rate
- stable calibration

### 10.2 Real-time viewing

The image is displayed at a selected frame rate. Higher frame rates improve temporal resolution and motion display but may increase patient dose. Lower frame rates reduce dose but may make fast motion appear less smooth.

### 10.3 Image processing

Modern systems may use:

- last-image hold
- temporal filtering
- spatial filtering
- edge enhancement
- frame averaging
- recursive noise reduction
- window and level adjustment

These tools can improve the displayed image without directly increasing exposure, although aggressive processing may blur moving structures or create artifacts.

---

## 11. Recording fluoroscopic images

Fluoroscopic images can be recorded for diagnosis, documentation, teaching, and later review.

### 11.1 Film recording

Older systems used radiographic film or cine film. These methods could provide high detail but required chemical processing and often involved substantial dose.

### 11.2 Photospot recording

A photospot camera records selected fluoroscopic images on film or another high-resolution medium. It may provide better spatial resolution than the continuously viewed image but can require a higher exposure.

### 11.3 Cine recording

Cine recording captures a sequence of images at a relatively high frame rate. It is useful for cardiac and vascular studies but may involve high radiation output.

### 11.4 Digital recording

Modern systems record digital frames or sequences. Digital recording permits:

- immediate review
- image processing
- storage and transmission
- frame selection
- dose documentation
- subtraction techniques

### 11.5 Last-image hold and image capture

Last-image hold displays the most recent frame without additional radiation. This allows the operator to study the image and plan the next step without continuously exposing the patient.

Image capture can store a selected frame for later review and reduces the need to repeat the exposure.

---

## 12. Image-intensifier limitations and quality control

Although image intensifiers provide a bright image, they have limitations:

- pincushion distortion
- S-distortion
- vignetting
- reduced resolution at the periphery
- veiling glare
- lag and afterglow
- image noise
- gas spots
- geometric magnification

Quality-control tests should examine:

- brightness uniformity
- spatial resolution
- contrast resolution
- distortion
- field-size accuracy
- image lag
- gas spots and artifacts
- monitor performance
- automatic brightness control

Many modern systems now use flat-panel detectors, which avoid some image-intensifier distortions but have their own noise, lag, defective-pixel, and dose-performance characteristics.

---

## 13. Radiation protection in fluoroscopy

Fluoroscopy can produce significant patient and staff exposure because radiation may be delivered for an extended time.

Important protective measures include:

- minimize fluoroscopy time
- use pulsed fluoroscopy where suitable
- select the lowest practical frame rate
- use last-image hold
- collimate to the region of interest
- use appropriate filtration
- avoid unnecessary magnification modes
- keep the image receptor close to the patient when possible
- keep the X-ray tube as far from the patient as practical
- use ceiling-suspended and table-mounted shields
- wear personal dosimeters and protective apparel

Magnification mode and automatic brightness control are especially related to dose. A smaller intensifier field may improve resolution, but automatic control can increase tube output to maintain brightness.

---

## 14. How all the topics are co-related

The fluoroscopic imaging process can be followed step by step:

1. The X-ray tube produces a beam with a selected energy and intensity.
2. The patient attenuates the beam and produces primary and scattered radiation.
3. The input phosphor converts transmitted X-rays into light.
4. The photocathode converts the light image into an electron image.
5. Electrostatic lenses focus and distribute the electrons.
6. Acceleration and reduction of image area produce brightness gain.
7. The output phosphor converts the electron image back into light.
8. Optical lenses or fibre-optic/electronic systems send the image to monitors and recorders.
9. Multi-field selection changes field of view, resolution, and dose.
10. Image quality is determined by unsharpness, noise, resolution, contrast, distortion, and display performance.

Direct fluoroscopy uses the light image directly and therefore has poor brightness and high dose requirements. Image intensification improves brightness through minification and flux gain. The viewing and recording system then determines how effectively that information is displayed, stored, and communicated.

Thus, receptor design, optical focusing, field selection, image processing, exposure control, and radiation protection are all parts of one integrated fluoroscopic system.

---

## 15. Final summary

Fluoroscopy provides real-time X-ray images. Direct fluoroscopy uses a fluorescent screen but has poor brightness and high dose requirements. An image intensifier improves brightness by converting X-rays to light, light to electrons, accelerating and focusing the electrons, and converting them back to light on a small output phosphor.

Brightness gain results from minification gain and flux gain. Multi-field intensifiers provide different fields of view and electronic magnification, improving resolution but potentially increasing dose through automatic brightness control. Image quality is influenced by unsharpness, noise, resolution, contrast, distortion, spectral matching, gas spots, and optical or electronic distribution.

The output image is viewed on monitors and may be recorded using film, cine, photospot, or digital systems. Last-image hold, pulsed operation, collimation, filtration, and appropriate magnification help reduce dose. All these topics are related because they describe the conversion, enhancement, distribution, display, and recording of the X-ray image while balancing diagnostic quality and radiation exposure.

## 16. Short exam-oriented conclusion

Fluoroscopy is real-time X-ray imaging. Direct fluoroscopy views a fluorescent screen directly, whereas an image intensifier produces a brighter image through input-phosphor conversion, photocathode electron emission, electrostatic focusing, electron acceleration, and output-phosphor conversion. Brightness gain is produced by minification and flux gain. Image quality depends on unsharpness, noise, resolution, contrast, distortion, spectral matching, gas spots, and optical distribution. Multi-field intensifiers provide different fields and magnification modes, but smaller fields may increase dose through automatic brightness control. The image is viewed on monitors and recorded by film, cine, or digital systems. These components are co-related as one chain from X-ray production to patient interaction, image intensification, display, recording, and radiation protection.
