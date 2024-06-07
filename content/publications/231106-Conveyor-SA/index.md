+++
author = "Seongwook Kim"
title = "Conveyor: Towards Asynchronous Dataflow in Systolic Array to Exploit Unstructured Sparsity"
date = "2023-11-06"
description = "Systolic array (SA) architecture efficiently offers parallel computation using a simple data movement across processing elements. However, their rigid structure and synchronous dataflow limit flexibility in handling sparse computations, resulting in underutilized resources and suboptimal performance. In this paper, we propose Conveyor-SA, a novel SA-based accelerator architecture leveraging asynchronous dataflow for unstructured sparsity exploitation. Conveyor-SA introduces three core mechanisms: Chunk Propagation for parallel data processing, PE Grouping to accelerate efficiently both sparse and dense CNN models, and Conveyor Queue for load imbalance mitigation. Our experimental results demonstrate that Conveyor-SA achieves an average speedup of 1.68x over the competitors while processing conventional CNN models. In addition, Conveyor-SA delivers 1.42x speedup over state-of-the-art sparse SA architecture while remarkably reducing the chip area requirement by 19.5%."
tags = [
    "emoji",
]
+++