# COMPUTATION:
- Process data on the cloud by making use of powerful processors whichserve multiple instances at a time.
- **HOST**: provides the functionality to start and control VMs and containers.
- **HYPERVISOR**: a program used to run and manage VMs on a computer.                     
     1.  **Type 1**  bare-metal or native.       
     2.  **Type 2**  hosted hypervisors.
- **VM**: A virtual machine is a computer file, that behaves like an actual computer including running applications and operating system.
   - types of VM              
      1. System Virtual Machine              
      2. process virtual machine
- **CONTAINERS**: packages of software that contain all of the necessary elements to run in any environment    
      1. Docker
      2. RXT
      3. PODMAN
      4. LXC

  # NETWORKING:
  - it includes services which provide a varietyof networking features such as security, faster access etc.
  - **OVs**
     - ovs- vswitchd
     - ovsdb-server
  - **LOADBALANCER** : distribution of set of task 
      - LAYER 4 :  Load balancers act upon data found in network and
      - LAYER 7 :  load balancers distribute requests based upon data
  - **OSI LAYER**
     1. Physical Layer
     2. Data link Layer
     3. network layer
     4. transport layer
     5. session layer
     6. presentation layer
     7. application layer
        
- **IP ADDRESS** -INTERNET PROTOCOL(IPv4,IPv6)

  - Public IP- ex:starts with 11..
 
  - Private IP-10. ,172. ,192. . 

  - Local IP-ex:starts with 127.0.00[a specific number]

- **PORT NUMBER**-

  - eg:HTTP-80

  - HTTPS-443

  - FTP-20,21

  - SMTP-25

  - TELMET-23

  - SSH[secure shell]-22

  - **DNS** (turns domain name into IP address)

 -   ***CDN(content delievery network)***
A content delivery network (CDN) is a group of geographically distributed servers that speed up the delivery of web content by bringing it closer to where users are.

##### SNOWBALL
  it is a way of trransferring the data physically.

- **ping**

- **NIC**

- **ethernet**

- **tap(temporary applicant pool)**

- **API**

- **rest api**

# STORAGE: 
 
- **block storage** ex:EBS

- **OBJECT STORAGE** ex:S3

- **db**-HELP TO MANAGE SERVICES

- **caching** ex:redish

- **RAM**

- **ROM**

- **OPTICAL DISK**

- **HDD(hard disk drive)**

- **SSD(Solid State Drive)**-new generation of storage device 

- **SHARDING**- process of storing a large database across multiple machines. a type of database partitioning that separates large databases into smaller, faster, more easily managed parts.

- **CEPH**

- **ETCD**-etcd stores data in a multiversion persistent key-value store.

## Architecture

- **api gateway**- act as mediator between server and client.

- **ELK STACK**-it is a open source and combination of elasticsearch,logstack and kiibana . it is alog management platform that provide centralized logging to identity the problems with users.

- **prometheus and grafana** opensource tools for application monitoring and analysis. 

- **Von Neumann architecture**

- **harvard architecture**

- **ISA(INSTRUCTION SET ARCHITECURE)**-defines how the CPU is controlled by the software.

- **CISC**- COMPLEX INSTRUCTION SET COMPUTER - CLOSED SOURCE-INTEL,AMD

- **RISC**- REDUCED INSTRUCTION SET COMPUTER - CLOSED SOURCE -ARM

  RISC V 
  
## SYSTEM DESIGN 

- **MQTT(MESSAGE QUEING TELEMETRY TRANSPORT)**- SMART SENSORS AND OTHER INTERNET OF THINGS(IOT).it is basicallly a messaging protocol.

- **PUB-SUB (PUBLISH/SUBSCRIBER)**- USED TO DISTRIBUTE SERVICE

- **SQL**-manage the permission on server.it is structured database and having predifed schema.

- **NOSQL(NOT ONLY SQL)**- it is unstructured and having dynamic schema.

- **CAP THEOREM**-it gave guarantee of only two characterstics: availabity,consistencyand partition tolerance.

## PROPERTIES
- **AUTO SCALING**

- **reliability**

- **HA(HIGH AVAILABILITY)**

- **REDUDANCY**

- **SECURITY**
  - **ZERO TRUST SECURITY** (ZTS) 
  
  - **ZERO TOUCH PROVISIONING** (ZTP)

  - **HTTPS**

  - **SSL(SECURE SOCKET LAYER)**- STANDARD FORM-X.509 
                                ex: caddy

  - **BGP(BORDER GATEWAY PROTOCOL)**-USE TO EXCHANGE ROUTING INFORMATION BETWEEN AUTONOMOUS SYSTEM(AS)

## CONCEPT
  - **RABBIT MQ**(message-queueing software)-OPENSTACK

  - **RAFT** AND **ROUND-ROBIN**-LOAD BALANCER
    
    
  
