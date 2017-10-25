---
title: Hello, World!
layout: default
---

<div id="Objectives" class="section">
    <h1>Objectives</h1>

    <p>The goal of this project is to successfully train a both a simulated and physical inverted pendulum to balance in an upright position for an extended period of time. The training of the pendulum will be done via the tweaking of a neural network using SARSA deep reinforcement learning, which will then be deployed for physical testbed involving a linear channel slider and a servo as the actuators and a BeagleBone Black as the primary controller.</p>

    <p>Additionally, should time permit, the system will be trained to have the added ability to maintain its state in a manner robust to attacks on the physical system.</p>

    <p>Deliverables for the project include the code used to run train and run simulations (primarily done in MATLAB) as well as the code deployed to the target embedded device used to control the testbed actuators (most likely done in Python). Photos, videos, and reports detailing intermediate progress and the final state of the project will be produced throughout the development cycle.</p>

    <p>Should the progress and findings of the project prove substantial, a final objective would be to use the inoformation as the basis of, or a signficant contribution to, a culimnating paper detailing the findings.</p>
</div>
<div id="People" class="section">
    <h1>People</h1>

    <strong>Arjun Lakshmipathy</strong>
    <p>A photo would be good</p>
    <p>Arjun is a first year M.S. student in the Computer Science Department. His research interests include modeling, control, and actuation proceses of both simulated and physical intelligent robotic systems. Prior embedded systems work includes research and development of lightweight game streaming devices with remote control capability.</p>
    <br>
    <br>
    <strong>Benjamin Wood</strong>
    <p>A photo would be good</p>
    <p>Some blurb about Ben</p>
</div>
<div id="Progress" class="section">
    <h1>Progress</h1>
    <p>This project can be roughly divided into N phases</p>
    <ul>
        <li>Phase 1: Model the motion of the pendulum in the simulation environment</li>
        <li>Phase 2: Replace the standard physical motion modeling with a neural network and train using SARSA deep reinforcement learning</li>
        <li>Phase 3: Train the network while running simulations to generate a network that produces desired behavior (in this case balancing the pendulum) for at least a specified period of time</li>
        <li>Phase 4: Set up the physical testbed and generate PWMs from the embedded controller to demonstrate working condition</li>
        <li>Phase 5: Translate simulation code and trained neural network to embedded controller</li>
        <li>Phase 6: Carry out physical testing and record / report results</li>
        <li>Phase 7: Refine and retest using findings from Phase 6</li>
        <li>Phase 8: Introduce attacks into simulation environment and refine network to be robust to them</li>
        <li>Phase 9: Repeat Phases 3, 5, 6, and 7 with new network</li>
    </ul>
    <p>Due to prior work done by NESL, we are currently in Phase 3 of the project and are expecting to enter Phase 4 soon.</p>
</div>
<div id="PhotosVideos" class="section">
    <h1>Photos and Videos</h1>
    <p>(To be posted throughout the quarter)</p>
</div>
<div id="Literature" class="section">
    <h1>Prior Literature</h1>
    <p>(Include all papers used and referenced with links to all of them)</p>
</div>



