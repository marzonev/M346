# KN 05

## Erklärung

### VPC

VPC ist ein virtuelles Netzwerk. Dort kann man Sachen wie Subnetze, public IPs, private IPs und static IPs definieren.

### Unterschied Public IP und Private IP

Die Public IP ist die welche von anderen Netzwerken aus erreicht werden kann. Die Private IP ist hinter dem Gateway und kann nur vom internen Netzwerk aus erreicht werden.

### Static IP

Eine statische IP wird **nicht** per DHCP zugewissen uns ist permanent

## Subnetze und IPs

![Subnetze](media/Subnetze.png)

IP-DB: 172.31.96.110

IP-Web: 172.31.96.120

## Sicherheitsgruppen

![Securitygroup-list](media/Securitygroup-list.png)

![Securitygroup-Webserver](media/Securitygroup-Webserver.png)

![Securitygroup-DBserver](media/Securitygroup-DBserver.png)

## Öffentliche, statische IP

![Static-IP](media/Static-IP.png)

## Instanzen erstellen

![Instances](media/Instances.png)

## Webseiten

![indexhtml](media/indexhtml.png)

![dbphp](media/dbphp.png)

![infophp](media/infophp.png)