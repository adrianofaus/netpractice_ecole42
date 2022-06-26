![netpracticee](https://user-images.githubusercontent.com/63206471/175390369-33add942-d657-4684-add8-da89ea61b7ba.png)

# Net Practice

* [Introduction](#introduction)
* [Notion](#notion-link)
* [The Project](#the-project)


## Skills that I have improved
* Network & system administration
* Rigor

## Introduction
* This project is a general practical exercise that let me discover networking.

## The project
In order to succeed in doing this project I had to master the following:
* TCP/IP Addressing
* Subnet mask
* IP Classes
* Routing

<details>
  <summary>Exercise 01</summary>
  
  ![Problem](img_solution/Ex_01_unsolved.png)<br>
  
  Solution
  ![Solution](img_solution/Ex_01_solved.png)<br>
  * `104.95.23` is the first network IP
  * _Client A_ and _Client B_ are on the same network so they need to have the same network IP
  * The host interval for the mask `255.255.255.0` is `1 to 254`. The host part of _Client A_  IP need to be on this interval
  * Repeat the logic for _Client D_
</details>

<details>
  <summary>Exercise 02</summary>
  
  ![Problem](img_solution/Ex_02_unsolved.png)<br>
  
  Solution
  ![Solution](img_solution/Ex_02_solved.png)<br>
  * The submask of Interface A1 is `255.255.255.224`
  * Interface B1 is on the same network as Interface A1, because of this both need to have the same submask
  * The IP of Interface B1 is `192.168.62.222`, then all devices that need to communicate with Interface B1 need to have an IP ranging from `192.168.62.192`to            `192.168.62.221`
  * The submask on the network that connects Interface C1 and Interface D is already configurated, then everything that is asked to do is to set up the IP of both devices
  * Because the submask of the network is `255.255.255.252` there are two availables hosts per sub-net
</details>
