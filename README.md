# Volatility-Surface-Calibration-for-Exotic-Options-Pricing

- This repository provides a stochastic volatility pricing engine based on Heston model calibration to vanilla option market quotes across a wide range of strikes and maturities, ensuring market-consistent volatility smiles and term structures.

- The tool provides 3D volatility surface visualization with color gradients to visualize how implied volatility changes across strikes and
expirations, allowing a clear comparison between market-implied volatilities and the model outputs for detecting potential inconsistencies or arbitrage opportunities.

- Building on the calibrated framework, model is extended to path-dependent payoffs, implementing Monte Carlo simulations to accurately value barrier options and other exotic derivatives.

- Finally, I integrated these components into interactive dashboards, where sliders and controls allow real-time adjustments of strikes, barrier levels, and simulated paths. This made it possible to perform dynamic scenario analyses and to explore the risk/return profile of exotic option payoffs under different market conditions.

- The tool integrates interactive dashboards for scenario analysis, equipped with sliders to vary strikes, barrier levels, and simulated paths in real time, enabling dynamic exploration of exotic option risk/return profiles under different market conditions.
