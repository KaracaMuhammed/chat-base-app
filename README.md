# chat-base-app
om te starten doe:
<br>
```
minikube start
```
<br>
om wijzigingen door te geven doe en start de tunnel opnieuw op indien nodig voer dit wel uit in de juiste dir(..\chat-base-app)!:
<br>

```
kubectl apply -f kubernetes
```
<br>
als je niet naar het ip kan surfen dat je krijgt door minikube ip zet dan een tunnel op en surf naar localhost. 
Hier het commando om de tunnel op te zetten:
<br>

```
minikube tunnel
``` 
<br>
om in de minikube in te kunnen loggen doe dan in je terminal:
<br>

```
minikube ssh
```
<br>
en om af te sluiten als je images wilt pushen naar kubernetes doe dan:
<br>

```
minikube image load [lokale image naam]
```
<br>
belangerijk om ook dit commando uit te voeren:
<br>

```
minikube addons enable ingress
```
