# Lorenz-Equations
This Github encompasses all the work done for the ESP project in the Differential Equations class at Vanier College during the winter 2023 semester.

# Introduction to Edward Norton Lorenz and a few key mathematical concepts
Edward Norton Lorenz, born on may 23, 1917, is a renowned mathematician and meteorologist. He first obtained a bachelor's degree in mathematics at Dartmouth College, followed by a master's in mathematics at the university of Harvard in 1940. He finished his studies at the Massachusetts Institute of Technology where he obtained both a master's and a doctoral degree in meteorology, in 1943 and 1948 respectively. For the rest of his career, Lorenz joined the department of meteorological scientific research at the MIT, and eventually became a professor in that domain. He served as the head of the Department of Meteorology from 1977 to 1981. In his study of meteorology, Edward Lorenz was interested in the prediction of the weather, and attempted to attribute to it a precise mathematical model taking into account parameters such as pressure or temperature. Thanks to his research and his numerical model, he was able to explain why long-term predictions of the weather forecasts are often inaccurate; the system of equations governing the atmospheric changes is chaotic, meaning that it is very sensible to initial values. In other words, a small inaccuracy in the first values means that further down the equations, the values become very different than the expected ones. Lorenz passes away on April 16, 2008, at the age of 90 [1].

In a differential equation or a system of differential equations, a critical point is defined as a point where the derivatives of all involved equations are equal to 0. A critical point can be either considered as stable, unstable or semi stable. A critical point in a differential equation is considered as stable if any small deviation from the critical point is set on an integral curve that converges right back to the critical point. A small deviation from an unstable critical point diverges from the critical point. A semi stable critical point converges on one side of the point and diverges on the other side of the point. If a differential equation has a parameter that is not set at a specific value, the critical points of the equation can be graphed as a function of the parameter. Plotting these functions makes it easy to visualise what impact the parameter has on the behavior of the differential equation at those critical points and is called a bifurcation diagram. In the case of the Lorenz equations, a bifurcation diagram for the Rayleigh parameter is a very useful tool to predict chaotic behavior.

In a dynamic system, an attractor, as the name suggests, makes all orbits from the system converge towards it. No matter what the initial conditions are, the system will be attracted to the attractor as time advances. An attractor can either be a fixed point, a limit cycle, or a strange attractor (Note: There are other types of attractors that are not mentioned as they are not relevant to the study). A point attractor is simply a fixed point towards which the system shifts. A limit cycle is a periodic cycle towards which the system evolves. A strange attractor is defined as an attractor on which a system exhibits chaotic behavior. While the motion inside is seemingly random and unstable, the system is generally bounded to that attractor, it is bounded to a set from which the system's orbits are unable to escape. Plotting a strange attractor yields a fractal structure, meaning that the shape of the attractor cannot simply be determined as one curve, but an infinite amount of smaller and smaller curves. The following image is an example of a strange attractor.
![HenonMappng](https://user-images.githubusercontent.com/128184412/226466686-c99d8e21-c7ea-4641-9270-286c90706e47.png)
The Hénon map is a map of the strange attractor created for certain valuyes of parameters in the set of equations corresponding to it [2]. At first glance, it looks like a simple curve, but if we were to zoom in on the graph, we would see smaller curves appear in what seemed like a uniform line at first. No matter how much we would zoom in, it would still yield new, smaller curves. This is what is called a fractal.

A system exhibiting chaotic behavior is a system that is highly sensitive on initial conditions. By changing the initial conditions ever so slightly, the trajectory of the system will diverge exponentially quickly from the first set of initial conditions. This sensitivity to initial conditions, paired with the presence of a strange attractor, creates a sense of randomness to the system, hence the name chaos. However, even if the system exhibits aperiodic behavior, it still cannot be labeled as random. A chaotic system is deterministic; it is a system on which a set of initial conditions is imposed and its solution can be predicted as time advances by solving the system itself. The chaotic nature arises when small variations to the initial conditions create entirely different trajectories as solutions when compared to the first set of initial conditions. For certain values of the parameter ρ in the Lorenz equations, the system will be exhibiting this chaotic behavior which is the main point of interest in this system of ordinary differential equations.
