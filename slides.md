---
download: true
selectable: true
theme: seriph
colorSchema: dark
title: cortical psychophysiology
author: Germano Gallicchio
layout: intro
transition: fade
hideInToc: true
mdc: true
browserExporter: true  # enable browser exporter, can be boolean, 'dev' or 'build'
exportFilename: slides-exported # filename of the export file
# export options
# use export CLI options in camelCase format
# Learn more: https://sli.dev/guide/exporting.html
export:
  format: pdf
  timeout: 30000
  dark: false
  withClicks: false
  withToc: false
---

### Psychophysiology of Sport and Exercise
# Cortical psychophysiology
<br>

Germano Gallicchio

JXH-3089, Bangor University

---
layout: center
---

Attendance PIN


---
title: overview
hideInToc: true
---

# Overview of this submodule

| CONTENT                               | LECTURE | WORKSHOP | SEMINAR | LABS |
| ------:                               | :-----: | :------: | :-----: | :---:|
| Reminders of Anatomy and Physiology   | X       |          |         |      |
| Foundations of Electroencephalography | X       | X        |         |      |
| Hands-on experience                   |         | X        |         | X    |     
| Applications to Sport & Exercise      |         |          | X       |      |


---

# Objectives 

<br>

Being able to elaborate:

<v-clicks>

- biological source of the EEG signal
- metrics that can be obtained from the EEG signal

</v-clicks>

::right::


---
layout: two-cols-header
---

# Study resources

::left::

## Main

These slides

<br>

Other resources (e.g., articles published in the journal _Psychophysiology_) are cited when relevant.


::right::



---

# Why study brain activity
<br>

Studying brain activity is useful for several purposes:

<v-clicks>

- **Understanding** how different brain regions contribute to various cognitive and motor functions.

- **Sleep** staging to distinguish the different phases of sleep.

- **Diagnosing** and monitoring neurological conditions such as epilepsy, sleep disorders, and brain injuries.

- **Enable brain-computer interfaces** that allow direct control of machines and external devices by controlling brain activity

- **Therapies** for mental health conditions such as anxiety, depression, and ADHD.

</v-clicks>

--- 
layout: two-cols-header
---

# Anatomical directions and planes

::left::

(Some) Anatomical directions:

<v-clicks>

- **Anterior** (or rostral) 
<br>
towards the front (literally: towards the face)

- **Posterior** (or caudal)
<br>
towards the back (literally: towards the tail)

- **superior** (or dorsal)
<br>
upwards 

- **inferior** (or ventral)
<br>
downwards

</v-clicks>

::right::

<img src="./images/brainDirections1.png" style="width:80%; margin:auto" >

---
layout: two-cols-header
---

# Anatomical directions and planes

<br>

::left::

<v-clicks>

- **Lateral** 
<br>
towards the side

- **Medial** 
<br>
towards the midline

- **ipsi**lateral
<br>
same side

- **contra**lateral
<br>
opposite side

- **Proximal**
<br>
closer to the point of attachment or origin

- **Distal**
<br>
further from the point of attachment or origin

</v-clicks>

::right::

<v-clicks>

Anatomical planes (useful to image them as slices): 
- **sagittal**
<br>
It divides the brain into left and right

- **coronal** (or frontal)
<br>
it divides the brain into anterior (rostral) and posterior (caudal)

- **horizontal** (or transverse)
<br>
it divides the brain into superior (dorsal) and inferior (ventral)

</v-clicks>

---
layout: two-cols-header
---

# The nervous system
<br>

::left::

```mermaid {scale:0.9}
flowchart TD
    A(nervous system) 
    B(central n. s.)
    C(peripheral n. s.)
    A --> B
    A --> C

    
    D(brain)
    E(spinal cord)
    B --> D 
    B --> E

    F(somatic n. s.)
    G(autonomic n. s.)
    C --> F
    C --> G

    H(sympathetic n.s)
    I(parasympathetic n.s)
    G --> H
    G --> I
```

::right::

<img src="./images/nervousSystem.png" style="width:100%; margin:auto" >

