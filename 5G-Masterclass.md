# The 5G system
## Standardization of 5G
- It is necessary to make our UE's work across the world, if the system is not standardized then it will not be possible for any user from one are to access services of another area.
- ITU(International Telecommunication Union) is the body which is responsible for all matters for information and communication technology.
  *Divisions of ITU*
   - Telecommunication standards(ITU-T)
   - Radiocommunication(ITU-R)-It is particularly involved in wireless telecommunication.
   - Telecommunication development(ITU-D)

- Requirements of 5G
<img width="700" alt="Screenshot 2023-11-07 214649" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b7d63816-184a-40c0-80a2-7c0135f50376">

## 3GPP(3rd Generation partnership project)
- Different telecommunication organisation from diffrent parts of world come  together to co create technologies specified by ITU.A lot of private companies also participate in this project.
<img width="700" alt="Screenshot 2023-11-07 210346" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/594f78c1-e25b-4048-bb23-4f3ca44914da">    
<img width="700" alt="Screenshot 2023-11-07 210525" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/97143531-7b88-4acc-b4be-9ac96b0d6029">

#### TSG(Technical specification group)
1.*TGS RAN*-It takes care of all topics related to wireless communication.

2.*TGS CT*- It handles mobility and security.

3.*TGS SA*- Different multimedia codecs and management.  

<img width="700" alt="Screenshot 2023-11-07 211101" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/1c00d903-9327-4a15-9620-46abd1cd6e8d">  
<img width="700" alt="Screenshot 2023-11-07 211148" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/9dec4b01-b4d3-4dcd-b800-acb4c0d2669a"> 

## Use cases of 5G
<img width="500" alt="Screenshot 2023-11-07 211633" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/35d4a343-e8e4-4757-bf4c-e618aa3d2ce9">  

#### eMBB
<img width="700" alt="Screenshot 2023-11-07 212119" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/d51db53c-3cc9-4018-920b-b90d0e6716ee">

#### mMTC
<img width="700" alt="Screenshot 2023-11-07 212259" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/45cb9439-86dc-47d0-a52b-d841a9800c6d">

#### URLLC
<img width="700" alt="Screenshot 2023-11-07 212432" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/29435ae4-6fd2-4c60-bacc-23edb9fba274">

## The 5G system
<img width="700" alt="Screenshot 2023-11-07 213240" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/05f3ee69-8237-4156-b374-bdbc392fb5c4">  

#### Representation of 5G network
<img width="700" alt="Screenshot 2023-11-07 213338" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/99970658-8478-408f-9f65-cb238af43b3a">  

#### Control and User plane
<img width="700" alt="Screenshot 2023-11-07 213605" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/2be64d01-abf5-4a57-9f2f-48506522f8f1">  

- *UPF*- Mobility anchor, policy enforcement, lawful interception
- *SMF*- Session management function (AMF(Access and mobility function) forwards all session related messages to SMF)
- *AUSF*(Authentication server function)- It supports AMF
- *UDM*-It is front end for USR(User subscription data) and provides info to AMF when necessary.
- *PCF*- It supports charging related functions.It provides policies for session management and no session management policies.

## 5G Deployment options
- *EPC*-Evolved packet core
- For now we are dependent of 4G LTE(eNodeB) for voice calls and dependent on 5G(gNodeB) for accessing internet.
- We can make some modifications in existing network and achieve an efficient and optimized system.
<img width="500" alt="Screenshot 2023-11-07 215627" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/85c35f3f-3d38-4926-a7fe-fbaeb0e1ac9a">
<img width="500" alt="Screenshot 2023-11-07 215651" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/bd5f0547-59e9-4c1f-a1bc-3cc764c59101">
<img width="500" alt="Screenshot 2023-11-07 215808" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/6ea36d74-6741-4a25-a995-52a796aaf77b">

