 
## Recent Work 

<div align="center">     <table align="center">        <tr>    <td width="33%">  <a href="https://sites.google.com/view/relmm"><h4>Autonomous real-world Reinforcement learning </h4><img width="100%" src="/assets/projects/ReLMM/complex_room_short.gif">
</a>
 </td> <td width="66%">  
We study how robots can autonomously learn skills that require a combination of navigation and grasping. While reinforcement learning in principle provides for automated robotic skill learning, in practice reinforcement learning in the real world is challenging and often requires extensive instrumentation and supervision. Our aim is to devise a robotic reinforcement learning system for learning navigation and manipulation together, in an autonomous way without human intervention, enabling continual learning under realistic assumptions. Our proposed system, ReLMM, can learn continuously on a real-world platform without any environment instrumentation, without human intervention, and without access to privileged information, such as maps, objects positions, or a global view of the environment. Our method employs a modularized policy with components for manipulation and navigation, where manipulation policy uncertainty drives exploration for the navigation controller, and the manipulation module provides rewards for navigation. We evaluate our method on a room cleanup task, where the robot must navigate to and pick up items scattered on the floor. After a grasp curriculum training phase, ReLMM can learn navigation and grasping together fully automatically, in around 40 hours of autonomous real-world training.
    </td>	</tr> </table></div>

<div align="center">     <table align="center">        <tr>    <td width="33%"> 
<a href="https://arxiv.org/abs/2104.11707">
<h4>Generalization across robots via inferring morphology</h4>
  <img width="100%" src="/assets/projects/anymorph/anymorph_prompt.gif"> 
  </a>
  </td> <td width="66%"> 
The prototypical approach to reinforcement learning involves training policies tailored to a particular agent from scratch for every new morphology. Recent work aims to eliminate the re-training of policies by investigating whether a morphology-agnostic policy, trained on a diverse set of agents with similar task objectives, can be transferred to new agents with unseen morphologies without re-training. This is a challenging problem that required previous approaches to use hand-designed descriptions of the new agent's morphology. Instead of hand-designing this description, we propose a data-driven method that learns a representation of morphology directly from the reinforcement learning objective. Ours is the first reinforcement learning algorithm that can train a policy to generalize to new agent morphologies without requiring a description of the agent's morphology in advance. We evaluate our approach on the standard benchmark for agent-agnostic control, and improve over the current state of the art in zero-shot generalization to new agents. Importantly, our method attains good performance without an explicit description of morphology. 
      </td>	</tr> </table></div>
   
<div align="center">     <table align="center">        <tr>    <td width="33%">   
<a href="https://sites.google.com/view/surpriseminimization">
<h4>Entropy minimization for emergent behaviour</h4>
<img width="100%" src="/assets/projects/SMiRL/robotsurprise_stacked.png">   <img width="100%" src="/assets/projects/SMiRL/miniGrid/minigrid-maze-random-count.gif"></a> </td> <td width="66%">
  
All living organisms carve out environmental niches within which they can maintain relative predictability amidst the ever-increasing entropy around them [schneider1994, friston2009]. Humans, for example, go to great lengths to shield themselves from surprise --- we band together in millions to build cities with homes, supplying water, food, gas, and electricity to control the deterioration of our bodies and living spaces amidst heat and cold, wind and storm. The need to discover and maintain such surprise-free equilibria has driven great resourcefulness and skill in organisms across very diverse natural habitats. Motivated by this, we ask: could the motive of preserving order amidst chaos guide the automatic acquisition of useful behaviors in artificial agents?      
      </td>	</tr> </table></div>


