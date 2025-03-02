# networking-fundamentals 
OSI MODEL
The Osi model [open system inter connection] model is a conceptual frame work used to understand and implement network protocol in seven layers.
SEVEN OSI MODELS LAYERS 
1. Physical Layer :Transmits raw binary data over the physical medium ,example the physical layer is the actual ethernet cable, radio waves and fiber optics.
2. Data Link Layer : It is responsible for node to node data transfer and error detection and correction, [defines the format of data on the network]example the ethernet protocol operates this layer its like a postal service that ensures letter get delivered to the right house on the street.
3. Network Layer : This layer hamdles IP addressing and routing decides which physical path the data will take, example it's like city road system that ensures vehicle goes to the right destination.
4. Transport Layer : Transmits data using transmission protocol including TCP and UDP and provides error-checking and recovery , example it's like a delivery service that gurantees package arrives without loss or damage.
5. Session Layer : This layer is responsible for establishing, managing and terminating connections between devices, example it's like a phone that makes a call [connection] maintains the call during conversation [manages] and ends it when you hang up[terminates].
6. Prensentation Later : This layer formats the data in a way the receiving application can understands it, it encrpyt and decrpyt data if needed ,example when a translator converts one language to another.
7. Application Layer : This layer provides network services directly to the end-user application , example it's like sending an email with a protocol like SMTP[simple mail transfer protocol].
   IP ADDRESSING CALCULATIONS
IP Address : A unique identifier eg[192.168.1.1]
Subnet Mask : Defines network and host portions eg[255.255.255].
Network Address : The first address in a subnet.
Broadcast address : The last address in a subnet.
Usable host : Total host in a subnet  minus 2[for network and  broadcast].
