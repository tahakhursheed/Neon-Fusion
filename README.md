# Main Inspiration
The main inspiration behind this piece is the lack of artwork that intersects traditional arab pieces of art and futuristic pieces of art. Futuristic pieces tend to be digitally inspired and traditional pieces are based heavily on culture and history of arab civilization. We sought to find a middle ground by integrating the past and present to make what we consider would be the future of art.

# How it was built

### **Neon Fusion** can be divided into two work streams and two seperate art pieces:

#### * **AI Stream**: Arabic symbols and patterns were fused with english alphabets using multiple AI algorithms
 1. *Dataset* : Created a curated dataset of english letters and arabic symbols
 2. *Fusion* : Selected english letter ('R') and an arabic symbol (saudi sword) which where fed into FCGAN creating a new fusion alphabet
 3. *Styling* : Fed Arabic patterns and output from previous step into a neural style transfer (NST) to get the desired digital artwork
 
#### * **Drone Stream**: The digital artwork was converted into a drone trajectory, a drone attached to a light source flew autonomously creating a 3D light painting
 1. *Light Painting* : Conducted initial testing with hand movements of light source to create artwork
 2. *Drone Trajectory* : Attempted to adapt drone scripts that take bitmap images from the AI Stream as input and give drone trajectory as output
 3. *Autonomous Drone Flight* : Fed coordinates to drone attached to a light source and autonomously fly it to create light painting on the sky
 
 # Supporting Pictures 
 
 