---
layout: two-cols-header
---

# The brain

::left::

```mermaid {scale:0.8}
flowchart LR
    A(brain)
    B(forebrain)
    C(midbrain)
    D(hindbrain)
    A --> B
    A --> C
    A --> D

    E(cerebrum)
    F(diencephalon)
    B --> E --> cortex
    B --> F

    G(cerebellum)
    H(pons)
    I(medulla)
    D --> G
    D --> H
    D --> I
```

::right::

<img src="./images/brainDivisions.jpg" style="width:100%; margin:auto" >

<br>

Interactive website:
<br>
https://www.brainfacts.org/3d-brain#intro=false&focus=Brain




---
layout: two-cols-header
---

# Cerebral cortex
The focus in this submodule

<img src="./images/cerebralCortex.png" style="width:90%; margin:auto" >

---

# Cortical Lobes

<img src="./images/corticalLobes1.png" style="width:75%; margin:auto" >

---

# Cortical Lobes

<img src="./images/corticalLobes2.png" style="width:75%; margin:auto" >

---

# Cortical Lobes

<img src="./images/corticalLobes3.png" style="width:75%; margin:auto" >

---
layout: two-cols-header
---

# Cortical layers

::left::

The cerebral cortex is divided into six layers, each with distinct types of neurons and connections.
- Layer I: Contains mostly dendrites and axons.
- Layer II: Contains small pyramidal neurons.
- Layer III: Contains medium-sized pyramidal neurons.
- Layer IV: Contains various types of neurons.
- Layer V: Contains large pyramidal neurons, including Betz cells.
- Layer VI: Contains spindle-shaped neurons.

::right::

<img src="./images/corticalLayers.png" style="width:75%; margin:auto" >

---
layout: two-cols-header
---

# Broadmann areas

<br>

<v-clicks>

Not only variations in cellular composition (cytoarchitecture) define the six cortical layers... 

...but also help identify different areas (i.e., **Broadmann** areas), each with distinct cellular structures and functions.

</v-clicks>

::left::

<v-clicks>

- Area 1, 2, 3: Primary somatosensory cortex.
- Area 4: Primary motor cortex.
- Area 17: Primary visual cortex.
- Area 22: Part of the superior temporal gyrus, involved in auditory processing.
- Area 44, 45: Broca's area, involved in language production.

</v-clicks>

::right::

<img src="./images/broadmannAreas.png" style="width:80%; margin:auto" >

---

# Cortex mapping
There are several examples of "mapping" (e.g., retinotopic, tonotopic, somatotopic)

**Somatotopic** mapping: organization of the primary somatosensory cortex (S1) and primary motor cortex (M1) where different parts of the body are represented in specific cortical areas. This is often illustrated by the sensory and motor _homunculus_, which shows the disproportionate representation of body parts based on their sensory and motor importance.

<img src="./images/cortexSomatotopic.png" style="width:100%; margin:auto" >

---

# Neurons

<img src="./images/neurons1.png" style="width:100%; margin:auto" >

---

# Neurons

<img src="./images/neurons2.png" style="width:80%; margin:auto" >



---
layout: two-cols-header
---

# Neuronal communication
electrochemical communication

<br>
<Youtube id="6qS83wD29PY" width="100%" height="30%"/>

https://youtu.be/6qS83wD29PY?t=8

::left::

**Action potential**:
- Fast voltage spike (1 ms)
- Travelling along the axon, from its beginning to its terminal
- Neurotransmitters are released
- Unlikely to be detected with surface electrodes

::right::

**Postsynaptic potential**:
- Slower voltage (up to hundreds of ms)
- increase (excitatory) or decrease (inhibitory)
- Travelling on the membrane of dendrites or soma
- Multiple potentials summate

---
layout: two-cols-header
---

# Dipoles

::left::

- Electrochemical activity in the dendrites generates electric fields.
- These fields create dipoles due to the separation of charges.

::right::

<img src="./images/neuronDipole.png" style="height:90%; margin:auto" >


---
layout: two-cols-header
---

# Dipoles

