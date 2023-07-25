# Navier Stokes solver using Physics Informed Neural Networks

This is replication of an existing implementation [Navier Stokes using PINNs](https://github.com/AZarbade/Navier-Stokes-using-PINNs) but with some changes to work with GPU acceleration.

### Reference work by: 
- [Maziar Raissi](https://github.com/maziarraissi)
- Raissi, Maziar, Paris Perdikaris, and George E. Karniadakis. "[Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations.](https://www.sciencedirect.com/science/article/pii/S0021999118307125)" Journal of Computational Physics 378 (2019): 686-707
- [ComputationalDomain](https://github.com/ComputationalDomain). Repo: [PINNs](https://github.com/ComputationalDomain/PINNs)


### Dependencies:
- Visual Studio Code. {recommended for easier setup}
- Dev Containers by Microsoft.
    [Dev Containers - Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-containers)
- Docker.
    [Docker](https://www.docker.com/)
   
### Installation:
1. Clone the repository.
    ~~~
    git clone https://github.com/AZarbade/Navier-Stokes-using-PINNs-GPU.git
    ~~~
2. Open it in Visual studio code.   
3. Open command pallet using "Ctrl + Shift + P".   
4. Search for "Dev Containers: Rebuild Container" and press "Enter".
5. This will build the entire project with all the required dependencies and at the prompts "Have fun!". This should indicate an errorless execution.
6. Project is now completely setup.   
