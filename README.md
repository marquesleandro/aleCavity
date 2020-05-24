 ======================================__
         ALE Cavity logBook__
 created by Leandro Marques at 05/2020 __
 Gesar Search Group - http://www.gesar.uerj.br/en/staff/equipe-gesar.html __
 State University of the Rio de Janeiro __
 e-mail: marquesleandro67@gmail.com __
 ======================================__




-------------------------------------------------------------------
05/24/20
-> renamed all mesh: 
mesh5 --> mesh6
mesh4 --> mesh5
mesh3 --> mesh4
mesh2 --> mesh3
mesh1 --> mesh2

-> created mesh1 with 68 elements

new mesh1 Paramenters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Gaussian Quadrature (Gauss Points): 3
 Mesh: mesh6.msh
 Number of nodes: 45
 Number of elements: 68
 Smallest edge length: 0.139089
 Time step: 0.0695446171216
 Number of time iteration: 142
 Reynolds number: 100.0
 Schmidt number: 1.0
-------------------------------------------------------------------



-------------------------------------------------------------------
05/22/20

-> mesh4 final result OK
-> mesh5 simulating yet

 all simulations was used ALE = 0.5
 nt = 10.0/dt -> 10s forced

mesh4 Parameters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Gaussian Quadrature (Gauss Points): 3
 Mesh: mesh4.msh
 Number of nodes: 7905
 Number of elements: 15488
 Smallest edge length: 0.009071
 Time step: 0.002
 Number of time iteration: 4999
 Reynolds number: 100.0
 Schmidt number: 1.0
-------------------------------------------------------------------



-------------------------------------------------------------------
05/21/20

-> simulations for relative error analysis using analytic linear element
   all simulations was used ALE = 0.5
   nt = 10.0/dt -> 10s forced

-> mesh4 and mesh5 will be simulated in cluster



mesh1 Parameters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Gaussian Quadrature (Gauss Points): 3
 Mesh: mesh1.msh
 Number of nodes: 142
 Number of elements: 242
 Smallest edge length: 0.072570
 Time step: 0.0362851257348
 Number of time iteration: 274 
 Reynolds number: 100.0
 Schmidt number: 1.0


mesh 2 Parameters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Gaussian Quadrature (Gauss Points): 3
 Mesh: mesh2.msh
 Number of nodes: 525
 Number of elements: 968
 Smallest edge length: 0.036285
 Time step: 0.0181425628674
 Number of time iteration: 550 
 Reynolds number: 100.0
 Schmidt number: 1.0


mesh3 Parameters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Gaussian Quadrature (Gauss Points): 3
 Mesh: mesh3.msh
 Number of nodes: 2017
 Number of elements: 3872
 Smallest edge length: 0.018143
 Time step: 0.00907128143369
 Number of time iteration: 1101 
 Reynolds number: 100.0
 Schmidt number: 1.0
-------------------------------------------------------------------


-------------------------------------------------------------------
05/21/20

-> Create logBook
-> modified simulatio_option Debug number 
-> modified input to automate Debug option
-> created polynomial_option for Analytic Linear Element
-> created if in Assembly for Analytic Linear Element
-> compared Horiziontal and Vertical results with Luis and Ghia OK

Simulation Parameters:
 Scheme: Semi Lagrangian
 Element Type: Analytic Linear Element
 Mesh: cavity.msh
 Time step: 0.006
 Number of time iteration: 999
 Reynolds number: 100.0
 Schmidt number: 1.0
-------------------------------------------------------------------

 
