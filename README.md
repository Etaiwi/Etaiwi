# Hi, I'm Etai Wigman

I'm an M.Sc. student in Electrical & Computer Engineering at Ben-Gurion University, interested in **Algorithm Engineering, Machine Learning Engineering, AI Research, and Data Science**.

My projects connect mathematical modeling with implementation and experimentation: sparse recovery, time-series forecasting, numerical linear algebra, sensor-data analysis, and computer vision. I also use coding agents to turn practical requirements into personal tools and workflows.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Etai_Wigman-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/etai-wigman/)
[![Email](https://img.shields.io/badge/Email-wigman.etai@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:wigman.etai@gmail.com)

## What I work on

- Algorithm design and problem-solving
- Machine learning, deep learning, and model evaluation
- Signal processing and data-driven experimentation
- Computer vision and image-processing systems
- Applied AI services and LLM-based workflows
- AI-assisted development, requirements definition, and manual functional testing

## Education

- **M.Sc. - Electrical & Computer Engineering**, Ben-Gurion University · 2026–2029 (expected)
- **B.Sc. - Electrical & Computer Engineering**, Ben-Gurion University · 2019–2024 · Signal Processing, Algorithms, and Machine Learning

Recent M.Sc. coursework: Model-Based Deep Learning, Information Theory, Numerical Linear Algebra, and Time Series Analysis.

## Featured projects

### [Sparse Recovery with Model-Based Deep Learning](https://github.com/ThEpiCake/hyperlista-mbdl) · [Report](https://github.com/Etaiwi/Etaiwi/blob/main/reports/sparse-recovery-report.pdf)

Co-developed a two-person study comparing classical and learned sparse-recovery methods. Designed and implemented three ISTA-derived deep-unfolded models. In the synthetic sparse-recovery experiment at K=16, the 32-parameter StepThresholdISTA model achieved −23.6 dB NMSE versus −20.3 dB for a LISTA baseline with about six million parameters.

`Python` · `PyTorch` · `Signal Processing` · `Optimization` · `Deep Unfolding`

### [Dynamic Multiscale DLinear Forecasting](https://github.com/Etaiwi/long-horizon-time-series-forecasting) · [Report](https://github.com/Etaiwi/Etaiwi/blob/main/reports/dlinear-forecasting-report.pdf)

Reconstructed DLinear and developed a dynamic multiscale decomposition for multivariate Weather forecasting. Built a chronological training and evaluation pipeline with leakage-safe preprocessing, validation-driven model selection, and evaluation across four forecast horizons.

At the 96-step horizon, the model reduced paired test MSE by 5.29% and MAE by 4.23% relative to DLinear, with approximately 0.2% additional trainable parameters. This was an AI-assisted, two-person academic submission with shared final verification.

`Python` · `PyTorch` · `Pandas` · `Time-Series Forecasting` · `Experimental Design`

### [Numerical Linear Algebra & Matrix Compression](https://github.com/Etaiwi/numerical-linear-algebra) · [Report](https://github.com/Etaiwi/Etaiwi/blob/main/reports/numerical-linear-algebra-report.pdf)

Implemented and evaluated SVD-based numerical-rank analysis, randomized rank estimation, and blocked randomized low-rank approximation for structured matrices. Benchmarked accuracy, runtime scaling, and memory efficiency against full SVD.

Used AI assistance for quadtree and hierarchical-matrix construction, then verified and corrected the structure, implemented memory analysis, and evaluated dense and low-rank block storage. Individual academic project.

`Python` · `NumPy` · `Numerical Linear Algebra` · `Randomized Algorithms` · `Hierarchical Matrices`

### [Parkinson's Disease Detection](https://github.com/Etaiwi/parkinsons-disease-detection) · [Report](https://github.com/Etaiwi/Etaiwi/blob/main/reports/parkinsons-detection-report.pdf)

Built an individual Freezing-of-Gait detection pipeline using data from 136 Parkinson's patients. Compared CNN and traditional machine-learning approaches using lower-back accelerometer signals, achieving 81.8% sensitivity, 80.8% specificity, and 0.890 AUC with the selected 1D CNN on four-second windows.

`Python` · `TensorFlow` · `NumPy` · `SciPy` · `Signal Processing` · `Time-Series Classification`

### [Snowboard Visual Simulator](https://github.com/Etaiwi/snowboard-simulator-using-image-processing) · [Report](https://github.com/Etaiwi/Etaiwi/blob/main/reports/snowboard-simulator-report.pdf)

Co-developed a real-time computer-vision interface in a four-person team. The system maps body posture and motion from a webcam stream to snowboard-game controls using classical image-processing techniques.

`Python` · `OpenCV` · `NumPy` · `Image Processing` · `Real-Time Computer Vision`

### [GenAI Safety Analyst](https://github.com/Etaiwi/genai-safety-analyst) · [Live demo](https://huggingface.co/spaces/Etaiwi/genai-safety-analyst)

Built and deployed an AI-assisted content-safety service combining classification, policy retrieval, vector search, structured outputs, validation, rate limiting, mocked tests, and container packaging.

`Python` · `FastAPI` · `Pydantic` · `LangChain` · `ChromaDB` · `Docker`

## Additional projects

### Career Automation System

A personal system I use regularly for job monitoring, application tracking, and CV optimization. Its four components are Job Scraper, Application Tracker, Career Knowledge, and Career Workflow.

The combined workflow takes a job URL, captures the listing, creates an application record, generates a tailored CV from confirmed career evidence, and saves that CV in the tracker. The job monitor runs scheduled checks every 15 minutes.

I originated the ideas, defined requirements and workflow behavior, manually tested the tools, and directed improvements through feedback. Codex implemented all code and automated tests.

`Codex` · `AI-Assisted Software Development` · `Requirements Definition` · `Manual Functional Testing` · `AI Workflow Design`

### [Face Mask Detection](https://github.com/Etaiwi/face-mask-detection) · [Live demo](https://huggingface.co/spaces/Etaiwi/face-mask-detection)

Built and deployed a binary image-classification application using MobileNetV2 transfer learning, with image-upload and webcam inference through an interactive Streamlit interface.

`Python` · `PyTorch` · `MobileNetV2` · `Transfer Learning` · `Streamlit`

## Technical toolbox

**Algorithms and problem-solving**

`Algorithm Design` · `Optimization` · `Signal Processing` · `Numerical Methods` · `Numerical Linear Algebra`

**Machine learning and data**

`PyTorch` · `TensorFlow` · `Scikit-learn` · `Pandas` · `Deep Learning` · `Model Evaluation` · `Time-Series Analysis`

**Computer vision and applied AI**

`OpenCV` · `Image Processing` · `Transfer Learning` · `FastAPI` · `LLM Workflows` · `Vector Databases`

**Programming and workflow**

`Python` · `C` · `C++` · `MATLAB` · `NumPy` · `Jupyter` · `Git/GitHub` · `SQL (foundational)`

**AI-assisted project practices**

`Codex` · `AI-Assisted Software Development` · `Requirements Definition` · `Manual Functional Testing` · `AI Workflow Design`

## Engineering foundations

Academic laboratory experience includes programming and debugging physical MSP430 boards in assembly using IAR Embedded Workbench, with GPIO, interrupts, timers, PWM, and ADC sampling. Circuit laboratory work includes reading schematics, building circuits, and measuring their behavior with oscilloscopes, bench power supplies, signal generators, and multimeters.

C/C++ and MATLAB experience comes from academic coursework; SQL foundations include hands-on completion of the PostgreSQL tutorial.

## Let's connect

I'm open to **internships, student positions, and full-time opportunities**, as well as conversations and collaborations involving:

- Algorithm Engineering
- Machine Learning Engineering
- AI Research
- Data Science
- Computer Vision
- Applied AI

If you're working on an interesting real-world problem—or think my background may fit your team—feel free to [connect with me on LinkedIn](https://www.linkedin.com/in/etai-wigman/) or [send me an email](mailto:wigman.etai@gmail.com).
