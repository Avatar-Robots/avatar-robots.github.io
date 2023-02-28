---
permalink: /scenarios/scenario-77/
title: Scenario 77
subtitle: ''    
---
Red and Yellow robot are initialized with the following goals. Using Linear Social MDP model, at different levels of reasoning, each robot recursively estimates the goals of another by observing their actions.

<table style="text-align:center">
    <thead>
        <tr>
            <th colspan="4" style="text-align:center; background: orange">Yellow Robot</th>
            <th colspan="4" style="text-align:center; background: red">Red Robot</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><b>Social Goal 1</b></td>
            <td><b>Social Goal 2</b></td>
            <td><b>Physical Goal 1</b></td>
            <td><b>Physical Goal 2</b></td>
            <td><b>Social Goal 1</b></td>
            <td><b>Social Goal 2</b></td>
            <td><b>Physical Goal 1</b></td>
            <td><b>Physical Goal 2</b></td>
        </tr>

<tr>
    <td>Compete on Tree</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Exchange on Saw</td>
    <td>Tree</td>
    <td>Fire</td>
</tr>
</tbody></table>

--- 
## Interactions


<table cellpadding="1">
    <tr>
        <td style="width:50%; text-align:center" id="level-0">
            <h6 style="text-align:center">Level 0</h6>
        </td>
        <td style="width:50%; text-align:center" id="level-1">
            <h6 style="text-align:center">Level 1</h6>
        </td>
    </tr>

    <tr>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E77-level0.mp4" type="video/mp4"></video>
            </center>
        </td>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E77-level1.mp4" type="video/mp4"></video>
            </center>
        </td>
    </tr>

    <td style="width:50%; text-align:center" id="level-2">
            <h6 style="text-align:center">Level 2</h6>
        </td>
        <td style="width:50%; text-align:center" id="level-3">
            <h6 style="text-align:center">Level 3</h6>
        </td>

    <tr>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E77-level2.mp4" type="video/mp4"></video>
            </center>
        </td>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E77-level3.mp4" type="video/mp4"></video>
            </center>
        </td>
    </tr>
</table>

---

## Results  
<p><span><img style="display: inline-block" src="/images/yellow-robot.png" width="25px" height="25px"/></span> (Level 3) estimating <span><img style="display: inline-block" src="/images/red-robot.png" width="25px" height="25px"/></span> (Level 2) 
    <span><img style="display: inline-block" src="/images/sg-legend.png" style="float:right" width="120px" height="120px"/></span>
</p>
<br>
&nbsp;

<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;"></td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Tree
        </td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Fire
        </td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Saw
        </td>
    </tr>

    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l3-yellow-tree.jpg"> 
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l3-yellow-fire.jpg">  
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l3-yellow-saw.jpg">  
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Linear Social MDP</td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l3-yellow-tree.jpg"> 
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l3-yellow-fire.jpg">  
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l3-yellow-saw.jpg">  
        </td>
    </tr>
</table>


<p><span><img style="display: inline-block" src="/images/yellow-robot.png" width="25px" height="25px"/></span> (Level 2) estimating <span><img style="display: inline-block" src="/images/red-robot.png" width="25px" height="25px"/></span> (Level 1) 
    <span><img style="display: inline-block" src="/images/sg-legend.png" style="float:right" width="120px" height="120px"/></span>
</p>
<br>
&nbsp;
<table cellpadding="1">
    <tr>
        <td style="width:20%; text-align:center; font-weight: bold; font-size: large;"></td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Tree
        </td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Fire
        </td>
        <td style="width:25%; text-align:center; font-weight: bold; font-size: large;">
            Saw
        </td>
    </tr>

    <tr>
        <td style="text-align:center; font-size: large;">Human</td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l2-yellow-tree.jpg"> 
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l2-yellow-fire.jpg">  
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/human-l2-yellow-saw.jpg">  
        </td>
    </tr>
    <tr>
        <td style="text-align:center; font-size: large;">Linear Social MDP</td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l2-yellow-tree.jpg"> 
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l2-yellow-fire.jpg">  
        </td>
        <td>
            <img src="/images/results/linear-social-mdp-results/smdp-combined-l2-yellow-saw.jpg">  
        </td>
    </tr>
</table>
