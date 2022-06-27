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
  * The submask of _Interface A1_ is `255.255.255.224`
  * _Interface B1_ is on the same network as _Interface A1_, because of this both devices need to have the same submask
  * The IP of Interface B1 is `192.168.62.222`, then all devices that need to communicate with _Interface B1_ through the same network need to have an IP ranging from `192.168.62.192`to `192.168.62.221`
  * The submask on the network that connects _Interface C1_ and _Interface D1_ is configurated, then everything that is asked to do is to set up the IP from both devices
  * Because the submask of the network is `255.255.255.252` there are two availables hosts per sub-net
</details>

<details>
  <summary>Exercise 03</summary>
  
  ![Problem](img_solution/Ex_03_unsolved.png)<br>
  
  Solution
  ![Solution](img_solution/Ex_03_solved.png)<br>
* The IP of _Interface A1_ is `104.198.101.125` and the sub mask of _Interface C1_ is `255.255.255.128`
* IP range for devices of this network is `104.198.101.1` to `104.198.101.126`
</details>