##### Option 3
- The core network sends data to eNodeB and it splits data stream , in which part one part is sent to UE and other part is sent to gNodeB which is then sent to UE 
- eNodeB sends data at smaller rates wheresa gNodeB sends it at a much higher rate
#### Option 3a
- Data is directly sent from core network to gNodeB at much higher rate but it has few disadvantages as it used eNodeB for voice calls.
#### Option 3x
- It is the combination of above two options in which eNB and gNB also communicates with each other as well as send data to UE.
<img width="500" alt="Screenshot 2023-11-07 220040" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/2989852d-eff4-483f-a676-5154dba106cf">
<img width="500" alt="Screenshot 2023-11-07 220114" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/7932a3a2-5861-4d6e-88d8-1a606141cfbb">
<img width="500" alt="Screenshot 2023-11-07 220219" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b880baaf-f0e1-4e39-8cee-1c0a486d468d">
<img width="500" alt="Screenshot 2023-11-07 220322" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/fe5ac2d1-fbae-4abf-a6c5-7a940d0a31b9">
<img width="500" alt="Screenshot 2023-11-07 221948" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/cde0393e-50eb-4578-bb1e-4490f0a49d78">

- Option 6 is not officialy supported.
#### Stand alone(Option 1,2) and Non stand alone(Option 3,4,7)
<img width="500" alt="Screenshot 2023-11-07 222006" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/79331cf7-63e5-4482-8583-6a1a0d19e76a">


# 5G NR
## The RAN Protocol Stack
- There are two types of RAN protocol stack
- *UPPS*-Supports carrying user data between different network and UE
- *CPPS*-Carry control information between UE and core network
  <img width="700" alt="Screenshot 2023-11-07 231427" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/d41312bc-db4b-4145-acfb-4f3ef8400da3">
- SDAP layer is to support quality of service
- Each down layer provides services to upper layers.

### User plane protocol stack
1.**Physical Layer(PHY)** - For Efficient wireless communication.

2.**Medium access control layer(MAC)** - Retransmission, multiplexing/demultiplexing and secheduling
<img width="650" alt="Screenshot 2023-11-08 124627" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/593e3ed9-9390-44c0-b88b-7a4b93d39978">

3.**Radio link control layer(RLC)**- ARQ(Automatic repeat query) segmentation

4.**Packet data convergence protocol(PDCP)**-Header compression, ciphering and intergrity protection and duplicate removal.

5.**Service data adaption protocol(SDAP)**-Quality of service

#### Service data unit(SDU) and Protocol data unit(PDU)
<img width="700" alt="Screenshot 2023-11-08 125704" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/6c0d4819-c728-4646-822f-3ef0de67a438">

<img width="700" alt="Screenshot 2023-11-08 130028" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/769ca761-4662-45c0-93f5-fc8b07552bf7">  


### Control plane protocol stack
1.**Non access stratum(NAS)**- Authentication, security and idle model procedures also assigns IP address
2.**Radio resource control(RRC)**-System information, radio bearers and measurement configuration; responsbile for RAN related control plane procedures i.e broadcasting systum

## SDAP(Service data adaptation protocol)
- *Types of traffic*
<img width="700" alt="Screenshot 2023-11-08 131256" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/bdf6a2ad-664a-4dd1-946a-418ad01776c6">

- *QoS flows*
  - When addtional QoS flow is required it can be established when corresponding application triggers traffic.

 <img width="700" alt="Screenshot 2023-11-08 131407" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/e1b78799-de89-417e-a55d-f7304fe1525f">  
 

   - QoS flow types
     - *GBR*- Guranteed bit rate QoS flow
     - *Non- GBR*- Used for traffic that are more bursty in nature
     - *Delay critical*- for self driving cars and remote control devices
     
<img width="450" alt="Screenshot 2023-11-08 131921" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/c5ae912b-6ace-490c-9af6-992b7a06482e">  
<img width="700" alt="Screenshot 2023-11-08 132151" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/66c97764-fbc9-4484-af6d-137a32d6ce20">

### 5QI(5G QoS identifiers)
<img width="600" alt="Screenshot 2023-11-08 132242" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/9f520bc2-b042-45d5-b848-bfc77c49c214">

#### Multiplexing
<img width="700" alt="Screenshot 2023-11-08 132342" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b98a51d7-c332-4249-8093-d9f62c9f6e5d">

