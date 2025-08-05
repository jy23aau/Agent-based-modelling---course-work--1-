# Agent-based-modelling---course-work--1-
7COM1032-0901- Artificial Life with Robotics 
Here is a concise and well-structured description you can use for the README file in your GitHub repository for this Agent Based Modelling project:

# Agent Based Modelling of Infectious Disease Spread

This project involves developing a NetLogo simulation model to analyze the spread of an infectious disease among two populations of agents within a defined timeframe. The model evaluates the effects of various factors affecting virus transmission including:

- **Travel Restrictions:** Comparing agents staying local within designated regions versus free movement.
- **Social Distancing:** Assessing impacts of agents maintaining distance versus no distancing.
- **Self-Isolation:** Analyzing infected agents’ behavior when self-isolating compared to not self-isolating.

## Model Features and Requirements
- The simulation world is a 91 x 91 patch grid divided into two colored halves (pink and gray), with wrap-around edges.
- Populations: Pink (1500 agents) and Gray (1000 agents) represented as turtles with attributes such as infection status, antibodies, and group.
- Infection, survival, immunity, and behavioral parameters such as infection rate, survival rate, immunity duration, undetected infectious period, and illness duration are all configurable.
- Agent behaviors include movement, infection probabilities based on proximity, and changes in status (infected, immune, self-isolating).
- Real-time outputs track infection rates, mortality, and antibody prevalence across populations.

## Analysis
The model includes automated analysis to determine:
- Most and least effective containment measures.
- Populations with highest mortality and immunity rates.
- Key variables impacting self-isolation effectiveness.
- Impact of population density under travel restrictions.

## Usage Notes
- The model follows strict coding requirements to ensure fair assessment: prohibited commands are avoided, and global variables for marking are defined.
- Compatible with NetLogo version 6.1.0 or above.
- Submit your model file named `_ABM.nlogo`.

This README text is clear, professional, and highlights the key aspects for users and evaluators accessing your GitHub project.
