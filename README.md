# AISnakeGame

# Firstly
This is not my original work, I created this by following a tutorial by Patrick Loeber. https://github.com/patrickloeber 
# Running
To run this project simply run the agent.py file, this AI is not too taxing on your computer since it uses CPU only. 
# Expectations
It takes around 90-100 games(10 minutes) for the AI to get a good consistent grasp on the movements and how to avoid itself.
If the snake seems to be just completely the same moves over and over (Spinning in a circle) then just be paitent. The random moves should kick it and throw it off course.
# Stack
Apart from stating the obvious and saying its written in Python, PyTorch is the brains behind the operation, using numpy for some tensor and matrix work, matplotlib for the fancy graph and IPython for displaying.
# Training/Learning style
The AI follows a fairly basic Reinforcement learning or Q learning in this case, this is following the Bellmans Equation for training. The reward system is fairly straightforward too, getting an apple is +10 and collisions are -10, every other action results in 0 like moving forward, left etc.