#### Uplink QoS
- *Reflective mapping*- When the device use same QoS flow and radio bearer as in downlink 
- *Explicit mapping*- When the devie is configured to use specific QoS flow and uplink bearer using RRC signaling

<img width="700" alt="Screenshot 2023-11-08 132941" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/5ce1e10b-a2a2-4b66-9902-62160166231f">

## PDCP(Packet data convergence protocol)
*Fucntions of PDCP*
- Header compression
- Ciphering and integrity protection
- Routing and duplication of split bearers
- In sequence delivery
<img width="600" alt="Screenshot 2023-11-08 133217" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/3a9eb315-06d6-47bb-85a3-59477856d7b6">

- For small data packets, header itself would itself be as long as data packet.
- PDCP performs header compression to reduce header length to a couple of bytes for wireless trasmission
- Decompression of header size before it is transmitted over IP protocols in the wired network is also done by PDCP
- The header compression scheme is based on Robust header Compression(ROHC) protocol

<img width="600" alt="Screenshot 2023-11-08 133722" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/e748164d-f9c4-4f6e-aa6a-064bde5c2ba5">
<img width="600" alt="Screenshot 2023-11-08 134123" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/f0f78b07-4840-45d3-b518-579d98fb8c31">
<img width="600" alt="Screenshot 2023-11-08 134212" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/0c5ff28d-6784-43ae-9263-822b7ec95fe9">

- If one fails , UE's can recieve data from the other bearer.
- In recieving side PDCP is responsible for discarding the duplicates and picking the  packet (selection diversity) if there is an error in any radio bearers.

<img width="600" alt="Screenshot 2023-11-08 134613" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/c48cee56-0049-4ed4-818b-89bf31bc3a7c">

- PDCP acts as a sequence number to ensure in-sequence delivery

## RLC(Radio Link Control)
*Function of RLC*
- Segmentation
- ARQ - Retransmissions
<img width="600" alt="Screenshot 2023-11-08 135047" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/6f3a79b9-3463-4426-adf9-aa9369311c3c">

- *Transparent mode*- In these cases the channels are already designed in such a way that there is no need for segmentation and retransmission
- *Unacknoledged mode* - When error free delivery is not required
- *Acknowlaged mode*- For web browsing , file transfer etc.
<img width="600" alt="Screenshot 2023-11-08 135659" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/448fc7a1-d1d4-4862-8771-0a68fd117a6e">

- 6 and 12 bits for unacknowledged mode
- 12 and 18 bits for acknowledged mode
- In case of segmentation each SDU carries same sequence number as unsegmented SDU
- RLC PDU are assembled as soon as possible without waiting and the MAC layer performers the concatination depending on the trasferred larger size which ultimately helps in low latency applications.-
- In LTE the PDU's are also concatenated to one big PDU, in NR  this is not done by RLC layer.
#### Retransmissions
- In LTE, RLC takes care of in sequence delivery
- In NR  this is taken care by PDCP because of two reasons:
   - Latency
   - Buffering requirements

  
-The RLC sends PDU's, if the PDU are succesfully received then it is delivered to higher layers
<img width="700" alt="Screenshot 2023-11-08 203307" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/c5f68186-da0a-499f-a531-b957983216b7">
<img width="490" alt="Screenshot 2023-11-08 203532" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b699f9d9-b15c-4065-8f6a-2ab67cb32b76">
- Duplicated action is also responsiblity of RLC
- Time 2:missing PDU arrives,If n+1 arrives two copies then one of the copies is dicarded

- Time 3: Tansmission continues with n+3,4,5
- Time 4: Status report, indicating the missing PDU's
- Time 5: Receipt of status report
- Time 6: All PDU's have been succesfully received

## MAC(Medium Access control)
*Functions of MAC*
- logical channerl multiplexing
- hybrid-ARQ retransmissions
- scheduling
- multiplexing/demultiplexing for CA
- MAC layer provide services to RLC by help of logical channels

<img width="700" alt="Screenshot 2023-11-08 204633" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/82774570-22eb-4abb-817c-00c3c92fa7b2">

