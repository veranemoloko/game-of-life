## How It Works?
# Cells follow 3 rules:
- Survive with 2-3 neighbors
- Die from loneliness (<2) or overcrowding (>3)
- Reproduce if exactly 3 neighbors (dead cells come alive)
- Control: Adjust speed and starting patterns (random/file input)

## You need:
- git clone
- gcc game_of_life.c -o life && ./life
- enjoy