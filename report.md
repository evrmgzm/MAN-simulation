![A close-up of a logo Description automatically generated](media/c0c86fffe1b10b282de46e6aa77c3ecc.png)

![meneviş mavisi, kare, dikdörtgen, güneş hücresi içeren bir resim Açıklama otomatik olarak oluşturuldu](media/5f5ed61736db2438b88c68f094399e10.png)

**DOKUZ EYLUL UNIVRESITY  
COMPUTER ENGINEERING**

**CME 3204**

**Data Communications and Computer Networks Midterm Project**

**2023-2024 Spring**

**Metropolitan Area Network Simulation**

**By**

**2020510039 Berkay Güzel**

**2020510009 Akif Selim Arslan**

**2020510091 Evrim Gizem İşci**

**1.INTRODUCTION**

**1.1. Project Definition and Problem Formulation**

A metropolitan area network (MAN) is a computer network that connects computers within a metropolitan area, which could be a single large city, multiple cities and towns, or any given large area with multiple buildings. A MAN is larger than a local area network (LAN) but smaller than a wide area network (WAN).

Computer Network planning and design is an iterative process, including topological design, network architectures, and network traffic characterization. Well-designed computer network architecture should support maximum number of network users, traffic load with minimum delay, and adequate hardware support for network expansions. However, the designer should keep the balance between the cost of network hardware and the system requirements. In this project, we built a Metropolitan Area Network (MAN) by using Cisco Packet Tracer software.

**1.2. The purpose and motivation of the project**

The purpose of this project is to design and implement a Metropolitan Area Network (MAN) using Cisco Packet Tracer software. The motivation behind this endeavor stems from the increasing demand for efficient and reliable network infrastructure within metropolitan areas.

By creating a MAN, we aim to address the following objectives:

-   Enhancing Connectivity
-   Optimizing Performance
-   Supporting Scalability
-   Cost-Effectiveness

By achieving these objectives, we aim to demonstrate the feasibility and benefits of deploying a well-designed MAN, showcasing its potential to serve as a reliable backbone for communication and collaboration within urban environments. This project serves as a valuable learning experience for students and professionals interested in the field of computer networking and infrastructure design.

**1.3 Term Definitions**

**Node**: In the context of computer networks, a node refers to any device that is part of the network. This could be a computer, server, router, switch, or any other device capable of sending, receiving, or forwarding data.

**Packet**: A packet is a unit of data that is transmitted over a network. It consists of a header and a payload. The header contains information such as the source and destination addresses, while the payload contains the actual data being transmitted.

**Channel**: A channel refers to the medium through which data is transmitted in a network. This could be a physical medium such as a wire or fiber optic cable, or a wireless medium such as radio waves or infrared.

**Protocol**: A protocol is a set of rules and conventions that govern how data is transmitted and received in a network. Protocols define things like the format of packets, the order in which they are transmitted, error handling procedures, and more.

**System**: In a broad sense, a system refers to a collection of interconnected components that work together to achieve a common goal. In the context of computer networks, a system could refer to a network of nodes and the software and hardware that enable communication between them.

**Architecture**: Architecture refers to the overall design or structure of a system. In the context of computer networks, it could refer to the design of the network topology, the choice of protocols and technologies, the arrangement of hardware components, and so on. Architecture encompasses both the physical and logical aspects of a system.

**Network**: Refers to all the components involved in enabling communication between computers and other hardware devices.

**Server**: Often referred to as a "file server" or "network server," it serves as the central hub for a network, hosting shared resources such as files, applications, or services. It typically requires more processing power and storage capacity compared to regular desktop workstations.

**Workstation**: The individual computers used by users on the network, such as desktop computers or laptops.

**Wireless**: A type of network that utilizes radio signals to transmit data between devices, allowing mobility and flexibility in device placement. Wireless networks require additional security measures compared to wired networks.

**Ethernet**: A standard networking technology commonly used for wired connections, typically capable of transferring data at a rate of 100 Mbps. It involves the use of cables and may also utilize hubs and switches for connecting devices.

**Router**: Acts as the central point of connection for a network, directing data traffic between different devices and networks. Routers assign unique IP addresses to devices and can provide security features such as firewalls and VPNs.

**Switch**: A high-speed networking device that directs data packets to their intended destinations within a network.

