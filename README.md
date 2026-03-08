# harmonic-oscillator-pinn
Code accompanying my blog post: [So, what is a physics-informed neural network?](https://benmoseley.blog/my-research/so-what-is-a-physics-informed-neural-network/)

<img src="figures/pinn.gif" width="850">

## Instructions to estimate carbon footprint:-
 1. Install codecarbon (pip install codecarbon)
 2. import codecarbon
 3. start tracker (tracker.start()) and stoped in the end (tracker .stop())
 4. got emission file.
 5. Then Generate a report using the current version of the GreenMetaData tool

## Data Summary:-
1. Project Name - Harmonic oscillator PINN
2. Emissions ~0.000717 kg CO2
3. Energy Consumed ~0.0010053 kWh
4. Duration ~294.59 seconds (approx. 4.9 minutes)

## System Specifications:-
1. CPU Intel(R) Pentium(R) Silver N5000 CPU @ 1.10GHz (4 cores)
2. RAM ~3.83 GB
3. OS- Windows-10

## Green software pattern that could be applied to make the code more environmentally friendly:-
1. Select the Right Hardware/VM Instance Types
2. Optimize the Size of AI/ML Models

## Redesign proposal
1. Using low powered CPU and faster RAM's instead of using massive and power-hungry servers, by this we can reduce the time and energy consumption.
2. By using methods pruning and quantization to reduce the complexity and neurons, which reduce the CPU and Ram consumption by 10% to 20% aprox.