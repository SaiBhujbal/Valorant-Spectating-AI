# Valorant-Spectating-AI

## Esports Spectating Automation using AI

Esports, with its 4.3 billion dollar global economy, has become a significant industry with a massive fanbase. Spectating in esports involves streaming players' Points of View (POVs) to the audience, but with multiple players in tournaments, manually streaming all of them is impractical. This project focuses on automating the spectating process using AI. This project was made using Roboflow.

### Factors Considered for POV Switching

1. **Euclidean Distance:**
   - Calculates the distance between enemy players.
   - Pairs with shorter distances are given higher priority.
   
2. **Edge Presence:**
   - Uses Euclidean distance along with the presence of edges between players on the map.
   - Edges represent walls and obstructions; no edges mean players can shoot through.
   - Switches POV with higher priority if there are no edges between enemy players.

### Clustering Effect

- Detects clustering events where a group of players gathers in the same area.
- Adjusts spectating behavior to switch players rapidly in clustered areas.
- Prevents missing thrilling combat situations, especially during rapid kills.



## HERE IS THE DEMO OF HOW THE AI DETECTING ALL THE POSITIONS AND PREDICTING THE PROBABLE FIGHT AND THE MAPPED KEYS ARE PRESSED: https://youtu.be/gsvYyvN-6Bw 



**Project is currently in review for patent hence the code is not shared** 



# This project is 1st Runner Up (Team OnlyTech) in Innverve 8, Biggest Student Driven Hackathon by **Army Insititue of Technology Pune**: https://x.com/IaSouthern/status/1756490525031739487/photo/4 