**HTTP**: The protocol used to send data over the internet is called HTTP. It specifies the instructions and services needed to transfer webpage data and is a component of the Internet protocol suite. The server-client paradigm underlies HTTP. For instance, a client might be a mobile device, laptop, or home computer. Usually, a web host running web server software like Apache or IIS serves as the HTTP server. Your browser makes a request to the relevant web server when you visit a website, and the web server replies with an HTTP status code. The server will transmit the website and any associated files to your browser if the URL is legitimate and the connection is approved.

**Channel**: Refers to either a physical transmission medium (such as a cable) or a logical connection (such as a radio channel) over which data is transmitted.

**DNS**: An application layer protocol used to translate human-readable domain names into IP addresses, enabling users to access internet resources using domain names.

**IP**: A fundamental protocol that facilitates communication between devices on the internet by assigning unique IP addresses to each device and providing a framework for routing data packets between them. IP operates at the internet layer of the TCP/IP model.

**POP**: Standardized method of emailing recipients. After being received by a POP3 mail server, emails are filtered and placed in the appropriate user folders. Upon connecting to the mail server to get their mail, the users receive the contents as a download onto their hard drive.

**FTP**: Created to facilitate file transfers over the Internet. A web browser, an FTP application, or a command line interface are examples of FTP clients that may be used to access files saved on an FTP server. It is possible to set up an FTP server to allow various kinds of access. For instance, anyone can access to the server using an anonymous FTP setup. Nevertheless, anonymous users might not be able to upload files and might only be able to access specific folders. To view and download files, users must log in if anonymous FTP access is blocked.

**2. METHOD AND SIMULATION**

**2.1 Simulation and Modeling Concepts**

A discrete-event simulation (DES) models the operation of a system as a (discrete) sequence of events in time. Each event occurs at a particular instant in time and marks a change of state in the system.

Modeling involves creating simplified representations of real-world systems to understand their behavior, analyze performance, and make predictions.

Benefits of Modeling and Simulation over Real Implementations are cost-effective, risk reduction, flexibility, speed and efficiency.

Challenges of Modeling and Simulation over Real Implementation are accuracy, validity, complexity, resource requirements.

**2.2. Simulation Environment/Tool**

In this project, we have chosen Cisco Packet Tracer as our simulation tool. Below is an overview of Packet Tracer's architecture, modeling concepts, capabilities, limitations, and how to program or run simulations using the tool:

-   **Architecture and Modeling Concepts**: Cisco Packet Tracer follows a client-server architecture. The server component manages the simulation environment, while the client component provides the user interface for designing, configuring, and interacting with the simulated network.
-   **Modeling Approach**: Packet Tracer adopts a discrete event simulation approach, where events such as packet transmissions, device configurations, and network changes are simulated sequentially based on predefined rules and timing. This approach allows users to observe the behavior of the network over time and understand how different configurations impact performance.
-   **Capabilities and Limitations**: Users can create complex network topologies, configure device settings, simulate traffic, and find network issues. However, Packet Tracer has certain limitations compared to physical hardware or more advanced simulation tools, such as limited support for certain protocols or hardware features found in enterprise-grade networking equipment.
-   **Programming or Running Simulation**: To program or run simulations in Packet Tracer, users can utilize the graphical user interface to drag and drop network devices onto the workspace, connect them using cables, and configure their settings through interfaces. Users can then start the simulation to observe how the network behaves based on the configured parameters.
-   **Modules, Libraries, Components**: Packet Tracer includes a comprehensive set of networking devices, protocols, and features found in Cisco networks. These include routers, switches, firewalls, access points, routing protocols, and security. Additionally, Packet Tracer provides built-in libraries of network components, simulation activities, and instructional materials to support learning and experimentation.

**2.3. Network Design Requirements**

**Number of the components:** 24 PC, 8 Laptop (Wireless user), 7 Smartphone, 5 Tablet, 10 web server, 4 FTP server, 1 DHCP server, 1 mail server, 1 DNS server, 2 VOIP, 1 (2811) router and 6 (2911) router that configurated with HWIC-2T for obtain 2 more serial port, 6 (2960-24TT) switch, 4 access point-PT.