- *Logical channel*- It is defined by type of information it carries generally classified by type of information
- *Transport channel*- It is defined by how and what characterstics are the information is transmitted over
<img width="600" alt="Screenshot 2023-11-08 204923" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/caf8c8cc-e48b-4adb-8fea-4c4bf9863608">

*Logical channels*

- PCCH is used paging of devices whose location at cell level is not known to network
- BCCH is used for transport of network information from network to all the cell
- CCCH is used for transmission of control information in conjuction with random access processes
- DTCH is used for transmission of user data to and end from devices. This is logical channel used for all unicast uplink and downlink channel of user data. It handles much of data traffic
- DCCH is used for transfer of control information to devices

*Transport channels*
- Data on transport channels are organised into transport blocks. A certain transport block can be transmitted in a TTI  in various formats in accordance with modulation scheme used,antenna configuration,etc
- PCH is used for transport of paging information from PCCH in logical channels
- BCH is used for transport of BCCH ,more specifically master information block
- *DL-SCH*- It is the main transport channel used for transmission of  downlink data in in NR
- *UL-SCH*-Uplink counterpart of downlink shared channel
<img width="700" alt="Screenshot 2023-11-08 210741" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/1b30dfce-256e-429c-b59f-bc56700db6c6">
- The basic principle of carrier aggregatgion from physical layer perspective is that physical layer process happens indepedently.

*HARQ*- The main mechanism in transmission of 5G system is HARQ (hybrid ARQ). It is called hybrid because it supports errror correction using channel coding  and retransmission when error cannot be corrected.
<img width="700" alt="Screenshot 2023-11-08 211926" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/f0b05960-9498-43d6-8cd8-6c239bf67dc3">
- Each process transmit a data unit and waits for feedback before transmitting next data unit
<img width="700" alt="Screenshot 2023-11-08 212335" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/161ad402-0777-49ee-8138-688a54ed697c">
<img width="700" alt="Screenshot 2023-11-08 212646" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/2a0ac904-fd5a-4ec0-ad16-97e894ad46ea">

## MAC Scheduler
- The job of schedule is to determine which devides should use which time frqeuency and antenna resources
- Scheduler is a part of a MAC layer but it  interacts with differnt layer in order to carry out differnt funcitons
<img width="700" alt="Screenshot 2023-11-08 212959" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/0a645469-f46e-48d4-8dda-5e8583c9bd30">
<img width="700" alt="Screenshot 2023-11-08 213444" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/60fee0f3-d326-4d3c-a535-b41b75c92ce2">
<img width="700" alt="Screenshot 2023-11-08 213745" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/7692ad60-a7f7-4c42-86fd-26f0ff26f5ed">

- As the time progresses the channel conditions also change and based on that the scheduler changes the device which device get correct transmission

<img width="700" alt="Screenshot 2023-11-08 214420" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/cc1165f7-6191-4c9f-aebe-a746632e3f43">

- When there is huge data to be send the device can be scheduled to use larger  bandwidth and after the work is done it can switch back to smaller bandwidth
- Adpatation is also controlled by scheduler
<img width="700" alt="Screenshot 2023-11-08 214638" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/573cd72b-bae6-4bb7-9c1b-be3d130274dd">
<img width="700" alt="Screenshot 2023-11-08 214900" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/fc0b54d2-cec1-40c3-b031-9dcdc5340ae2">

- Most commonly used mechanism for scheduling is *Dynamic Scheduling*

*Dynamic scheduling*-Dynamic scheduling, as its name implies, is a method in which the hardware determines which instructions to execute

*SPS(Semi persistent scheduling)*- It is a mechanism for improving the efficiency and reliability of resource allocation for periodic data transmissions. It is used in wireless communication systems, specifically in Long-Term Evolution (LTE). It is activated whenever the need arises and then deactivated. It can be enabled or disabled using DCI


<img width="700" alt="Screenshot 2023-11-08 215358" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/f1d87e68-1abc-4a47-aedc-777d30c736df">
<img width="700" alt="Screenshot 2023-11-08 215510" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/9db83978-2506-48f7-9bbb-394892a0c682">

