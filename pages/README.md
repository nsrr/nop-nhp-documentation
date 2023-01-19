# About

The Non-Human Primate NOP Agonist (NHP-NOP) dataset contains EEG and EMG recordings conducted in in non-human primates, specifically, 5 adult male Cynomolgus macaques. This dataset was provided by the Sleep Neurobiology Laboratory at SRI International in order to facilitate research on the N/OFQ- NOP receptor system. The data include the EEG spectral activity (0.3-100 Hz) and EMG signals collected during an experiment whose aim was to assess the effects of NOP agonists on sleep and wakefulness in rodents and non-human primates. The cohort of macaques were treated subcutaneously with either vehicle (HPMC:1.25% hydroxypropylmethyl cellulose, 0.1% dioctyl sodium sulfosuccinate, and 0.25% methylcellulose in purified water) or the NOP agonist Ro64-6198 (0.1 mg/kg) in a counterbalanced design, approximately 30 min before lights off at ZT12. A minimum of 3 days elapsed between treatments.

## Citation and Acknowledgment

<i>Manuscript not yet published (Submitted Jan 25th 2023)</i>

**Please include the following text in the Acknowledgements:**

>The recordings deposited here were supported by NIH R21 NS113589 to Thomas S. Kilduff and R01 HL150836 to Thomas S. Kilduff and Michael R. Bruchas. We thank the NIDA Drug Supply Program for the Ro64-6198 used in these studies.

## Data overview

**[/edf](:files_path:/edf)**