**Interconnection topology:** Hierarchical topologies had been used in this project. In this project we use a hierarchical topology, with multiple layers of switches and routers. This type of topology is commonly used in large networks to improve scalability and performance. The use of a hierarchical topology suggests that the network is designed to be scalable and to support a large number of devices. The use of multiple routers suggests that the network is also designed to be fault-tolerant, so that if one router fails, the rest of the network can still function.

The network likely uses a variety of protocols, including TCP/IP for communication between devices, and DHCP for assigning IP addresses. The specific protocols used would depend on the specific devices and applications on the network.

We used in this project client server architecture. Client-server architecture is a computing model that divides tasks or processes between clients and servers, where clients request services or resources from servers. This architecture is commonly used in networking and web-based applications.

The interaction between clients and servers follows a request-response model, where clients send requests to servers, and servers process those requests and send back responses to the clients. This communication typically occurs over a network using standard protocols such as HTTP, TCP/IP, or FTP.

Client-server architecture offers several advantages, including scalability, centralized management, resource sharing, and security. Overall, it provides a flexible and efficient way to distribute tasks and resources in a networked environment, making it widely used in various applications, including web servers, email servers, database servers, and more.

**2.4. Requirement Analysis**

**Functional Requirements:**

**Support for VoIP**: The network must support Voice over Internet Protocol (VoIP) for conference events in the first branch's second facility.

**Web Browsing**: All users across both branches should be able to browse the web.

**Email Services**: Users should have the ability to send and receive emails.

**File Transfer**: Users must be able to transfer files between devices.

**Performance Requirements:**

Number of Users: The network should accommodate all users specified for each facility in both branches. First branch has contain 15 users and second branch has 29 users.

Speed of the Network: The network should provide adequate bandwidth to support the required services without significant latency or congestion. A pc has 100 Mbps bandwidth. A smartphone and tablet has 54 mbps bandwidth. Laptop has 24 mbps bandwidth and wireless pc 18 mbps.

**Constraints:**

Cost: 24 x 1000 PC, 8 x 1000 laptop, 7 x 250 smartphone, 5 x 400 tablet, 17 x 2000 servers, 7 x 900 routers, 6 x 1500 switch, 2 x 75 VOIP, 4 x 20 access point.

Hardware Limitations: Lack of ports of the routers we had to add HWIC-2T for obtain 2 more serial ports.

**2.5. Definitions of the System/Model**

**Assumptions:**

Device Compatibility: We assume that all devices used in the network design are compatible with Cisco Packet Tracer and can be configured according to its capabilities.

Stable Connectivity: We assume a stable connection between routers, switches, and end-user devices within the MAN.

Standard Protocols: We assume the use of standard networking protocols such as TCP/IP, DHCP, DNS, and VoIP protocols for communication.

**System Structure:**

The system structure consists of interconnected components including routers, switches, access points, servers, and end-user devices arranged in a hierarchical topology to facilitate efficient data transmission and communication within the MAN.

**Input Parameters:**

Network Topologies: We'll use hierarchical topologies with routers connecting branches, switches connecting facilities within each branch, and access points providing wireless connectivity.

Network Applications and Services: These include web browsing, email services, file transfer, and VoIP for conference events.

Network Configuration: This encompasses IP addressing, routing protocols (such as OSPF or EIGRP), VLAN configuration, and Quality of Service (QoS) settings.

Device Types: Hosts include PCs, laptops, smartphones, tablets, servers, and VoIP phones. Managed devices include routers, switches, and access points.

Destination and Number of Users: We have specific destinations and numbers of users for each facility within both branches as specified in the requirements.

**2.6. Simulation Elements**

1.  **System Entities**:
    -   Computer nodes (workstations, servers, routers, laptops, tablets, smartphones)
    -   Networking devices (routers, switches, access points)
    -   Servers (Web servers, FTP servers, DHCP server, mail server, DNS server)
    -   Queues (queues for packet transmission)
    -   Packets (data packets transmitted over the network)
    -   Flows of packets (data streams between different entities)
2.  **System State Variables**:
    -   Status of network channels (idle or busy)
    -   Status of network devices (up or down)
    -   Connectivity status between devices (connected or disconnected)
    -   Traffic load on network links (measured in percentage or utilization)
