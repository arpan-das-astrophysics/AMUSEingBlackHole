# AMUSEingBlackHole

### A N-body cosmological simulation code to study the formation of Supermassive Black Hole seeds in dense stellar cluster.

##### This is the official repository for AMUSEinggBlackHole. AMUSEingBlackHole is a N-body code that is able to simulate dense stellar clusters with many star particles. It is super fast and could use a single CPU, CPU cluster, GPU and GPU cluster as per requirement.

---

#### Key feautres:

1. Accretion recipes: Different accretion recipes e.g., constant accretion, **Bondi-hoyle-lyttleton** accretion and **Eddington** accretion

2. Mass-radii relationship for main sequence stars 

3. Collisions are handled by sticky sphere approximation 

4. Gravitational interactions between the stars are modelled using the N-body code ph4

5. Gravitational effect of the gas cloud is included via an analytical background potential coupled to the N-body code using the BRIDGE method

6. All the outputs are saved in Pandas Dataframe

--- 

#### Powered by: 

* Numpy
* scipy
* astropy
* pandas
* matplotlib
* mpi4py
* cuda 

---
