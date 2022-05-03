# DRpathways
Metabolic pathways involved in drug resistance of Mtb

**Pathway modeling**
The models are created based on reactions that convert a set of species into another set of species. Each species are located in a compartment which is a physical location with a size. The biochemical network was constructed by structured diagram editor Cell Designer v4.4 (Funahashi A. et al., 2008) in a machine-readable format (*.sbml). The Graphical notation for protein, receptor, gene, drug, and molecules was used in pathway modeling.

 **Reaction parameters**
The missing kinetic measurements were assigned, including mass-action, Hill, convenience, and Michaelis-Menten-based kinetics using SBML squeezer v2.1 (Dräger A et al., 2008). Each reaction is analyzed for its properties, such as reactants, products, and all participating modulators, before deciding which kinetic equation to apply. Whenever this equation can be used, it also provides zeroth-order forward or reverses mass-action kinetics, depending on the reaction's reversibility. The complex, generic protein, macromolecules, truncated protein, and RNA were treated as enzymes; pH, temperature, and the remaining parameters are in default mode.
 
 **Pathway simulation**
After applying missing kinetics, all curated and edited pathways were simulated using COPASI v4.29 (http://copasi.org/). The simulation was performed using stochastic 
Runge-Kutta (RI5) kinetics and Gibson & Bruck's version of Gillespie's algorithm for exact stochastic kinetics. The time course simulation was set for 1000ns with teninterval sizes

# KEGG ID Pathway name Essential Non-essential
1. mtu00061 Fatty acid biosynthesis 3 8
2. mtu00190 Oxidative phosphorylation 11 23
3. mtu00240 Pyrimidine metabolism 15 12
4. mtu00360 Phenylalanine metabolism 2 34
5. mtu00380 Tryptophan metabolism 2 41
6. mtu00473 D-Alanine metabolism 2 -
7. mtu00550 Peptidoglycan biosynthesis 10 5
8. mtu00571 Lipo-arabinomannan biosynthesis 5 -
9. mtu00627 Amino-benzoate degradation 2 29
10. mtu00670 One carbon pool by folate 8 5
11. mtu00760 Nicotinate & nicotinamide metabolism 6 15
12. mtu00790 Folate biosynthesis 8 16
13. mtu00983 Drug metabolism - Isoniazid - -