3.  **Input Variables**:
    -   Arrival rate of packets (number of packets arriving per unit time)
    -   Service rate of devices (rate at which devices can process packets)
    -   Bandwidth of network links (capacity of links to carry data)
    -   Transmission time for packets (time taken to transmit packets from source to destination)
4.  **Resources**:
    -   Bandwidth availability between different network segments
    -   Number of servers available for specific services (Web, FTP, DHCP, etc.)
    -   Processing capacity of routers and switches
    -   Memory and storage capacity of servers
5.  **Activities and Events**:
    -   Packet delay (time taken for a packet to traverse the network)
    -   Queuing delay (time spent by packets in queues waiting for transmission)
    -   Packet arrival events (triggers when packets arrive at a device)
    -   Packet transmission events (triggers when packets are transmitted from one device to another)
    -   Network congestion events (triggers when network load exceeds capacity)

**3. Traffic Analysis and Simulation Results**

**Scenario 1: A wireless user from first facility of second branch wants to read emails and browse Web.**

**![](media/3620960d66e8a0a734986b298e332b5b.png)**

Figure 1 reading email

![](media/064d03f49b7d3848eab4390e7611fa0c.png)

**![](media/496ccdc9f22baf43562bc94fb667e6bd.png)**

Figure 2 web browsing

![](media/f2bdfb6e0727e0c70081a8cc92d774d0.png)

**2. A computer engineer from second facility of second branch developed a web application and wants to send his/her code files to FTP server in the third facility of first branch.**

**![](media/2a14a519bc25dc1eeb08630c6d0ea49d.png)**

Figure 3 ftp server

![](media/5683448832b4fd4d8b5f4d10d3eecff5.png)

**3. Two users from second facility of first branch want to talk via VoIP.**

**![](media/e080dcdbc31b8f343908b8d345d242f0.png)**

Figure 4 VOIP

![](media/9b4bdc726dc1273590e430ec1ba6d33d.png)

**4. A user in the second facility of the first branch wants to send an email message to his friend in the second facility of second branch.**

**The second branch second facility doesn’t have access to mail server. Then the simulation will fail.**

![](media/816e982ccc59b2f3534bf1f348260171.jpeg)

**5. A user from first facility of second branch pings Web server of second facility of first branch.**

**![](media/753a56f2244f3419b498aa342d2bf2a5.png)**

Figure 6 second facility first branch pc pings the web server

**![](media/a6ead534d7d2b40518a944e33f710b63.png)**

Figure 7 first facility of second branch ping the second facility first branch pc

**![](media/1f05f7136acbf0be31ca1c25abbb1475.png)**

**![](media/20600c031af88e65b2b366ef83b9b611.png)**

**6. A laptop user from first facility of first branch office wants to send email to her friend in the first facility of second branch office.**

**![](media/1051e8121a3d4129ea7fc2739ae05097.png)**

**![](media/22b3bc3bfd137bb822607f0f84f31409.png)**

**![](media/60f8280c58b0ce74324d398da2140111.png)**

**7. A smartphone user from third facility of second branch office wants to use ssh to connect to a Web server in the third facility of first branch office**

**![](media/248ea04cf5a44c3b57f9c569b7512721.png)**

**![](media/8e7acdab0a8d198917543d20c83e88a9.png)**

**![](media/ad1634d2b8912249ac14288b7a4b400d.png)**

**![](media/ccd638dc16c8fb560956eec0cad46c75.png)![](media/159c3db55183b0a2eae2870538706dc6.png)**

**![](media/4378cd2342855af3ae7ecfefc760d1a6.png)**

**![](media/54f3f52d5e5237a75b52739d9547b72c.png)**

**![](media/098860f98a3fc6d37e50abe9020cf8a3.png)**

**![](media/1493853841d774fcaff485a10eb98924.png)**

**![](media/cd18e6afa2ead748ce41212db8235f5e.png)**

**![](media/623110113bcbe27e57b0a6f72dbf8c29.png)**

**![](media/50dc4404dff7f40eb5d3005b178e6db4.png)**

**![](media/fe7ce7a5bef0a39dff69cfc51b9ef530.png)**

**8. Sending notes to other user in voip conference.**

**![](media/22aa2bf174bb79dc42cba9a4898aaa35.png)**

**![](media/8b840786a439c4cbf400c7e8153016df.png)**

