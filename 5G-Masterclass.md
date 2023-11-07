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










































  

     
