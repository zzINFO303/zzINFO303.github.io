---
title: Code Generation Error Taxonomy
tags: [LLMs, Code Generation, Research, Towards Understanding the Characteristics of Code Generation Errors Made by Large Language Models]
style: fill
color: info
image: assets/pngs/icse-2025-logo.png
description: A research project exploring the characteristics of code generation errors made by LLMs. The website provides interactive visualizations from our empirical analysis.
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---

# Towards Understanding the Characteristics of Code Generation Errors Made by Large Language Models

This [research](https://www.arxiv.org/abs/2406.08731) investigates the nature of code generation errors made by Large Language Models (LLMs). We conducted a comprehensive empirical study across six representative LLMs using the HumanEval dataset.

Through **open coding** and **thematic analysis**, we distilled a rich taxonomy of error types, covering both semantic and syntactic dimensions. Our findings reveal that LLMs frequently make **multi-line, non-trivial errors**, often with subtle root causes and distributed error locations, which pose challenges for debugging and comprehension.

We also analyzed the correlation between error patterns and task complexity/test pass rates. To support transparent research and encourage future exploration, we created an [**interactive website**](https://llm-code-errors.cs.purdue.edu/) that visualizes these patterns and errors.

<br>

<div class="left">
{% include elements/button.html link="https://www.arxiv.org/abs/2406.08731" text="Paper" %}
</div>

<div class="right">
{% include elements/button.html link="https://llm-code-errors.cs.purdue.edu/" text="Data" %}
</div>