##### Uplink scheduling
- Uplink has a lot of flexibility than downlink in terms of scheduling
- SRS(Sounding reference signals) supports only a maximum of 4 antenna ports whereas CSI-RS can use 32 antenna ports
<img width="700" alt="Screenshot 2023-11-08 215845" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/7bbb15f5-8f81-4e6d-aca8-d27900f10be0">

- Uplink supports two configured scheduling


<img width="700" alt="Screenshot 2023-11-08 220129" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/26397268-ee32-46e5-9139-c86457f83046">

## PHY(Physical Layer)
- It mainly handles mapping of transport channels to physical channels
<img width="700" alt="Screenshot 2023-11-08 220919" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/6de2d4e0-29ea-4508-8d09-7f2f8f3f6cfe">
<img width="700" alt="Screenshot 2023-11-08 221137" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/2d64b00b-9388-43e4-82f2-3b19b5ac7cf1">


- *DCI*(Downlink control information) provides necessary information for reception and decoding of downlink data
- *UCI*(Uplink control information) which  provides scheduler information  about the situation at the device

<img width="700" alt="Screenshot 2023-11-09 120604" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/4d7323b0-e3b4-481c-b7e2-7c9386e18444">

- *CRC(Cyclic redundancy check)*- Error detection in transport block level.It also request retransmissions.Its length can vary according to payloads ; 24 bit CRC is used for payloads larger than 3824 bits and if the payload is smaller than that a 16 bit CRC is used
<img width="700" alt="Screenshot 2023-11-09 121001" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/d4118566-f31e-413c-9149-2ef87b6b1414">

- *LDPC(Low density parity check)*
<img width="700" alt="Screenshot 2023-11-09 121426" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/3d911aa5-401f-44f6-83dc-7d5fad3da648">

- *Code Block segmentation*
<img width="524" alt="Screenshot 2023-11-09 121157" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/17c6d2d3-ea4c-48ff-98a6-4120c0ee3d9a">

- *Rate matching*- To extract the set of bits to be transmitted
<img width="700" alt="Screenshot 2023-11-09 121547" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b95fcdae-bc66-4b1d-814d-b54806ad6e05">
<img width="700" alt="Screenshot 2023-11-09 121723" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/bb93fea5-8017-4a6b-8487-38dd6fbda699">
<img width="700" alt="Screenshot 2023-11-09 121819" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/406068c4-6de0-4db4-9bce-425170f73126">
<img width="700" alt="Screenshot 2023-11-09 121927" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/c8651517-11df-4e1b-b056-d7c3ad3dcc39">
<img width="700" alt="Screenshot 2023-11-09 122025" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/df5c8b49-af50-4b94-9585-0bb5ca1ddf12">
<img width="700" alt="Screenshot 2023-11-09 122156" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/03eef58d-e782-4b2b-9817-fe16005e817d">

## The Physical layer structure

*Modulation scheme*

<img width="700" alt="Screenshot 2023-11-09 122448" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/329deaa8-eb24-4a24-8351-322ccc379bbd">


- *OFDM*- It can be used to transmit a wideband signal using multiple narrow band signals
- Larger cells would require large cyclic prefix and vice vers
*Disadvantage of OFDM*
- High peak power to average power ratio
<img width="700" alt="Screenshot 2023-11-09 122707" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/85b4c044-5358-4245-b63b-0519c3c8c26f">
<img width="700" alt="Screenshot 2023-11-09 122958" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/9321aeb2-2776-456c-b39a-ac513eae5f48">

- For example-if vehicular technology, if one vehicle has to speak to another vehicle then instead of speaking to gNB they both can directly communicate between one another.
<img width="700" alt="Screenshot 2023-11-09 123426" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/110b6f62-a141-49d0-8ca1-ea0121379eb6">

- 240kHz  subcarrier spacing is not used for data channels and it supported only for SS block  
<img width="700" alt="Screenshot 2023-11-09 123745" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/72869a43-4913-46fa-997d-1dd38bc85565">

*Time Domain*

