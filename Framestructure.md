# *NR Frame Structure*
<img width="723" alt="Screenshot 2023-11-04 223616" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/0d953086-fada-4f8b-8c98-ec3728d00de1">  

- *Radio Frames*-Data(UL/DL) is transmitted in the form of radio frames in the air. Radio Frames are of a duration of 10ms which consists of 10 subframes each having a duration of 1ms.
- *Subframes*-Subframes inside a radio frame are serialized as SF0, SF1, SF2, SF3, …., and SF9. A subframe is made up of a Resource Grid.
- *Resource Grid*- Resource Grid is a (m x n) matrix of Resource Elements where ‘m’ defines the number of Sub-carriers and ‘n’ defines the number of OFDM Symbols.
- Subframes are further divided into slots. LTE has fixed 2 slots per subframe as per numerology, 15KHz. But in NR, the number of slots varies, depending on the SCS(SubCarrier Spacing). Slot length gets shorter as Subcarrier Spacing gets wider.
  
<img width="728" alt="Screenshot 2023-11-04 224358" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/8cc48587-599d-46f1-a9a5-71a76af8a957">  

- LTE supports numerology of 15KHz only but in 5G, the supported numerologies are 15KHz, 30KHz, 60KHz, 120KHz, and 240KHz.
- Multiple Subcarrier Spacing provides flexibility for multiple services on the same carrier frequency but it also introduces interference with other services having different numerology.
- Formula to calculate, SCS = 15 x 2μ kHz(where μ = 0, 1, 2, 3, 4).
- **Slot**-A Slot is another matrix of 12 subcarriers along with a variable number of symbols in the time domain or simply a Resource Block. It can further be classified based on the number of OFDM symbols. The number of OFDM Symbols varies with slot configuration, and the type of Cyclic Prefix used.
- *Types of slot*
   - Slot Configuration 0 – This configuration is newly introduced in the NR System. The number of symbols in a slot is always 14 for Normal Cyclic Prefix and 12 for Extended Cyclic Prefix.
   - Slot Configuration 1 – In this configuration, the number of symbols in a slot is always 7 for Normal Cyclic Prefix and 6 for Extended Cyclic Prefix. This is the old Slot configuration mechanism used in the 4G System for resource allocation.
     
<img width="737" alt="Screenshot 2023-11-04 224429" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b635cf4c-ace5-4bd8-870c-129f3fcc8818">  

### FDM(Frequecy division multiplexing) | OFDM (Orthogonal frequency division multiplexing)   


1.**QAM**- Quadrature amplitude modulation (QAM) is a digital modulation scheme that uses two signals to amplitude-modulate two carriers that are 90 degrees out of phase with each other.  

2.**FDM**- Frequency division multiplexing (FDM) is a multiplexing technique that divides the available bandwidth into multiple sub-bands, each of which can carry a signal.   

3.**OFDM**- Orthogonal frequency-division multiplexing (OFDM) is a multi-carrier modulation system that transmits data as a combination of orthogonal narrowband signals known as subcarriers. OFDM is a widely used modulation method used to achieve high data rates and spectral efficiency.  

4.**ISI**-Intersymbol interference (ISI) is a type of signal distortion that occurs in digital communications systems. It happens when the energy of a symbol spills over into succeeding symbols, causing interference. This can cause noise in the signal, making communication less reliable. 


![2-Table1-1](https://github.com/raunakkk21/5G-for-everyone/assets/143111163/d8f30bf8-b359-4fee-9cc1-8855b336b146)      
<img width="636" alt="Screenshot 2023-11-05 000948" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/8ab25234-8cef-4335-86cd-e958be5db983">






