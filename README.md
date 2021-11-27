Salsabila Irbah - 05111942000007

Hilmy Thoriq - 05111942000012

Nadhif Bhagawanta - 05111942000029

# QUESTION
![image](https://user-images.githubusercontent.com/81474281/143683260-ad5a5be3-98f3-48b8-b46e-613b70f50224.png)

Create using GNS3 and Cisco Packet Tracer with different CLASSLESS calculation methods


# ANSWER
![Gambar topologi](https://user-images.githubusercontent.com/81411468/143681459-e6159b8a-ae50-44b4-bc5b-869e71664827.png)
Here we want to make VLSM and CIDR with this Topology with different classless calculation<br>

# VLSM
first we need to make the subnet <br>

After that we need to check the netmask of each subnet<br>
![Netmask](https://user-images.githubusercontent.com/81411468/143681557-2ec09f2c-ad77-4b2c-8301-172f20c96479.PNG)

Next we need to make the tree to define each subnet ip
![Pohon Benar](https://user-images.githubusercontent.com/81411468/143681577-72216919-7632-4e6e-b0cc-aad3994066e6.png)

lastly we can define each subnet information such as NID, Broadcast Address, and Netmask
![A1-A6](https://user-images.githubusercontent.com/81411468/143681659-124b175c-f437-43bd-b018-f13f9cc0116f.PNG)
![A7-A12](https://user-images.githubusercontent.com/81411468/143681664-0d20ae01-409e-4fe2-aff8-a787941227fa.PNG)
![A13-A15](https://user-images.githubusercontent.com/81411468/143681666-1e19bb4d-1cc3-4692-8eed-f9d32e26a28a.PNG)

And then we can do the Ip distribution
![Bagi IP VLSM](https://user-images.githubusercontent.com/81411468/143681689-46750e00-96c4-4e14-8883-ca0a45549698.png)

# CIDR
First we need to group each subnet like this <br>
![CIDR](https://user-images.githubusercontent.com/81411468/143684057-deb28029-2fc8-4684-a979-b43ad34e1a9b.png)
![CIDR 1](https://user-images.githubusercontent.com/81411468/143684067-9458d50c-a61b-4f31-a4dc-bd8da6c71fe8.png)
![CIDR 2](https://user-images.githubusercontent.com/81411468/143684069-f605ac08-1391-4e00-a192-5bcb88f8eefa.png)
![CIDR 3](https://user-images.githubusercontent.com/81411468/143684072-9d5bcdf9-94ba-4930-9fe5-c83328e0c707.png)
![CIDR 4](https://user-images.githubusercontent.com/81411468/143684084-b0b82016-be4a-4010-a8f6-e437cd4ba8fb.png)
![CIDR 5](https://user-images.githubusercontent.com/81411468/143684089-1f652b9e-aafe-415e-9ef2-d15e6fb79c67.png)
![CIDR 6](https://user-images.githubusercontent.com/81411468/143684090-4f744cd9-c497-44c2-80a8-cea07f25324f.png)
![CIDR 7](https://user-images.githubusercontent.com/81411468/143684080-4f36592b-c39b-49b7-bac6-e3b7bfe721e3.png)
<br>

Next We need to make Tree for the IP Distribution
![Pohon CIDR](https://user-images.githubusercontent.com/81411468/143684849-69fbdd15-af4e-47c7-8cdd-8e539c32c54f.png)


**Difficulties**
- Dont understand yet the testing for both VLSM and CIDR
- At first, pretty hard to learn the ip distribution