**9. Ping operation with traffic generator application**

**![](media/891c4bdf4b95f1f8ea446970d0f7cf9b.png)**

**![](media/a8832011d3788bf95cd7e7f4060eb340.png)**

**4. Conclusion**

In conclusion, the successful planning and design of a Metropolitan Area Network (MAN) using Cisco Packet Tracer software. Throughout this project, we addressed the diverse needs of two distinct branch offices located within a city, ensuring seamless connectivity and efficient communication between users and resources across both locations. Each branch office was tailored to accommodate the specific requirements of its facilities and users, ranging from basic web browsing and email services to more complex functionalities such as VoIP conferencing and file transfers. The deployment of routers, switches, servers, and end devices was optimized to achieve maximum performance while maintaining a balance between hardware costs and system requirements. Furthermore, the simulation scenarios provided valuable insights into the functionality and reliability of the network infrastructure we designed. Through thorough testing and analysis, we were able to verify the effectiveness of our configurations and identify areas for potential optimization or improvement.

**5. References**

**[1]S. Kimanzi, “Secure Shell (SSH) configuration on a switch and router in Packet Tracer,” Computer Networking Highlights, Jul. 05, 2018.** [**https://computernetworking747640215.wordpress.com/2018/07/05/secure-shell-ssh-configuration-on-a-switch-and-router-in-packet-tracer/**](https://computernetworking747640215.wordpress.com/2018/07/05/secure-shell-ssh-configuration-on-a-switch-and-router-in-packet-tracer/)

**[2]S. Kimanzi, “RIP configuration in Packet Tracer,” Computer Networking Tips, Jul. 05, 2018.** [**https://computernetworking747640215.wordpress.com/2018/07/05/rip-configuration-in-packet-tracer/**](https://computernetworking747640215.wordpress.com/2018/07/05/rip-configuration-in-packet-tracer/)

**[3]G. Wright, “What is a metropolitan area network?,” SearchNetworking, Feb. 2021.** [**https://www.techtarget.com/searchnetworking/definition/metropolitan-area-network-MAN**](https://www.techtarget.com/searchnetworking/definition/metropolitan-area-network-MAN)

**[4]Cisco Networking Academy, “Download The Packet Tracer Simulator Tool & Find Courses \| Networking Academy,” Netacad.com, 2019.** [**https://www.netacad.com/courses/packet-tracer**](https://www.netacad.com/courses/packet-tracer)

**[5]“How to Configure DHCP Server on Cisco Routers,” ComputerNetworkingNotes.** [**https://www.computernetworkingnotes.com/ccna-study-guide/how-to-configure-dhcp-server-on-cisco-routers.html**](https://www.computernetworkingnotes.com/ccna-study-guide/how-to-configure-dhcp-server-on-cisco-routers.html)

**[6]PacketTracerNetwork, “Packet Tracer 8.1.1 tutorial - IP telephony advanced configuration,” Packet Tracer Network, Feb. 22, 2022.** [**https://www.packettracernetwork.com/tutorials/voipadvancedconfiguration.html**](https://www.packettracernetwork.com/tutorials/voipadvancedconfiguration.html)

**[7]“Configure web server in packet tracer to enable internet,” Packet tracer labs, Jan. 15, 2023.** [**https://www.packettracerlab.com/configure-web-server-in-cisco-packet-tracer/**](https://www.packettracerlab.com/configure-web-server-in-cisco-packet-tracer/)

**6. Appendices**

**![](media/24aed2b0a0b5badaa36101c5d2d72560.png)**

Figure 8 First Branch

**![](media/c8764ff9c866d85b36b52d17aaf66273.png)**

**![](media/9223e60f8b48c2acc8feb1ad6d5f1bca.png)**

**![](media/5fd613080260eef71f2b5337f88c0451.png)**

**![](media/a46c19be30ae912fb5a4902fa0f2e2a6.png)**

**![](media/3fcf73bfb17446875be1acc2948f3c0f.png)**

Figure 9 Second Branch

![](media/11563d6e65486ffbb0125352fd318c8f.png)

![](media/fcffc9669da42de62dc647c50355fca8.png)

![](media/3542dee0cfac2f9f1d0befdc825d8803.png)

![](media/0a74c57ca0fd84721f152f08c60a6f88.png)
