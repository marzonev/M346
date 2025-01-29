# KN07

## A) Datenbank im PAAS Modell (20%)

![mysqlworkbenchquery](media/mysqlworkbenchquery.png)

Die Wartung, Sicherstellung der Verfügbarkeit, und das Skalieren der Datenbank wird von den Anbietern übernommen.

Kosten für Mitarbeiter die sich um die Server kümmern ist wahrscheinlich höher als die Kosten für eine PAAS oder SAAS Datenbank.

## B) PAAS Applikation erstellen (60%)

![subnets](image.png)

Bei den Subnets habe ich zwei genommen, da ein Load Balancer verlangt, dass man mindestens zwei Subnets verwendet.

Ich habe auch eine Public IP hinzugefügt, falls ich direkt etwas auf der Instanz Troubleshooten will.

![Securitygroup](media/Securitygroup.png)

Als Securitygroup habe ich einfach eine ausgewählt, die HTTP (Port 80) durchlässt.

![auto-scaling](media/auto-scaling.png)

Auto Scalling habe ich einfach 2 minimum und 4 maximum, da dies genügt für einen Webserver.

## B) Erstellte Ressourcen/Objekte und CloudFormation (20%)

![securitygroup2](media/securitygroup2.png)

Es hat eine zusätzliche Security Group erstellt mit den selben Berechtigungen wie die welche ich ausgewählt habe.

![instances](media/instances.png)

Die zwei minimum Instances wurden auch erstellt.

![load-balancer-created](media/load-balancer-created.png)

![target-group](media/target-group.png)

Load-Balancer und Target Group wurden auch erstellt.

![auto-scaling-created](media/auto-scaling-created.png)

![.](media/easteregg.png)
