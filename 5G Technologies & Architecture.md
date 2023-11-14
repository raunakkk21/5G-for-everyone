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


### Resource Block
- In 5G NR resource block is only defined in frequency domain and not in time domain having 12 consecutive block vertically
- In case of LTE resource block was defined in both frequency and time domains.
- As the spacing of sub carriers increased the duration of time slot is increased.
<img width="700" alt="Screenshot 2023-11-13 212236" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/c2fae0fe-bdbf-4d48-923c-8c26b9c6617b">

### Resource element
- It is defined in both time and frequency domain
<img width="700" alt="Screenshot 2023-11-13 212815" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/8b476207-bb84-42d7-bbf5-be2ea51e2436">

### Modulation in 5G
- *QAM*- Quadrature amplitude modulation
- When the distance between UE and tower increases and if there are obstacles between them, we need to downgrade the modulation scheme.
- For example
   - 16 QAM= 4 bits per symbol
   - 256 QAM= 8 bits per symbol, i.e it is defined in the power of 2
<img width="700" alt="Screenshot 2023-11-13 212922" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/2942c414-d454-4af7-ad21-4522537d6312">

### Cloud RAN
<img width="700" alt="Screenshot 2023-11-13 213508" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/3107841d-e559-4f9d-b9bf-93c9d2813d51">
<img width="700" alt="Screenshot 2023-11-13 213929" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/80e03a37-672f-44a4-891f-699209f3fff6">

## Beamforming and Beam steering
<img width="700" alt="Screenshot 2023-11-13 223901" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/9710809b-5eb1-4b94-8070-f89c99fb82c8">

<img width="700" alt="Screenshot 2023-11-13 224526" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/8fc1ef27-7fcd-4c7a-a3fd-2a47ae6def4d">


- Each antenna is transmitting signals at a speed of 10Mb per second
- In single user mimo there are four antennas at transmitter and four at receiver, also calle 4*4 order
- In multi user mimo there are 2 antennas each at transmitter and receiver


<img width="700" alt="Screenshot 2023-11-13 224604" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/cc86e84c-31b9-4b0e-b4d0-0471caa52bf8">

### Antenna for mmWave
- If we increase the frequency from 3 to 30 GHz, its dimensions would be reduced 10 times.
<img width="700" alt="Screenshot 2023-11-13 225043" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/6a45d858-aaaa-4ce4-94c4-fd2ca6096f71">

### 3D beam forming
<img width="700" alt="Screenshot 2023-11-13 225248" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/8390a9ec-0661-418d-b95b-7c249932da49">

### Beam forming and Massive MIMO
<img width="700" alt="Screenshot 2023-11-13 225622" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/e54f0e1b-a017-443c-91b1-52d8df246f06">
<img width="700" alt="Screenshot 2023-11-13 225653" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/0baca3cf-f7ba-4e58-bf96-87128a0bdeef">

## 5G Network Arhitecture
<img width="700" alt="Screenshot 2023-11-13 231329" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/da7f6fba-428e-4b99-9a55-deab8de1f214">

- Access stratum signaling is that signaling which is going on between user equipment and gNB
- Non access stratum signaling is that signaling which happens between UE and core network
- Radio resource managmement- gNB has to decide that what resource blocks are being allocated to these UE in order to satisfy their demands in terms of quality and service
<img width="700" alt="Screenshot 2023-11-13 231655" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/1d554002-27ff-49e5-b162-666ab4011a8e">

### PDU(Protocol data unit) sessions
<img width="700" alt="Screenshot 2023-11-13 231751" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/5fdf4094-8718-48fb-9f35-7e6d692093a1">

- In order to provide services, network need to establish PDU session with UE's
- Each PDu session may contain one or more QoS

### Control and User plane
<img width="700" alt="Screenshot 2023-11-13 232432" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/ca1d3409-31c0-44cf-8784-566e42d8762f">

## AMF(Access and mobility  managment function)
<img width="700" alt="Screenshot 2023-11-13 233806" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/8e3df5a9-a4c4-4ccc-ad8d-4872047b5313">

- AMF is resposible for registering the UE to the network.
- When a UE moves from one TA(tracking area) to other then then tracking area number needs to be updated in the core network which is handled by AMF


### Authentication Server Funtion(AUSF)
- Whenever UE wants to register itself to a network or make a call, it is done by AUSF
- Whenever AMF inititaes the authentication process it sends the identity of UE to AUSF .
- AUSF requests UDM to generate the authentication vector which is generated by a secret key

<img width="700" alt="Screenshot 2023-11-13 234925" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/231451e8-c669-45f9-bf28-000aa1e6c7bf">

### SMF(Session management function)
<img width="700" alt="Screenshot 2023-11-13 235057" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/40d0a400-a026-44a3-99bf-d8b354ad8341">

### UPF(User Plane Function)
- When a UE moves it may go from coverage area of one tower to another but it  would always be have PDU session established with UPF
<img width="700" alt="Screenshot 2023-11-13 235521" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/1217b840-94c5-4374-b6d0-41f3a52d2047">

