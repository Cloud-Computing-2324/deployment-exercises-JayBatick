#Wiki.js

Opdracht 1 op Toledo. Als je gebruik maakt van Helm, zet je values-file in deze map, en je commando hieronder. Maak je gebruik van klassieke deployments, zet dan je bestanden in deze map.

PS C:\Users\jeanb> helm install wikijs requarks/wiki

PS C:\Users\jeanb> helm upgrade wikijs requarks/wiki -f "C:\Users\jeanb\deployment-exercises-JayBatick\01_WIKI/values.yaml"