<img width="700" alt="Screenshot 2023-11-09 123859" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/3831908f-37bd-4aa2-834b-285e670d04df">
<img width="700" alt="Screenshot 2023-11-09 124138" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/b48ac2c5-bbf7-4fc2-9e2e-f8b9340095f5">

## RRC and NAS

- Responsible for connection setup, mobility and security related functions

<img width="700" alt="Screenshot 2023-11-09 124320" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/2cb81503-386b-44a8-8456-cd45197857e7">

- RRC inactive is newly introduced in NR

<img width="700" alt="Screenshot 2023-11-09 124646" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/84ccc122-d492-42d8-844d-910b94d5aba1">

## Mobility functions

<img width="700" alt="Screenshot 2023-11-09 125245" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/1c42085c-9513-458a-96bf-9d1fd3778311">

- Connected mode mobility is triggered by network whereas idle and inactive based mobility was based on decisions by device

<img width="700" alt="Screenshot 2023-11-09 125540" src="https://github.com/raunakkk21/5G-for-everyone/assets/143111163/cd96137f-be94-4b88-af99-50f6c2bbe83c">  

## Initial access procedures
- *Cell search*= Procedure by which a UE acquires time and frequency synchronization with a cell and detects the cell Id of that cell
<img width="700" alt="Screenshot 2023-11-09 132449" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/cbb9ec16-558e-4db1-be8e-13c6df93c32d">

*Working of cell search*
- In LTE there are tens of different bands, UE starts scanning a set of frquency band that is preferred. This informationis available in SIM card
- In LTE carrier raster is equal to synchronization raster which is 100kHz
- In LTE sync signals are transmitted every 5ms
- In NR there are much more bands than LTE
- In NR sync signals are transmitted every 20ms before checking next possible location
-  To improve the efficiency the Sync raster and carrier raster are decoupled

<img width="700" alt="Screenshot 2023-11-09 133413" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/3090c77a-78ed-43f6-a648-0b943be740fa">

- PSS can take one of  the three possible values
- SSS can take 336 possible values
<img width="700" alt="Screenshot 2023-11-09 133635" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/0ce26fae-6431-4dfe-8dd6-8c208ebb8b39">
<img width="700" alt="Screenshot 2023-11-09 133743" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/22cde1ee-528b-4f93-9799-3efe12aacddc">
<img width="700" alt="Screenshot 2023-11-09 133901" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/b8c19f99-add8-44bf-bc87-9c57ae5d31ac">
<img width="531" alt="Screenshot 2023-11-09 134014" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/c0504f50-7eb0-4adf-92d3-da3dfc556515">
- UE decides if to camp or not

## RAP(Random access procedures)
- *Triggers when*
   - RRC idle to RRC connected
   - Uplink data
   - Sync lost
   - Sync during handover
 
<img width="700" alt="Screenshot 2023-11-09 135056" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/165e9ce8-32a3-4df2-8647-fca650ea7c9f">  
<img width="700" alt="Screenshot 2023-11-09 140109" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/c563bc89-7df5-453e-9a3f-c5c4ac26800c">
<img width="700" alt="Screenshot 2023-11-09 140238" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/282a5828-b223-490f-8e32-d7f80c350336">
- Same preamble= same temp ID = Collision
<img width="700" alt="Screenshot 2023-11-09 140517" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/2fd50aef-163d-494e-934d-4a88794ced29">

<img width="523" alt="Screenshot 2023-11-09 140717" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/bdddab59-03bc-4ddc-86cc-9449f7684f57">

#### CFRA(Contention free random access)
- *Triggers*:
   - Handover
   - DL data for UE
   - Non stand alone mode, NR cell

- gNB makes sure that id does not give same preamble to more than 1 device
- CBRA is triffered by UE whereas CFRA is triggered by gNB
  
<img width="700" alt="Screenshot 2023-11-09 141230" src="https://github.com/raunakkk21/Everything-about-5G/assets/143111163/cebf9959-9e5d-427e-9817-49cb88dad93c">

     














 

  


























































  

  







  
  


























 
























  












  
  
  
















































       










 


 














































  

     