### UDM(Unified Data management)
- It is the centralised database for all the subsciber in 5G network
- UDM can have internal data base, built in , or it can use external database like UDR
<img width="700" alt="Screenshot 2023-11-14 002502" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/0bb8e2a7-a7ec-4744-a9e4-1f7e5abd80aa">

### PCF(Policy charging function)
<img width="700" alt="Screenshot 2023-11-14 002647" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/3a479643-69eb-4a3b-b3e7-be32414d8715">

### AF(Application Function)
<img width="700" alt="Screenshot 2023-11-14 002935" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/d8013751-9d4a-4134-b0e2-05a1893384a3">


## NFV(Network Function Virtualization)
<img width="700" alt="Screenshot 2023-11-14 194904" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/9f93f930-f6f7-4574-ba59-ae66286ffa69">

<img width="700" alt="Screenshot 2023-11-14 195203" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/ef1c5e70-fc84-42eb-9180-1b3f13abb101">


#### NFV Architecture by ETSI
- *ETSI*-European Telecommunications Standards Institute

<img width="700" alt="Screenshot 2023-11-14 195344" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/76b4dda5-5458-4763-9033-9ee566e8e4d7">



<img width="700" alt="Screenshot 2023-11-14 195638" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/38c361e5-d445-4b8a-965c-3c268edbb031">

<img width="700" alt="Screenshot 2023-11-14 201200" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/ef3f67e3-08e5-4294-acb2-1a67b7d2a776">

### Network Slicing
<img width="700" alt="Screenshot 2023-11-14 201339" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/2a9c61ca-d264-4429-86da-ed1a4e74d197">

<img width="700" alt="Screenshot 2023-11-14 201445" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/6e4d0161-973d-44b5-aff9-336f3bbecef8">

## NRF(Network Repository Function)
- If NSSF wants to know where the network functions of SMF are located then NRF receives request of NF
- All network function have to  register themselves with NRF so that it can facilitate  their discovery by other Network Function
<img width="700" alt="Screenshot 2023-11-14 204622" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/cca106f0-33ee-4b1c-aa2d-7d402f2843a9">

### NSSF(Network slice selection function)
<img width="700" alt="Screenshot 2023-11-14 204715" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/983b51fb-1464-4caa-a6a8-aa4d94e40451">

### NEF(Network Exposure Function)
- It plays a key role in security of the devices in network
<img width="700" alt="Screenshot 2023-11-14 205059" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/1b619a1c-5ac1-4770-aa0d-5b57eaccf724">


## Identifiers in 5G
- IMSI(International mobile subscriber identity) for 3GPP access
- NAI(Network access identifier) for non 3GPP acsess
- SUCI is called after encryption in SUPI
- The device uses SUCI to register itself on the network after powering on first time
<img width="700" alt="Screenshot 2023-11-14 205735" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/b9907413-1b58-4c02-b310-c09504b92ab0">

<img width="700" alt="Screenshot 2023-11-14 214556" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/42b5b394-2db6-495b-a726-25754c33258a">


## Tracking areas in 5G
- In case of idle mode, the location of the device is known at the level or tracking area. Network does not know that in which cell the device is located.
- The purpose of building tracking area is to reduce the signaling load while mobile is idle as in that case we need to only update the location of device when it moves from one area to other.
- In case when the device is moving very fast i.e on a train, in that case the network can assign a list of tracking areas to this device so that if the device is moving very fast so that it does not need to update its location to the network.
<img width="700" alt="Screenshot 2023-11-14 214839" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/2ed8180a-3cd5-4324-9b0f-394528f09d9b">

### 5G Network identifiers
- Identitiy of the device is called PLMN-ID which is combination of mobile country code and mobile network code.

<img width="700" alt="Screenshot 2023-11-14 215412" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/103f07cb-ec26-4898-b3bc-59a3533e5581">


## UE Power on procedure
- *PSS*- Primary synchronization sequence
- *SSS*- Secondary synchronization sequences
- Reading PSS and SSS will enable the device to decode the broadcast information on each of the cells
<img width="700" alt="Screenshot 2023-11-14 234951" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/9e8f66d7-f391-4662-8d7c-82b3ff85a397">

<img width="700" alt="Screenshot 2023-11-14 235533" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/b8581167-6ec5-4a66-8465-441c63589430">

- UE goes to the best cell in the selected PLMN network

<img width="700" alt="Screenshot 2023-11-14 235939" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/202f93ca-7f34-4418-8ce2-46a00c165ae6">

<img width="700" alt="Screenshot 2023-11-15 000009" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/0b8e73a9-8111-496e-a35c-185eec53e700">

<img width="700" alt="Screenshot 2023-11-15 000055" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/5b20e50c-977e-4d32-9115-bc3879c5262c">

<img width="700" alt="Screenshot 2023-11-15 000121" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/16d6cf35-20aa-4071-956e-7dd11e79fb91">

<img width="700" alt="Screenshot 2023-11-15 000224" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/a2259972-2f1a-46fe-9a67-d91901080738">

<img width="700" alt="Screenshot 2023-11-15 000305" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/09a71a79-b121-49c6-9f80-10359a16efd6">










































































 



















































































