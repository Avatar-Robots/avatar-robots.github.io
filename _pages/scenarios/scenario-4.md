---
permalink: /scenarios/scenario-4/
title: Scenario 4
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
    <td>Cooperate on Fire</td>
    <td>None</td>
    <td>Tree</td>
    <td>Saw</td>
    <td>Cooperate on Tree</td>
    <td>Coercion on Saw</td>
    <td>Fire</td>
    <td>Tree</td>
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
                <video width="400" height="400" controls><source src="/scenario-videos/E4-level0.mp4" type="video/mp4"></video>
            </center>
        </td>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E4-level1.mp4" type="video/mp4"></video>
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
                <video width="400" height="400" controls><source src="/scenario-videos/E4-level2.mp4" type="video/mp4"></video>
            </center>
        </td>
        <td>
            <center>
                <video width="400" height="400" controls><source src="/scenario-videos/E4-level3.mp4" type="video/mp4"></video>
            </center>
        </td>
    </tr>
</table>
