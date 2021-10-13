# deepDrone
A tool that records drone footage from the famous game rainbow six siege and learns from the footage.

# Preface
deepDrone is a program that will record footage of drones in the game rainbow six siege automatically, and annotate certain routes from several positions (top-down, first person) in an attempt to learn common positions for defenders on certain maps.

Uses object detection and AI to detect, trigger events, and eventually be fully autonomous.

# To-Do
- Record Drone footage with python and openCV, stop after drone phase
- Auto-Detect Drone and record when using it
- Take pictures of all rainbow six siege maps from top-down perspective
- Annotate pathfinding routes for drones using data
- Detect defenders from drone footage (object detection)
- add Reinforcement learning mode where the AI learns to find operators by itself (openai playground possibly)
