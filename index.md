---
layout: index
title: 'Avatar Robots'
subtitle: 'Although telepresence assistive robots have made significant progress, they still lack the sense of realism and physical presence of the remote operator. This results in a lack of trust and adoption of such robots. In this paper, we introduce an Avatar Robot System which is a mixed real/virtual robotic system that physically interacts with a person in proximity of the robot. The robot structure is overlaid with the 3D model of the remote caregiver and visualized through Augmented Reality (AR). In this way, the person receives haptic feedback as the robot touches him/her. We further present an Optimal Non-Iterative Alignment solver that solves for the optimally aligned pose of 3D Human model to the robot (shoulder to the wrist non-iteratively). The proposed alignment solver is stateless, achieves optimal alignment and faster than the baseline solvers (demonstrated in our evaluations). We also propose an evaluation framework that quantifies the alignment quality of the solvers through multifaceted metrics. We show that our solver can consistently produce poses with similar or superior alignments as IK-based baselines without their potential drawbacks.'
---

<tr>
        <td>
            <center>
                <img src="/images/overall-architecture.drawio-3.jpg" style="width:50%;"/>
            </center>
        </td>
</tr>
    
## Poses
We propose the first general purpose end-to-end robotic system that provides the integration of our solver along with other baseline solvers (adapted) into augmented reality (AR) device and robot; Our system achieves efficient and reactive real-time pose synchronization, alignment computation, and overlay projection. See list of <a href="{{ item.url | relative_url }}/poses">all poses</a>.

## Emulated Therapy Session
In the emulated therapy, 'shoulder flexion with elbow extension therapy', we program the robot to follow a trajectory that guides the user's forearm to rotate around his elbow joint. See the system in action for the <a href="{{ item.url | relative_url }}/sessions">session</a>.


## Results

<!--#### Evaluating solvers on a set of static poses-->
<br/><br/>
<tr>
        <td>
            <center>
                <img src="/images/poses.jpg" style="width:30%;"/>
            </center>
        </td>
</tr>
<span style="font-size:medium;">Violin plots of performance metrics of solvers evaluated from 12 poses. The minimums, maximums and medians are marked with black bars. We see that ONIA is the fastest of all, achieves the best overlay ratio, and scales the upper arm most conservatively and most consistently. See <a href="{{ item.url | relative_url }}/poses">results for all poses</a>.</span>

<!--#### Evaluating the solvers through an emulated physical therapy session-->

<br/><br/>
<tr>
        <td>
            <center>
                <img src="/images/metrics.jpg" style="width:30%;"/>
            </center>
        </td>
</tr>
<span style="font-size:medium;">Metrics of all solvers evaluated throughout the therapy session. ONIA has the highest overlay ratio in average and runs the fastest. It scales the upper arm similar to FABRIK but scales the forearm more aggressively. FABRIK exhibits poor alignment metrics for initially, and we find Jacobian to be lagging behind robot movements even with the smallest damping necessary to keep it stable. See the results for the session <a href="{{ item.url | relative_url }}/sessions">here</a>.</span>

## Code
Refer to the [Avatar Robots System repository](https://github.com/Avatar-Robots/avatar-system) for the codebase of the all the alignemnt solvers and the system.


