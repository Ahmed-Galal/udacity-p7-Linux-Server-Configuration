# udacity-p7-Linux-Server-Configuration

## content
- [overview](#overview)
- [software installed](#software)

IP address, URL, summary of software installed, summary of configurations made, and a list of third-party resources used to completed this project.


## overview

- this project is a linux configuration to deploy web app via apache using cloud instance (cloud vm)(vps)
<table>
 <tr>
 <td>IP address</dt>
 <td>35.184.174.25</td>
 </tr>
  <tr>
 <td>ssh port</dt>
 <td>2200</td>
 </tr>
 <tr>
 <td>URL</dt>
 <td>http://mohymenu.tk</td>
 </tr>
 </table>
 
 ## software installed 
 
 
- apache2 

## step by step
- install ubunut 
- add user grader  ``` useradd grader ```
- give grader sudo with out password 
```
vim /etc/sudors.d/grader 
#insert in fill grader 
grader ALL=(ALL:ALL) NOPASSWD:ALL
```
- enable ssh connect for grader

```
from pc you want to ssh connect 
ssh-keygen
type ~/grader
will genrate two files

 
