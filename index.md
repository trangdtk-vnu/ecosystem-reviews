---
layout: default
title: Home
---

# 🌍 Ecosystem of Systematic Reviews  

<iframe src="/ecosystem-reviews/carbon_pricing_graph.html" width="800" height="700" style="border:none;"></iframe>

<!-- Tooltip Legend Icon -->
<div style="position: relative; display: inline-block; margin-left: 10px;">
    <span style="cursor: pointer; font-size: 16px; font-weight: bold;" onmouseover="showTooltip()" onmouseout="hideTooltip()">ℹ️</span>
    <div id="tooltip" style="
        display: none;
        position: absolute;
        left: 20px;
        bottom: 20px;
        background: white;
        color: black;
        border: 1px solid #ddd;
        padding: 8px;
        border-radius: 8px;
        box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
        font-size: 14px;
        width: 250px;
        z-index: 10;
    " onmouseover="keepTooltip()" onmouseout="hideTooltip()">
        <strong>Legend:</strong>
        <div style="display: flex; align-items: center; margin-top: 5px;">
            <div style="width: 15px; height: 15px; background-color: green; border-radius: 50%; margin-right: 8px;"></div>
            <span>Finished: Effectiveness - <a href="https://www.nature.com/articles/s41467-024-48512-w" target="_blank">Published Paper</a></span>
        </div>
        <div style="display: flex; align-items: center; margin-top: 5px;">
            <div style="width: 15px; height: 15px; background-color: yellow; border-radius: 50%; margin-right: 8px;"></div>
            <span>In Progress: Innovation, Carbon Intensity, Leakage, Labour Market  </span>
        </div>
        <div style="display: flex; align-items: center; margin-top: 5px;">
            <div style="width: 15px; height: 15px; background-color: white; border: 1px solid black; border-radius: 50%; margin-right: 8px;"></div>
            <span>Needs Review - Not Yet Started: Distribution, Public Perception, Competitiveness </span>
        </div>
    </div>
</div>

<script>
    function showTooltip() {
        document.getElementById("tooltip").style.display = "block";
    }

    function keepTooltip() {
        document.getElementById("tooltip").style.display = "block"; // Keep it open when hovering over the tooltip
    }

    function hideTooltip() {
        document.getElementById("tooltip").style.display = "none";
    }
</script>