::left::

- Dipoles can be detected from the scalp as voltage differences.
- The _orientation_ and magnitude of dipoles influence the signal on the scalp
- Simultaneous dipoles _summate_
- The myriad of dipoles active at the same time contributes to the overall voltage pattern on the scalp.

::right::

<img src="./images/neuronsDipolesCortex.png" style="width:100%; margin:auto" >

---
layout: two-cols-header
---

# Dipoles

::left::

- **Radial dipoles**: Oriented _perpendicular_ to the cortical surface, often generated by pyramidal neurons in the gyri. These dipoles are _more likely_ to be detected from electrodes on the scalp because their orientation aligns with the electrodes on the scalp.

- **Tangential dipoles**: Oriented _parallel_ to the cortical surface, often found in the walls of the sulci. These dipoles are _less likely_ to be detected by electrodes on the scalp as their orientation does not align well with the scalp.

Both types of dipoles contribute to the overall EEG signal, but radial dipoles generally have a stronger influence due to their alignment with the scalp surface.

::right::

<img src="./images/neuronsDipolesCortexEEG.png" style="width:90%; margin:auto" >

---
layout: two-cols-header
---

# Electroencephalography (EEG)

::left::

| MORPHEME  | MEANING |
|---------: |:----------|
| Electro   | = electrical activity |
| encephalo | = of the brain (cortex) |
| graph    | = measurement |

::right::

<img src="./images/brainTechniques.png" style="width:100%; margin:auto" >

---
layout: two-cols-header
---

# Characteristics of the EEG

::left::
- noninvasive
- portable
- postsynaptic potential
- high temporal resolution
- cerebral cortex
- poor spatial resolution
- objective


::right::

<img src="./images/biosemiCap.png" style="width:100%; margin:auto" >

---

# Main parameters of waveforms

- **Frequency**: The number of cycles the waveform completes in a given time period, usually measured in Hertz (Hz). Higher frequency indicates more cycles per second.
- **Phase**: The position of a point in time on the waveform cycle, indicating the timing of the waveform relative to a reference point. Phase differences can affect how waveforms interact with each other.
- **Amplitude**: The height of the waveform, representing the strength or intensity of the signal. Higher amplitude indicates stronger signals.

<img src="./images/waveformParameters.png" style="width:60%; margin:auto" >

---

# Main parameters of waveforms
varying frequency

<img src="./images/waveformParameters_frequency.png" style="width:90%; margin:auto" >



---

# Main parameters of waveforms
varying phase

<img src="./images/waveformParameters_phase.png" style="width:90%; margin:auto" >

---

# Main parameters of waveforms
varying amplitude

<img src="./images/waveformParameters_amplitude.png" style="width:90%; margin:auto" >

---

# Simulating EEG signal
Let's sum, time by time, three waves varying in frequency, phase, and amplitude

<img src="./images/waveformParameters_sum.png" style="width:90%; margin:auto" >

---

# Simulating EEG signal
Same as before but let's add noise

<img src="./images/waveformParameters_sumWithNoise.png" style="width:90%; margin:auto" >

---
layout: two-cols-header
---

# 10-20 system
an internationally recognized method to describe the location of scalp electrodes

::left::

- Electrodes are placed at intervals of 10% or 20% of the total distance between specified skull _landmarks_.
- Common landmarks include the _nasion_ (bridge of the nose), _inion_ (bump at the back of the skull), and _preauricular points_ (just in front of the ears).
- Electrode positions are labeled with letters and numbers, where letters correspond to brain regions (e.g., F for frontal, T for temporal) and numbers indicate the hemisphere (odd numbers for the left, even numbers for the right).
- It can be expanded to include additional electrodes for higher resolution recordings, known as the 10-10 or 10-5 systems.

::right::

<img src="./images/1020system.png" style="width:100%; margin:auto" >


---
layout: two-cols-header
---

# 10-20 system

::left::

| Letter    | Region  |
|----------:|:--------|
| F         | Frontal |
| C         | Central |
| P         | Parietal|
| T         | Temporal|
| O         | Occipital|
| Fp        | Frontopolar |

