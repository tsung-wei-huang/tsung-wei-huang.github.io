---
title: "TW's Research Group - Research"
layout: textlay
excerpt: "TW's Research Group -- Research"
sitemap: false
permalink: /research/
---

## Research

Our overarching goal is to create novel software systems to simplify the programming complexity
of heterogeneous computing resources. 
Our systems target performance-critical applications, 
such as computer-aided design, machine learning, and quantum computing.
We have released several open-source software projects 
(e.g., <a href="https://github.com/taskflow/taskflow">Taskflow</a>, <a hreff="https://github.com/opentimer/opentimer/">OpenTimer</a>)
that are being used by many industrial and academic projects.
Our research is framed by the following themes:

+ [Theme #1: Heterogeneous Programming Environments](#theme-1-heterogeneous-programming-environments)
+ [Theme #2: Electronic Design Automation](#theme-2-electronic-design-automation)
+ [Theme #3: Quantum Computing](#theme-3-quantum-computing)
+ [Theme #4: Machine Learning Systems](#theme-4-machine-learning-systems)

<hr>

### Theme 1: Heterogeneous Programming Environments

**Research Question**: *How can we make it easier for researchers and developers to write parallel and heterogeneous programs with high performance and simultaneous high productivity?*

<center><div style="max-width: 400px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_parallelism_3p.png"  class="rounded" style="max-width: 100%">
</div></center>


<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/theme_parallelism.png){: style="width: 450px; float: right; margin: 0px 0px"}-->

Modern scientific computing relies on a heterogeneous mix of computational patterns, domain algorithms, and specialized hardware to achieve key scientific milestones that go beyond traditional capabilities. However, programming these applications often requires complex expert-level tools and a deep understanding of parallel decomposition methodologies. A suitable software environment that can streamline the complexity of programming large parallel and heterogeneous systems is therefore very crucial to facilitate transformational scientific discoveries. **Our research investigates new programming environments to assist researchers and developers to tackle the implementation complexities of high-performance parallel and heterogeneous programs.**

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><a href="https://taskflow.github.io/"><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/taskflow_logo.png" style="width: 100%;"></a></p>
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4><a href="https://taskflow.github.io">Taskflow: A General-purpose Parallel and Heterogeneous Task Programming System</a></h4>
  <p>
  Taskflow helps C++ developers quickly write parallel and heterogeneous programs
  with high performance and simultaneous high productivity.
  </p>
  </div>
</div>

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><a href="https://taskflow.github.io/"><img src="{{ site.url }}{{ site.baseurl }}/images/respic/taro-logo.png" style="width: 100%;"></a></p>
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/dian-lun-lin/taro">Taro: Task Graph-based Asynchronous Programming System using C++ Coroutine</a></h4>
  <p>
  Taro is an asynchronous task graph programming system that allows you to write coroutines in a task graph while abstracting away complex coroutine management.
  </p>
  </div>
</div>

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/dtcraft_logo.png" style="width: 100%;"></p>
  </div>
  </div>

  <div class="col-md-10 col-sm-10">
  <h4><a href="https://tsung-wei-huang.github.io/DtCraft/">DtCraft: A Distributed Programming System using Data-parallel Streams</a></h4>
  <p>DtCraft helps developers streamline the building of high-performance distributed applications using data-parallel streams on a machine cluster.</p>
  </div>
</div>

<div class="row">
<div class="col-sm-6">
  <h4 class="badge badge-primary">Taskflow at CppCon</h4>
  <div class="embed-responsive embed-responsive-16by9"><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/MX15huP5DsM" allowfullscreen></iframe></div>
</div>
<div class="col-sm-6">
  <h4 class="badge badge-primary">cudaFlow at CppCon</h4>
  <div class="embed-responsive embed-responsive-16by9"><iframe class="embed-responsive-item" src="https://www.youtube.com/embed/-tIQbIhTAv8" allowfullscreen></iframe></div>
</div>
</div>

<hr>



### Theme 2: Electronic Design Automation

**Research Question**: *How can we leverage emerging heterogeneous parallelism to speed up electronic design automation (EDA) algorithms and achieve order-of-magnitude performance breakthrough?*

<center><div style="max-width: 500px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_cad.png"  class="rounded" style="max-width: 100%">
</div></center>

<!--![]({{ site.url }}{{ site.baseurl }}/images/respic/theme_cad.png){: style="width: 450px; float: right;"}-->
The ever-increasing design complexity in very-large-scale integration (VLSI) implementation has far exceeded what many existing electronic design automation (EDA) tools can scale with reasonable design time and effort. A key fundamental challenge is that EDA must incorporate new parallel paradigms comprising manycore central processing units (CPUs) and graphics processing units (GPUs) to achieve transformational performance and productivity milestones. However, this goal is impossible to achieve without a novel computing system to tackle the implementation complexities of parallelizing EDA, such as irregular task parallelism, large CPU-GPU dependent tasks, dynamic control flow, and distributed computing, which cannot be expressed and executed efficiently with mainstream parallel computing systems. **Our research investigates new computing methods to advance the current state-of-the-art by assisting everyone to efficiently tackle the challenges of designing, implementing, and deploying parallel EDA algorithms on heterogeneous nodes.**
  
<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/opentimer_logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/OpenTimer/OpenTimer">OpenTimer: A High-performance Timing Analysis Tool for VLSI Systems</a></h4>
  <p>OpenTimer helps electronic design automation tool researchers and developers quickly analyze the timing of large circuit designs.</p>
  </div>
</div>

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/rtlflow-logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/dian-lun-lin/RTLflow">RTLflow: A GPU Acceleration Flow for RTL Simulation with Stimulus Batches</a></h4>
  <p>RTLflow helps circuit designers quickly simulate RTL designs using automatically generated C++ and CUDA code on a high-throughput GPU platform.</p>
  </div>
</div>

<hr>

### Theme 3: Quantum Computing

**Research Question**: *How can we create fast and reliable software for researchers and developers to understand quantum operations and design reliable quantum computers?*

<center><div style="max-width: 800px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_qc.png"  class="rounded" style="max-width: 100%">
</div></center>

Quantum computing (QC) is a promising computing paradigm for tackling certain types of problems that are classically intractable, such as cryptography, chemistry simulation, finance, and combinatorial optimization.
Among various QC applications, classical software support for quantum circuit analysis and synthesis
is essential for researchers to understand quantum algorithms and optimize quantum circuits.
However, building such software is extremely challenging 
because it demands large computation and memory to evaluate quantum operations.
For example, simulating an n-qubit quantum circuits requires an exponential size of vector to store 2^n
amplitudes, as a result of superposition.
**Our research investigates new algorithms for quantum circuit simulation and optimization by leveraging the power of classical high-performance computing techniques.**

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/bqsim.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/IDEA-CUHK/BQSim">BQSim: GPU-accelerated Batch Quantum Circuit Simulation</a></h4>
  <p>BQSim helps quantum computing researchers and developers quickly simulate how quantum circuits work using the power of GPU.</p>
  </div>
</div>

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100%; display: inline-block; text-align: center; margin: auto;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/FlatDD-logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/IDEA-CUHK/FlatDD">FlatDD: Quantum Circuit Simulation using Decision Diagram and Flat Array</a></h4>
  <p>FlatDD helps quantum computing researchers and developers quickly simulate the functionality of quantum circuits using efficient CPU-parallel algorithms.</p>
  </div>
</div>

<hr>

### Theme 4: Machine Learning Systems

**Research Question**: *How can we accelerate machine learning kernels in large-scale inference and training workloads using modern heterogeneous computing techniques?*

<center><div style="max-width: 500px">
<img src="{{ site.url }}{{ site.baseurl }}/images/respic/theme_ml.png"  class="rounded" style="max-width: 100%">
</div></center>

Machine learning has become centric to a wide range of today's applications, such as autonomous driving, recommendation systems, and natural language processing. Machine learning algorithms are based on deep neural networks (DNN), which commonly have millions or billions of parameters to compute. Due to the unique performance characteristics, graphics processing units (GPUs) are increasingly used for machine learning applications and can dramatically accelerate neural network training and inference. Modern GPUs are fast and are equipped with new programming models and scheduling runtimes that can bring significant yet largely untapped performance benefits to many machine learning applications. For example, our research has shown that by leveraging the new GPU task graph model in CUDA to describe end-to-end parallelism, we can achieve 5--10 times speed-up over existing systems. **Our research investigates novel parallel algorithms and frameworks to accelerate machine learning system kernels with order-of-magnitude performance breakthrough.**

<div class="row row-padded align-items-center">
  <div class="col-md-2 col-sm-2 masthead">
  <div style="max-width: 100px; display: inline-block; text-align: center;">
  <p><img src="{{ site.url }}{{ site.baseurl }}/images/logopic/snig_logo.png" style="width: 100%;"></p>
  </div>
  </div>
  <div class="col-md-10 col-sm-10">
  <h4><a href="https://github.com/dian-lun-lin/SNIG">SNIG: Large Sparse Neural Network Inference using Task Graph Parallelism</a></h4>
  <p>SNIG is the Champion-Award inference engine of the 2020 IEEE/MIT/Amazon HPEC Graph Challenge for Large Sparse Neural Network.</p>
  </div>
</div>

<br>


