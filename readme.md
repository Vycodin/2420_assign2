# 2420 Assignment 2

## Authors:
Hai Run(Kooby) Yin (A01186094)

## Incorporated Systems Include:
Windows WSL<br>
Digital Ocean Droplets<br>
Digital Ocean Firewall<br>
Digital Ocean Load Balancer

## Important Note
This guide operates under the assumption you already have WSL and your droplets set up.

### Step 1: Setting up Infrastructure
1.1 Under the networking tab select the create dropdown menu and select Load Balancer<br>
    Follow the instructions on digital ocean and add your droplets via **tags** or the names of your droplets<br>
    ![Alt text](img/createDropdown.png)
1.2 To create the Firewall, utilize the same dropdown menu as above and choose Firewall<br>
    Add an inbound rule for HTTP and change the Sources to your load balancer from the previous step<br>
    ![Alt text](img/inbound.png)
    ![Alt Text](img/loadbalancerfw.png)
    Add your droplets to your firewall and press the **Create Firewall** button.
    ![Alt text](img/adddptofw.png)
