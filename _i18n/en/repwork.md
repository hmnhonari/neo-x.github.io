 
## Recent Work 

<div align="center">     <table align="center">        <tr>    <td width="33%">  <a href="https://sites.google.com/view/relmm"><h4>Autonomous real-world Reinforcement learning </h4><img width="100%" src="/assets/projects/ReLMM/complex_room_short.gif">
</a>
 </td> <td width="66%">  
We study how robots can autonomously learn skills that require a combination of navigation and grasping. While reinforcement learning in principle provides for automated robotic skill learning, in practice reinforcement learning in the real world is challenging and often requires extensive instrumentation and supervision. Our aim is to devise a robotic reinforcement learning system for learning navigation and manipulation together, in an autonomous way without human intervention, enabling continual learning under realistic assumptions. Our proposed system, ReLMM, can learn continuously on a real-world platform without any environment instrumentation, without human intervention, and without access to privileged information, such as maps, objects positions, or a global view of the environment. Our method employs a modularized policy with components for manipulation and navigation, where manipulation policy uncertainty drives exploration for the navigation controller, and the manipulation module provides rewards for navigation. We evaluate our method on a room cleanup task, where the robot must navigate to and pick up items scattered on the floor. After a grasp curriculum training phase, ReLMM can learn navigation and grasping together fully automatically, in around 40 hours of autonomous real-world training.
    </td>	</tr> </table></div>

<div align="center">     <table align="center">        <tr>    <td width="33%"> 
<a href="https://arxiv.org/abs/2104.11707">
<h4>General task learning by inferring rewards from example data</h4>
  <img width="100%" src="/assets/projects/DiscoRL/DisCoRL.png"> 
  </a>
  </td> <td width="66%"> 
 
Can we use reinforcement learning to learn general-purpose policies that can perform a wide range of different tasks, resulting in flexible and reusable skills? Contextual policies provide this capability in principle, but the representation of the context determines the degree of generalization and expressivity. Categorical contexts preclude generalization to entirely new tasks. Goal-conditioned policies may enable some generalization, but cannot capture all tasks that might be desired. In this paper, we propose goal distributions as a general and broadly applicable task representation suitable for contextual policies. Goal distributions are general in the sense that they can represent any state-based reward function when equipped with an appropriate distribution class, while the particular choice of distribution class allows us to trade off expressivity and learnability. We develop an off-policy algorithm called distribution-conditioned reinforcement learnin (DisCo) to efficiently learn these policies. We evaluate DisCo on a variety of robot manipulation tasks and find that it significantly outperforms prior methods on tasks that require generalization to new goal distributions. 
      </td>	</tr> </table></div>
   
<div align="center">     <table align="center">        <tr>    <td width="33%">   
<a href="https://sites.google.com/view/surpriseminimization">
<h4>Entropy minimization for emergent behaviour</h4>
<img width="100%" src="/assets/projects/SMiRL/robotsurprise_stacked.png">   <img width="100%" src="/assets/projects/SMiRL/miniGrid/minigrid-maze-random-count.gif"></a> </td> <td width="66%">
  
All living organisms carve out environmental niches within which they can maintain relative predictability amidst the ever-increasing entropy around them [schneider1994, friston2009]. Humans, for example, go to great lengths to shield themselves from surprise --- we band together in millions to build cities with homes, supplying water, food, gas, and electricity to control the deterioration of our bodies and living spaces amidst heat and cold, wind and storm. The need to discover and maintain such surprise-free equilibria has driven great resourcefulness and skill in organisms across very diverse natural habitats. Motivated by this, we ask: could the motive of preserving order amidst chaos guide the automatic acquisition of useful behaviors in artificial agents?      
      </td>	</tr> </table></div>


