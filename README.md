# GNU Radio Experiments

This repository contains a collection of **GNU Radio Companion (GRC) experiments** developed while learning and exploring fundamental concepts in **Software Defined Radio (SDR), signal processing, analog modulation, and digital modulation**. The experiments progress from basic signal generation and signal analysis to practical implementations of AM, FM, ASK, BPSK, QPSK, and QAM, including the effect of noise and channel impairments. For installation guide refer [📄 Radioconda Installation Guide](./Radioconda%20Installation%20Steps.pdf)
## Experiments

### 1. Sinc Signal Experiment — `sincexp.grc`

This experiment demonstrates the generation and analysis of **sinc signals** using GNU Radio. Two sinc functions with adjustable amplitudes and different time shifts are generated using vector sources, combined, and observed in both the time and frequency domains using QT GUI sinks. It provides a basic introduction to waveform generation, signal addition, and frequency-domain analysis.

### 2. Baseband Signal — `Baseband_Signal.grc`

This experiment focuses on the generation and analysis of a **baseband signal**. An audio/WAV signal is processed using filtering and noise addition, allowing the resulting waveform to be observed in both the time and frequency domains. The experiment introduces basic signal conditioning concepts such as band-pass filtering, noise addition, and spectrum visualization.

### 3. Amplitude Modulation — `AM_Test.grc`

This experiment demonstrates the basic principle of **Amplitude Modulation (AM)**, where an information signal is combined with a carrier by varying the carrier amplitude according to the input signal. The flowgraph includes signal sources, multiplication, filtering, gain control, and visualization blocks to observe the modulated waveform and its characteristics.

### 4. Frequency Modulation — `FMMOD.grc`

This experiment explores **Frequency Modulation (FM)**, in which the instantaneous frequency of a carrier is varied according to the amplitude of the information signal. GNU Radio's phase modulation functionality is used along with signal processing blocks to generate and observe the FM waveform in both the time and frequency domains.

### 5. Amplitude Shift Keying — `ASK1.grc`

This experiment introduces **Amplitude Shift Keying (ASK)**, a basic digital modulation technique in which digital symbols are represented by different carrier amplitudes. Random digital data is converted into symbols and used to control a carrier signal, allowing the resulting ASK waveform to be examined in the time domain.

### 6. ASK Modulation and Demodulation — `ASK.grc`

This experiment extends the ASK concept into a more complete **digital communication system**. Random binary data is modulated using ASK and passed through a channel model before being processed by synchronization and demodulation blocks. The recovered data and constellation are then analyzed to understand the complete modulation and reception process.

### 7. Binary Phase Shift Keying — `BPSK2.grc`

This experiment implements **Binary Phase Shift Keying (BPSK)**, where binary symbols are represented using two different carrier phases. Random binary data is mapped to constellation points, shaped and modulated onto a carrier, and the resulting signal is analyzed using time-domain, constellation, and eye-diagram visualizations.

### 8. BPSK with Noise — `BPSKWITHNOISE.grc`

This experiment investigates the effect of **noise on a BPSK communication system**. A BPSK-modulated signal is combined with an adjustable noise source before being processed and observed. The experiment helps demonstrate how increasing channel noise affects the received waveform and the quality of digital symbol detection.

### 9. QPSK Modulation — `QPSK1.grc`

This experiment demonstrates **Quadrature Phase Shift Keying (QPSK)**, where two bits are represented by one of four possible carrier phases. The flowgraph generates digital data, maps it to complex symbols, performs pulse shaping and carrier modulation, and provides time-domain, constellation, and eye-diagram visualization for analyzing the QPSK signal.

### 10. 4-QAM Modulation and Channel Impairments — `QAM_Test.grc`

This experiment implements **4-QAM (Quadrature Amplitude Modulation)** using complex I/Q symbols. The flowgraph allows different practical impairments such as frequency offset, phase noise, I/Q magnitude imbalance, and phase imbalance to be introduced and adjusted. The resulting constellation and eye diagram provide a visual representation of how these impairments affect a digital communication signal.