::right::

| Second Letter or Digit | lateral/medial  |
|-----------:|:---------------|
| z          | = on the midline |
| odd digit  | = lateral (left) |
| even digit | = lateral (right)|
| smaller digit | = closer to the midline |
| larger digit  | = farther from the midline |


---
layout: two-cols-header
---

# 10-20 system

::left::

<img src="./images/1020system2.png" style="width:90%; margin:auto" >

::right::

Some examples:

Cz = central on the midline (aka vertex)

P3 = parietal, lateral to the left

P5 = parietal, even more lateral to the left (not in the figure)

---

# Electrical reference

reminder: One electrode alone cannot measure anything. You need two electrodes to measure voltage


- **Bipolar montage**:
    - Each electrode is referenced to an adjacent electrode.
    - Measures the voltage difference between pairs of electrodes.
    - Useful for detecting localized activity.
    - Can help reduce common noise.

- **Monopolar (or referential) montage**:
    - Each electrode is referenced to a common reference electrode.
    - Measures the voltage difference between each electrode and the reference.
    - Provides a broader view of brain activity.
    - Common reference points include the mastoids, earlobes, or an average of all electrodes.

---

# EEG signals

<img src="./images/eegSignal.png" style="width:90%; margin:auto" >

---

# EEG signals

<img src="./images/eegSignal2.png" style="width:60%; margin:auto" >

Recordings from multiple channels

---

# EEG signals

<img src="./images/eegSignal3.png" style="height:80%; margin:auto" >

Recordings from the same channel, under different states of consciousness

---
layout: two-cols-header
---

# EEG artifacts

::left::

<img src="./images/eegArtifacts.png" style="width:90%; margin:auto" >

::right::

- **Eye movements**: Blinks and saccades, especially in the frontal region.
- **Muscle activity**: Tension or movements in the scalp, neck, or face muscles can introduce high-frequency noise.
- **Electrode movement**: Shifts in electrode position can cause sudden changes in the recorded signal.
- **Sweat**: Changes in skin conductance can affect low-frequency characteristics.
- **Heartbeats**: electrical activity of the heart (e.g., R-waves, pulse waves).
- **Environmental noise**: Electrical interference from nearby equipment or power lines can introduce 50/60 Hz noise.

---

# Brain rhythms

<img src="./images/eegPrism.png" style="width:90%; margin:auto" >

Spectral decomposition breaks down the complex EEG signal into its constituent _frequency_ components. This process facilitates analysis of the different brain rhythms and their contributions to the overall signal.

---
layout: two-cols-header
---

# Brain rhythms
<br>

::left::

<v-clicks>

- **Alpha waves (8-12 Hz)**: 
    - Associated with neuronal suppression (e.g., cognitive activity, relationx).
- **Beta waves (12-30 Hz)**:
    - Associated with alertness, concentration, and active thinking.
    - Can be increased by stress, anxiety, or mental effort.
- **Delta waves (0.5-4 Hz)**:
    - Predominantly seen during deep sleep.

</v-clicks>

::right::

<v-clicks>

- **Theta waves (4-8 Hz)**:
    - Associated with executive functions (inhibition, updating, shifting).
    - More prominent in the frontal regions.
- **Gamma waves (30-100 Hz)**:
    - Associated with neuronal excitations 
- **Mu waves (8-13 Hz)**:
    - Similar to alpha waves but more localized to the sensorimotor cortex.
    - Associated with motor planning, execution

</v-clicks>

---
layout: two-cols-header
---

# Topographical mapping

::left::

<img src="./images/eegTopoMap.png" style="width:90%; margin:auto" >

::right::

- Visual representation of EEG data across the scalp.
- Helps identify spatial patterns of brain activity.
- Useful for detecting regional differences in brain function.
- Often used in clinical and research settings to analyze brain waves.
- Provides a comprehensive view of brain dynamics over time.

---

# Uses of EEG in sport and exercise

<img src="./images/eegSport.png" style="width:90%; margin:auto" >


----
