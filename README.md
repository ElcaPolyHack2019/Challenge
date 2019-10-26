# Challenge

## Motivation
During a Mars expedition, some astronauts went missing and are not able to communicate anymore. As a rescue team just landed on Mars, your task is to analyze the unknown terrain, navigate thru it and search for as many astronauts as possible before the energy goes out.

## General Requirements

## Challenge Criteria

### Points
| Criteria        | Description      | Points |
| --------------- | ---------------- | -----: |
| Driving | The rover is able to drive to a point on Mars. | 10 |
| Mapping | A visual map is created that represents the area with the obstacles. | 30 |
| Pathfinding | An efficient algorithm is used to find a way thru the area. | 5 |
| Astronaut Detection | A yellow astronaut can be detected with the camera. | 3 |
| Astronaut Pick-Up | The rover drives to the astronaut (max 30cm away from center of the rover) and faces it with the front. | 5 |
| Astronaut Rescuing | A picked up astronaut is brought to the starting point. | 8 |

### Malus Points
| Criteria        | Description     | Points  |
| --------------- | --------------- | ------- |
| Driving | The rover drives into an obstacle. | -2 |
| Driving | The rover leaves the area. | -2 |
| Mapping | Wrongly shown or not shown obstacle on the map. | -3 (per wrong sqm) |

### Bonus Points
| Criteria        | Description     | Points  |
| --------------- | --------------- | ------- |
| Astronaut Detection | The astronauts are detected by color and shape. | 5 (one-time) |
| Dynamic Obstacles | Obstacles can be dynamically placed and removed from the area. | 10 (one-time) |

Efficiency
