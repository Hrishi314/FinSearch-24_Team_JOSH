# FinSearch'24 Project: Deep Reinforcement Learning to Optimize Stock Trading Strategy

Welcome to the FinSearch'24 repository! This project leverages **Reinforcement Learning (RL)** to enhance stock trading strategies and maximize investment returns. Developed by the Finance Club, IIT Bombay, our study explores the effectiveness of RL techniques like **Deep Q-Networks (DQN)** in dynamic financial markets.

**_Important Note_**: Please do not copy this README or any part of the project. For any questions or clarifications, please reach out to me at [jatin.ee.iitb@gmail.com](mailto:jatin.ee.iitb@gmail.com).

---

## Table of Contents

1. [Introduction](#introduction)
2. [Project Roadmap](#project-roadmap)
3. [Methods and Algorithms](#methods-and-algorithms)
4. [Implementation](#implementation)
5. [Results and Analysis](#results-and-analysis)
6. [Resources](#resources)
7. [Contact](#contact)

---

## Introduction

Predicting stock market trends has always been a challenging yet essential endeavor in finance. This project focuses on training an RL agent on historical market data to develop a trading strategy that maximizes returns while balancing risk.

**Objectives**:
- Compare traditional models like **ARIMA** and **LSTM** with reinforcement learning models in a stock trading scenario.
- Assess RL's adaptability and profitability against these traditional models.
  
Our team members include:
- **Sangeetha D** (Roll No: 22B3310)
- **Hrishikesh S** (Roll No: 22B4217)
- **Jatin Kumar** (Roll No: 22B3922)
- **Oviya S** (Roll No: 22B3918)

Mentor: **Likhitha Sree**

---

## Project Roadmap

To guide our development, we designed a [Project Roadmap](https://github.com/your-repo/roadmap). This roadmap outlines each phase of our project and details the integration of various components, including data preprocessing, model selection, and hyperparameter tuning.

*For the detailed roadmap, please refer to our [Roadmap Document](https://github.com/your-repo/roadmap).*  

---

## Methods and Algorithms

### 1. Time Series Forecasting Models

1. **ARIMA (Autoregressive Integrated Moving Average)**:
   - A statistical model frequently used for time series forecasting due to its simplicity and interpretability. It was chosen as a benchmark to compare with RL.

2. **LSTM (Long Short-Term Memory)**:
   - A type of RNN capable of learning complex patterns in time series data. Used for its robustness in sequential data modeling.

### 2. Reinforcement Learning and Deep Q-Networks (DQN)

Incorporating **Deep Q-Learning** allows us to adapt trading strategies in real-time. RL adapts to market conditions dynamically, making it an optimal choice for trading decisions that respond to changing data patterns.

For more technical details, please review our [Midterm Report](https://github.com/your-repo/midterm-report).

---

## Implementation

The project's implementation phase involved two main components: **LSTM-based prediction** and **Q-Learning-based RL trading strategy**.

1. **LSTM Implementation**:
   - The LSTM model was trained to predict stock prices using NIFTY 50 data. We used **MinMaxScaler** for data normalization, and predictions were made using a one-step look-back window.

   *Explore the implementation code here:* [LSTM Implementation.ipynb](https://github.com/your-repo/lstm-implementation)

2. **Q-Learning Implementation**:
   - The RL model was designed with a two-action space: **Hold** or **Buy**. A Q-table was initialized, and an epsilon-greedy policy was applied to balance exploration and exploitation.

   *Explore the implementation code here:* [Q-Learning Implementation.ipynb](https://github.com/your-repo/rl-implementation)

---

## Results and Analysis

Our results indicate that the RL agent outperformed the LSTM model in both short-term (6-week) and long-term (1-year) simulations. The Q-learning-based RL model demonstrated better adaptability, yielding a significantly higher return on investment.

Comparison of model performance is detailed in the [End-Term Report](https://github.com/your-repo/end-term-report), complete with performance graphs and statistical analysis.

---

## Resources

### Reports and Notebooks

- **Mid-Term Report**: [FinSearch'24 Mid-Term Report](https://github.com/your-repo/midterm-report)
- **End-Term Report**: [FinSearch'24 End-Term Report](https://github.com/your-repo/end-term-report)
- **Test Cases**: [Test Cases for Model Evaluation](https://github.com/your-repo/test-cases)

For code files and model notebooks:
- **LSTM Model Notebook**: [LSTM Model](https://github.com/your-repo/lstm-implementation)
- **Reinforcement Learning Model Notebook**: [RL Model](https://github.com/your-repo/rl-implementation)

---

## Contact

For any questions about this repository or other queries, please feel free to contact me:

- **Jatin Kumar**: [jatin.ee.iitb@gmail.com](mailto:jatin.ee.iitb@gmail.com)

---

**_Please do not copy_**: This work is the culmination of our team's efforts at FinSearch'24, IIT Bombay. Duplication or unauthorized sharing is strictly prohibited and may result in academic or legal consequences.
