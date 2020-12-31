# Restaurant-of-The-Future
Restaurant of the Future: <a href="https://www.facebook.com/marsiitr/videos/214354466310067/">Facebook</a> / <a href = "https://www.youtube.com/watch?v=dR3jsaHACXw">Youtube</a>
## The Waiter Robot
> Hello,
> I have Re-designed an improved version of the robotic waiter, capable of traversing in a restaurant <b>autonomously</b> with a 3WD.
> I applied a Lead-screw based mechanism to Al-extrusions to carry and transfer <b>payloads</b> up to 10kg to variable platforms.
> It has incorporated general curve navigation with the help of encoder coupled motor and PID controller for navigation.
---
## Mechanical Design
Design: ROTF Robot<br>
<img src="https://github.com/visvash/Restaurant-of-The-Future/blob/master/images/rotf5.JPG" height=300><br>
3 Wheel Omni Drive For Traversing<br>
<img src="https://github.com/visvash/Restaurant-of-The-Future/blob/master/images/rotf2.JPG" height=300><br>
Extrusion Rails Using Lead-Screw Mechanism<br>
<img src="https://github.com/visvash/Restaurant-of-The-Future/blob/master/images/rotf1.JPG" height=300><br>
# Electronics and control
## Process brief
<ol>
<li>Image Input from the overhead cameras on the restaurant are processed and path is planned using Image Processing and Dijkstra Algorithm.</li>
<li>Path send to Arduino using Wifi Module</li>
<li>Omni chasis based traversal on the given path of the bot to reach the desired table.</li>
<li>Chatbot starts interacting with the the customer and takes the order while recognising face and emotion of the customer.</li>
<li>After taking order, Bot traverses back to the initial position, waits for the order to be kept on its serving trays.</li>
<li>Bot traverses back to the customer on the same path and serves using a 3-tray serving mechanism</li>
</ol>
