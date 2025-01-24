# Welcome to the ODINN research project and SciML modelling framework

ODINN is an open-source glacier modelling project that investigates innovative hybrid methods to discover new laws governing glacier physics. 
By leveraging differentiable programming techniques, we are developing hybrid models that integrate differential equations describing ice flow with machine learning models to learn and parameterize specific components of these equations. 
This approach facilitates the discovery of parameterizations for glacier processes, helping to bridge the gap between our current mechanistic understanding of glacier physics and emerging observational data.

## Architecture

ODINN is split among multiple Julia packages (with the exception of Gungnir), each one playing a very specific role:

<img src="https://github.com/ODINN-SciML/.github/blob/main/ODINN_architecture.png" width="500">
