# BGP Exploration and Attack
Border Gateway Protocol (BGP) stands as the fundamental protocol underpinning internet routing, facilitating
the exchange of routing information between autonomous systems. Despite its critical role, BGP is prone to
vulnerabilities that can be exploited by malicious actors. These vulnerabilities encompass various attack vectors,
such as route hijacking, route leaks, and prefix hijacking. Given the pivotal nature of BGP in directing internet
traffic, any compromise in its integrity can result in significant disruptions, including service outages, data
interception, and redirection of traffic to unauthorized destinations. Thus, understanding the inherent risks
associated with BGP is paramount to safeguarding the stability and security of global internet infrastructure.

## Installation
(We have to have docker previously installed)

We start by cloning the repository

```bash
git clone https://github.com/StevenZ-G/BGP-Exploration-and-Attack.git
```
Now we go to the output folder within our project.

```bash
cd Projectsetup/output
```

The next step is to run the following commands

```bash
docker-compose build
docker-compose up
```

For the following configurations I am going to ask you to follow the steps present in the **BGP.jpg** document
