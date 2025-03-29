# Taxonomy of labels:

Upon a new release, the agreed-upon taxonomy below should be provided/updated in the repo as a suite of formats that is easily ingested programattically (e.g. for drop-down menus in annoation UIs):

 - JSON?
 - csv?

## Taxonomy proposed by Orcasound

### Current Orcasound proposal in text format

```
signal
|-- calls (could be a bout label, or annotation of a bounded sequence of calls)
|     |-- call (a bounded call, not yet classified as discrete, variable, or aberrant)
|     |-- call? (a bounded potential call, not yet sub-classified, likely needing input from other annoators)
|     |-- discrete
|     |     |-- S01 (note leading zero!)
|     |     |-- S02 ...
|     |     |-- ...
|     |     |-- S42
|     |-- variable
|     |     |-- S01?
|     |     |-- S02?
|     |     |-- ...
|     |     |-- S42?
|     |-- aberrant (definitely a call from an SRKW, but not a discrete or variable call)
|-- whistles (could be a bout label, or annotation of a bounded sequence of whistles)
|     |-- whistle (bounded, but not yet classifed)
|     |-- SW01
|     |-- ...
|     |-- SW07
|-- clicks (could be a bout label, or annotation of a bounded sequence of clicks)
|     |-- pulse (a label for an individual echolocation pulse)
|     |-- clicks-slow (a sequence label)
|     |-- clicks-fast (a sequence label)
|     |-- buzz (a sequence label)
|     |-- sweep (a sequence label, primarily for waveform annotation, in which received pulse amplitude rises and then falls within a click sequence)
|-- other
|     |-- percussive
```

### Current Orcasound discussion


SV note from [discussion of label alignment between HALLO and Orcasound](https://github.com/orcasound/signals-srkw/discussions/16): 

```
I've barely thought about the other category (and rarely label any of these sounds), but added to the Gsheet this short list of 6 that might eventually be useful at Orcasound locations (e.g. if we add in-air microphones):

    Cavitation (Bigg's bangs?)
    Wave
    Blow
    Inhalation
    Rasperry
```

### Context labels: 

**Ecotype**

In this signal repository, all labels are assumed to be only for use with members of Orcinus orca within the southern resident killer whale population. The label for this ecotype is:

SRKW

**Pod(s)**

Each label means at least one member of each pod (J, K, and/or L) was within detection range when the signal was received

 - J
 - K
 - L
 - JK
 - KL
 - JL
 - JKL

### Signal labels: 

**Calls**
  - call
    - S01
    - S02
    … ...

Use the list from Ford+2024 open catalog, but simplify labels through agreement with HALLO and other annotation groups?

Link to catalog?
Link to Google sheet?

**Whistles**
 - whistle
   - SW01
   - SW02
   - SW03
   - SW04
   - SW05
   - SW06
   - SW07

**Clicks**
 - echolocation
   - clicks (a series or sequences of clicks, not yet classified based on ICI measurement within a sequence)
   - clicks-slow
   - clicks-medium
   - clicks-fast

## Taxonomy under discussion

**Context**

From finwave.io API and/or Google API of other community resources, like the Bigg's nickname Google sheet?

 - Matrilines 
 - Individuals
 
**Signals**

- Percussives
 - pectoral fin slap
 - fluke slap
 - breach
- Fluke cavitation, underwater tail slaps, and/or ramming prey (e.g. during harbor porpoise harrassment and killing?)
 - Do SRKWs ever create impulsive sounds through mechanisms other than surface percussives?
 - Do they make anything like ["Bigg's bangs"](https://www.orcasound.net/2018/12/08/biggs-bangs-the-sound-of-marine-mammal-death-heard-live/)?
- Rasps
 - a series of frequency modulated clicks associated with foraging in other odontocetes (Aguilar de Soto et al., 2012)
- Calls that have meaning (as we discover it, e.g. call types shared across KW ecotypes, like the excitement call [S10 in SRKWs])
 - excitement

# Methodology of labeling:

This could go here, or maybe there should be a link to a shared procedure that's standardized across all `signals-` repos?

## Preliminary (weak) labeling 

## Maximum (strongest) labeling

# Locations of labeled data sets:

Just add a link to the orcadata wiki?

Or specify: 

**Orcaound**
audio-deriv-orcasound-net S3 bucket

**HALLO**

**DCLDE**
