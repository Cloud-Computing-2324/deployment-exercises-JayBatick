#Uptime
Opdracht 2 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.

helm repo add uptime-kuma https://helm.irsigler.cloud

helm upgrade uptime-kuma uptime-kuma/uptime-kuma --install --namespace wikijs -f "C:\Users\jeanb\deployment-exercises-JayBatick\02_UPTIME/values.yaml"