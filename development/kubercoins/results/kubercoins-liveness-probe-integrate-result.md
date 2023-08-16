# Nombre de la asignación

Participantes
- ARCE MUÑOZ OCAMPO
- DANIEL EDUARDO AGUILAR ZÚÑIGA
- ELEU LOPEZ LOPEZ
- JOSE REYES ROMERO CERDA
- VICTOR EDUARDO ZAVALA RANGEL

Actividades
- Kubercoins-liveness-probe-integrate

Comandos
- kubectl create namespace yellow
- kns yellow
- cd ~
- git clone https://github.com/jpetazzo/kubercoins
- cd kubercoins
- vim rng-deployment.yaml
- kubectl apply -f .
- kubectl get svc rng
- kubectl get events -w
- httping 10.103.193.46
- kubectl get pods -w
- ab -c 10 -n 1000 http://10.103.193.46/1

Recursos externos
-

Artifactos
- Anexar artifactos al directorio de respuesta