EDF files exported by [NeuroscoreTM CNS Software](https://www.datasci.com/products/software/neuroscore) which includes 3 EEG channels, 1 EMG channel, body temperature (Tb) and locomotor activity (LMA). Data were recorded at a sampling rate of 500 Hz with [Ponemah software (version 5.20; DSI)](https://www.datasci.com/products/software/ponemah), although the DSI D70-EEE wireless transmitters only permit EEG power analysis in the 0.3-100 Hz range.

**[/fft](:files_path:/edf)**

FFT files exported by [NeuroscoreTM CNS Software](https://www.datasci.com/products/software/neuroscore). These files contain an epoched (10-second epochs) representation of the data including:
- sleep stages (manually scored) 
- power spectral density data as determined by fast Fourier transform across 820 bins between 0 and 100 Hz.

## PSG Scoring Methods

Recordings were scored in 10-s epochs for sleep/wake states by expert scorers using Neuroscore (DSI, St Paul, MN) according to the criteria described previously ([Goonawardena et al., 2018](https://pubmed.ncbi.nlm.nih.gov/31236518/); [Goonawardena et al., 2019](https://pubmed.ncbi.nlm.nih.gov/30954024/)). 

Continuous acquisition of the EEG and EMG telemetry signals occurred at a sampling rate of 500 Hz using [Ponemah software (version 5.20; DSI)](https://www.datasci.com/products/software/ponemah); the frequency range of the D70-EEE telemetry transmitters was 0.3–100 Hz. Wake was scored when > 50% of the epoch consisted of alpha (8-13 Hz) activity or low amplitude, mixed frequency (2-7 Hz) activity and active EMG.  N1 was scored when 50% of the epoch consisted of relatively low amplitude, mixed frequency (2-7 Hz) activity and <50% of the epoch contained alpha (8-13 Hz) activity accompanied with lower EMG activity. N2 was scored when K-complexes (1-2 Hz isolated waves) and/or sleep spindles (regular 12-16 Hz EEG sequences) were observed and <20% of the epoch contained high amplitude (>75 µV), low frequency (1-4 Hz) activity. N3 was scored when ≥20% of the epoch consisted of high amplitude (>75 µV), low frequency (1-4 Hz) EEG waves (i.e., slow wave activity). REM was scored when the epoch contained relatively low voltage, mixed frequency activity with predominant theta activity (4-9 Hz) accompanied with low EMG activity (i.e., atonia). Epochs with prominent muscular artifacts were identified and excluded from subsequent EEG spectral analysis. Power spectral analyses of the EEG (0.3-100 Hz) was determined within each state.

## Animal Experimental Procedures

- **Surgical Procedures:**  Male Cynologus macaques (n = 5, 14-19 years, 7-10 kg) were fully anesthetized [telazole (4 mg/kg, i.m.) and 1% isoflurane] and implanted for recording 3 EEG and 1 EMG channels.  A disk-shaped telemetry transmitter (D70-EEE; DSI, St-Paul, MN) was placed between the internal oblique muscle and the aponeurosis of the transverse abdominis muscle as described previously (Goonawardena et al., 2019a; Goonawardena et al., 2019b).  Electrode locations were labeled according to the 10-20 system in humans. EEG wires from the transmitter were placed over the right frontal cortex (Fp2), centrally (Cz), over the right parietal cortex (C4), and over the occipital cortex (Oz, reference location). Actual coordinates (from Bregma) for the EEG electrodes: Fp2: AP +18.0 mm, M -15.0 mm; Cz: AP 0.0 mm, ML 0.0 mm; C4: AP: 0.0 mm, ML 18.0 mm; all three EEG channels referenced to Oz: AP -27.0 mm; ML 0.0 mm.  Stainless steel screws were inserted until the tips were estimated to touch the dura mater and the exposed EEG wire tips were wrapped around the screws; silver epoxy was then applied over the wire/screws to ensure good electrical conductivity.  Once the epoxy was fully dried (approx 15-20 min), all wires/screws were insulated with dental cement (FuliCEM resin modified glass ionomer cement; Net 32 Inc., Cary, NC).  Electromyographic (EMG) electrodes connected to the transmitter were implanted bilaterally into the superficial neck musculature (trapezius).  All animals received perioperative anesthetic monitoring, postoperative analgesia for ≥ 72-h, antibiotics for 10–14 d, and were allowed a minimum of 21-d recovery period before experiments.

- **Dosing:** NHPs received either the HPMC vehicle (1.25% hydroxypropylmethyl cellulose, 0.1% dioctyl sodium sulfosuccinate, and 0.25% methylcellulose in purified water) or the NOP agonist Ro64-6198 (0.1 mg/kg, s.c.) in a counter-balanced design.  

- **Time of day:** Dosing occurred just prior to light offset at ZT12.  A minimum of 3 days elapsed between treatments. 

- **Duration of data collection:** EEG and EMG were recorded in each animal in its home cage across the 12-h dark phase beginning at light offset (ZT12). Continuous acquisition of the EEG and EMG telemetry signals occurred at a sampling rate of 500 Hz using Ponemah software (version 5.20; DSI); the frequency range of the D70-EEE telemetry transmitters was 0.3–100 Hz.  

## Access Restrictions

The NOP-NHP dataset is only available for non-commercial use.

## Other Relevant Publications

>[Goonawardena AV, Morairty SR, Orellana GA, Willoughby AR, Wallace TL, Kilduff TS. Electrophysiological characterization of sleep/wake, activity and the response to caffeine in adult cynomolgus macaques. Neurobiol Sleep Circadian Rhythms. 2018 Aug 22;6:9-23. doi: 10.1016/j.nbscr.2018.08.001. PMID: 31236518; PMCID: PMC6586594.](https://pubmed.ncbi.nlm.nih.gov/31236518/)

>[Goonawardena AV, Morairty SR, Dell R, Orellana GA, Hoener MC, Wallace TL, Kilduff TS. Trace amine-associated receptor 1 agonism promotes wakefulness without impairment of cognition in Cynomolgus macaques. Neuropsychopharmacology. 2019 Jul;44(8):1485-1493. doi: 10.1038/s41386-019-0386-8. Epub 2019 Apr 6. PMID: 30954024; PMCID: PMC6784974.](https://pubmed.ncbi.nlm.nih.gov/30954024/)

