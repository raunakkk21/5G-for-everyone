# Standardiazation of 5G
- *ITU-R*(International telecommunicaiton union-Radiocommunication) is the body that holds responsibilitites to develop 5G and maintain the technical standard.
- IMT(International mobile telecommunications) are the requirements issued by ITU-R.
<img width="700" alt="Screenshot 2023-11-13 131132" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/4a91f060-7ff1-4e77-8f94-0a22100ddc75">

#### Evolution to 5G
- GPRS was put as an add on to GSM network which provided speed of 50Kbps
<img width="700" alt="Screenshot 2023-11-13 131429" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/c9a5ace7-572f-48b1-abca-a27f4a5247e0">

#### Use cases of 5G
<img width="700" alt="Screenshot 2023-11-13 131642" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/f64c69d6-0e66-4413-8747-de33889103f1">

- Inner light green boundary represents the requirements of 4G and outer represents of 5G.
- 3GPP stands for 3rd Generation partnership project

**Use scenarios**

- **eMBB**
  - It requires high data rate with low latency

<img width="700" alt="Screenshot 2023-11-13 132333" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/322230f5-c27a-4580-b602-fdb3500305a8">

-----------

- **mMTC**
  - It focuses on longer battery life as small devices like in smart city or IoT runs on a smaller battery for a longer time.
<img width="700" alt="Screenshot 2023-11-13 132501" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/832bca5d-0cad-4d1d-9c3d-a829e1638cef">

-----------

- **uRLLC**
  - It's focus is on providing low latency connection with reliability.
<img width="700" alt="Screenshot 2023-11-13 165823" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/a6cd019e-d0fd-44f1-8bd3-a3bd2a39aa79">

--------
**IMT use cases**

<img width="700" alt="Screenshot 2023-11-13 132754" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/b9a517c3-15df-4dd8-b958-cbace63bca0a">

--------

**Roadmap to 5G**

<img width="700" alt="Screenshot 2023-11-13 132842" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/f06ced0c-f60c-4b61-bdbd-cabfee33afeb">


## 5G architecture
<img width="700" alt="Screenshot 2023-11-13 133001" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/27818bba-524b-4cfd-a9dc-334817acba1e">

- 5G is all IP architecture which means all calls and data are handled in packets.

- **Non Stand alone vs Stand alone**
<img width="700" alt="Screenshot 2023-11-13 133255" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/419b52d1-aedc-438a-9740-4b469058e84a">

- *Evolved packet core* is core of 4G network
- *E-UTRAN*- Evolved Universal Terrestrial Radio Access Network
- *NG-RAN*- New generation radio access network

## Key features of NG-RAN
<img width="700" alt="Screenshot 2023-11-13 173601" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/490c389b-e4a2-404f-8524-0e0aed4e63a0">


### Dual connectiviy in 5G
<img width="700" alt="Screenshot 2023-11-13 172412" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/6a3aa11f-76cf-49a7-b90e-a626b446ab4f">

- We can have master node as 4G eNB that is connected to 4G core(EPC-Evolved packet core)
- Split bearer is the function that allows the split of data going to gNB from the core side into two paths
<img width="700" alt="Screenshot 2023-11-13 174003" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/448673e5-2652-41f2-9a3d-9d7dca8b8bf3">


### Small cells in 5G networks
- Using dual connectivity it can connect to two cells which increases data rates.


### Increased spectrum
<img width="700" alt="Screenshot 2023-11-13 175245" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/47ad3ccf-832b-4f0f-8122-19535dafdf39">

- Lower frequencies have less attenuation with excellent building penetration but have limited availibility
- Range of 6-100Ghz is what called mmWave but attenuation is much higgher as compared to other frequencies
  
### OFDMA
- Orthogonal frequency division multiple access
- In OFDMA the frequency band in is divided into sub carriers
- Spacing between two subcarriers is called del f
- Flexible numerology is reffered by 	μ
- The guard period between two OFDM signals is called as Cyclic prefix, purpose of guard period is that one symbol does not overlap with adjacent symbol
- There are two prefix normal and extended
    - Extended prefix is used for the cell having larger area

<img width="700" alt="Screenshot 2023-11-13 175709" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/76398a34-c72b-4fff-a1f1-45dc456e7453">
<img width="700" alt="Screenshot 2023-11-13 180551" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/f0c55ed8-3aac-401a-9ce9-4edd796c1feb">
<img width="700" alt="Screenshot 2023-11-13 180614" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/e2fb0046-4637-4787-a486-767003246c41">












































