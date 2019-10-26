# Challenge

## Motivation
During a Mars expedition, five astronauts went missing and are not able to communicate anymore. As a rescue team you just landed on Mars. Your task is to analyze the unknown terrain, navigate thru it and search for as many astronauts as possible before the air runs out.

## Challenge Criteria

### Points
| Criteria        | Description      | Points |
| --------------- | ---------------- | -----: |
| Driving | The rover is able to drive to a point on Mars. | 10 |
| Mapping | A visual representation of the map is created that represents the area with the obstacles. | 30 |
| Pathfinding | An efficient algorithm is used to find a way thru the area. | 1-5 (depending on the solution) |
| Astronaut Detection | A yellow astronaut can be detected with the camera. | 3 (per astronaut detected) |
| Astronaut Pick-Up | The rover drives to the astronaut (max. 30cm away from center of the rover) and faces it with the front. Multiple astronauts can be carried at the same time. | 5 (per pick-up) |
| Astronaut Rescuing | A picked up astronaut is brought back to the starting point. | 5 (per astronaut returned) |

### Malus Points
| Criteria        | Description     | Points  |
| --------------- | --------------- | ------- |
| Driving | The rover drives into an obstacle. | -2 (per collision) |
| Driving | The rover leaves the area. | -2 (per case) |
| Mapping | Wrongly shown or not shown obstacle on the map. | -3 (per wrong sqm) |

### Bonus Points
| Criteria        | Description     | Points  |
| --------------- | --------------- | ------- |
| Astronaut Detection | The astronauts are detected by color and shape. | 5 (one-time) |
| Dynamic Obstacles | Obstacles can be dynamically placed and removed from the area. | 15 (one-time) |
