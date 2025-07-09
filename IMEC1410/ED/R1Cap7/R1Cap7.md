![](_page_0_Picture_1.jpeg)

0 0 1000 Stress (MPa) 2000 0.000 0.040 0.010 Strain Strain 0.080 2000 TS *σ*y *(b)*

Figure (*a*) shows an apparatus that measures the mechanical properties of metals using applied tensile forces (Sections 7.3, 7.5, and 7.6). Figure (*b*) was generated from a tensile test performed by an apparatus such as this on a steel specimen. Data plotted are stress

> (vertical axis—a measure of applied force) versus strain (horizontal axis—related to the degree of specimen elongation). The mechanical properties of modulus of elasticity (stiffness, *E*), yield strength (*σy*), and tensile strength (*TS*) are determined as noted on these graphs.

Figure (*c*) shows a suspension bridge. The weight of the bridge deck and automobiles imposes tensile forces on the vertical suspender cables. These forces are transferred to the main suspension cable, which sags in a more-or-less parabolic shape. The metal alloy(s) from which these cables are constructed must meet certain stiffness and strength criteria. Stiffness and strength of the alloy(s) may be assessed from tests performed using a tensile-testing apparatus (and the resulting stress–strain plots) similar to those shown.

**216 •** 

# **WHY STUDY** *Mechanical Properties***?**

It is incumbent on engineers to understand how the various mechanical properties are measured and what these properties represent; they may be called upon to design structures/components using predetermined materials such that unacceptable levels of deformation and/or failure will not occur. We demonstrate this procedure with respect to the design of a tensile-testing apparatus in Design Example 7.1.

# **Learning Objectives**

After studying this chapter, you should be able to do the following:

- **1.** Define engineering stress and engineering strain.
- **2.** State Hooke's law and note the conditions under which it is valid.
- **3.** Define Poisson's ratio.
- **4.** Given an engineering stress–strain diagram, determine (a) the modulus of elasticity, (b) the yield strength (0.002 strain offset), and (c) the tensile strength and (d) estimate the percentage elongation.
- **5.** For the tensile deformation of a ductile cylindrical metal specimen, describe changes in specimen profile to the point of fracture.
- **6.** Compute ductility in terms of both percentage elongation and percentage reduction of area for a material that is loaded in tension to fracture.

- **7.** For a specimen being loaded in tension, given the applied load, the instantaneous cross-sectional dimensions, and original and instantaneous lengths, compute true stress and true strain values.
- **8.** Compute the flexural strengths of ceramic rod specimens that have been bent to fracture in three-point loading.
- **9.** Make schematic plots of the three characteristic stress–strain behaviors observed for polymeric materials.
- **10.** Name the two most common hardness-testing techniques; note two differences between them.
- **11.** (a) Name and briefly describe the two different microindentation hardness testing techniques, and (b) cite situations for which these techniques are generally used.
- **12.** Compute the working stress for a ductile material.

# **7.1 INTRODUCTION**

Many materials are subjected to forces or loads when in service; examples include the aluminum alloy from which an airplane wing is constructed and the steel in an automobile axle. In such situations it is necessary to know the characteristics of the material and to design the member from which it is made so that any resulting deformation will not be excessive and fracture will not occur. The mechanical behavior of a material reflects its response or deformation in relation to an applied load or force. Key mechanical design properties are stiffness, strength, hardness, ductility, and toughness.

The mechanical properties of materials are ascertained by performing carefully designed laboratory experiments that replicate as nearly as possible the service conditions. Factors to be considered include the nature of the applied load and its duration, as well as the environmental conditions. It is possible for the load to be tensile, compressive, or shear, and its magnitude may be constant with time or may fluctuate continuously. Application time may be only a fraction of a second, or it may extend over a period of many years. Service temperature may be an important factor.

Mechanical properties are of concern to a variety of parties (e.g., producers and consumers of materials, research organizations, government agencies) that have differing interests. Consequently, it is imperative that there be some consistency in

the manner in which tests are conducted and in the interpretation of their results. This consistency is accomplished by using standardized testing techniques. Establishment and publication of these standards are often coordinated by professional societies. In the United States the most active organization is the American Society for Testing and Materials (ASTM). Its *Annual Book of ASTM Standards* (http://www.astm.org) comprises numerous volumes that are issued and updated yearly; a large number of these standards relate to mechanical testing techniques. Several of these are referenced by footnote in this and subsequent chapters.

The role of structural engineers is to determine stresses and stress distributions within members that are subjected to well-defined loads. This may be accomplished by experimental testing techniques and/or by theoretical and mathematical stress analyses. These topics are treated in traditional texts on stress analysis and strength of materials.

Materials and metallurgical engineers however, are concerned with producing and fabricating materials to meet service requirements as predicted by these stress analyses. This necessarily involves an understanding of the relationships between the microstructure (i.e., internal features) of materials and their mechanical properties.

Materials are frequently chosen for structural applications because they have desirable combinations of mechanical characteristics. This chapter discusses the stress–strain behaviors of metals, ceramics, and polymers and the related mechanical properties; it also examines other important mechanical characteristics. Discussions of the microscopic aspects of deformation mechanisms and methods to strengthen and regulate the mechanical behaviors are deferred to Chapter 8.

# **7.2 CONCEPTS OF STRESS AND STRAIN**

If a load is static or changes relatively slowly with time and is applied uniformly over a cross section or surface of a member, the mechanical behavior may be ascertained by a simple stress–strain test; these are most commonly conducted for metals at room temperature. There are three principal ways in which a load may be applied: namely, tension, compression, and shear (Figures 7.1*a*, *b*, *c*). In engineering practice many loads are torsional rather than pure shear; this type of loading is illustrated in Figure 7.1*d*.

# **Tension Tests1**

One of the most common mechanical stress–strain tests is performed in *tension*. As will be seen, the tension test can be used to ascertain several mechanical properties of materials that are important in design. A specimen is deformed, usually to fracture, with a gradually increasing tensile load that is applied uniaxially along the long axis of a specimen. A standard tensile specimen is shown in Figure 7.2. Normally, the cross section is circular, but rectangular specimens are also used. This "dogbone" specimen configuration was chosen so that, during testing, deformation is confined to the narrow center region (which has a uniform cross section along its length) and also to reduce the likelihood of fracture at the ends of the specimen. The standard diameter is approximately 12.8 mm (0.5 in.), whereas the reduced section length should be at least four times this diameter; 60 mm (2<sup>1</sup> <sup>4</sup> in.) is common. Gauge length is used in ductility computations, as discussed in Section 7.6; the standard value is 50 mm (2.0 in.). The specimen is mounted by its ends into the holding

<sup>1</sup> ASTM Standards E8 and E8M, "Standard Test Methods for Tension Testing of Metallic Materials."

l

![](_page_3_Figure_1.jpeg)

grips of the testing apparatus (Figure 7.3). The tensile testing machine is designed to elongate the specimen at a constant rate and to continuously and simultaneously measure the instantaneous applied load (with a load cell) and the resulting elongation (using an extensometer). A stress–strain test typically takes several minutes to perform and is destructive; that is, the test specimen is permanently deformed and usually fractured. [Chapteropening photograph (*a*) for this chapter is of a modern tensile-testing apparatus.]

illustration of how a tensile load produces an elongation and positive linear strain. (*b*) Schematic illustration of how a compressive load produces contraction and a negative linear strain. (*c*) Schematic representation of shear strain *γ*, where *γ* = tan *θ*. (*d*) Schematic representation deformation (i.e., angle of twist *ϕ*) produced by an applied torque *T*.

**Figure 7.2** A standard tensile specimen with circular cross section.

![](_page_4_Figure_2.jpeg)

The output of such a tensile test is recorded (usually on a computer) as load or force versus elongation. These load–deformation characteristics depend on the specimen size. For example, it requires twice the load to produce the same elongation if the cross-sectional area of the specimen is doubled. To minimize these geometrical factors, load and elongation are normalized to the respective parameters of **engineering stress**  and **engineering strain.** Engineering stress *σ* is defined by the relationship

$$
\sigma = \frac{F}{A_0} \tag{7.1}
$$

in which *F* is the instantaneous load applied perpendicular to the specimen cross section, in units of newtons (N) or pounds force (lbf), and *A*0 is the original cross-sectional area before any load is applied (m<sup>2</sup> or in.2 ). The units of engineering stress (referred to subsequently as just *stress*) are megapascals, MPa (SI) (where 1 MPa = 10<sup>6</sup> N/m<sup>2</sup> ), and pounds force per square inch, psi (customary U.S.).<sup>2</sup>

Engineering strain *ε* is defined according to

$$
\varepsilon = \frac{l_i - l_0}{l_0} = \frac{\Delta l}{l_0} \tag{7.2}
$$

in which *l*0 is the original length before any load is applied and *li* is the instantaneous length. Sometimes the quantity *li* − *l*0 is denoted as Δ*l* and is the deformation elongation or change in length at some instant, as referenced to the original length. Engineering strain (subsequently called just *strain*) is unitless, but meters per meter or inches per inch is often used; the value of strain is obviously independent of the unit

**Figure 7.3** Schematic representation of the apparatus used to conduct tensile stress– strain tests. The specimen is elongated by the moving crosshead; load cell and extensometer measure, respectively, the magnitude of the applied load and the elongation. (Adapted from H. W. Hayden, W. G. Moffatt, and J. Wulff, *The Structure and Properties of Materials*, Vol. III, *Mechanical Behavior*, p. 2. Copyright © 1965 by John Wiley & Sons, New York. Reprinted by permission of John Wiley & Sons, Inc.)

![](_page_4_Figure_10.jpeg)

### 2 Conversion from one system of stress units to the other is accomplished by the relationship 145 psi = 1 MPa.

### **engineering stress engineering strain**

Definition of engineering stress (for tension and compression)

Definition of engineering strain (for tension and compression)

Tutorial Video: What Are the Differences between Stress and Strain?

system. Sometimes strain is also expressed as a percentage, in which the strain value is multiplied by 100.

# **Compression Tests<sup>3</sup>**

Compression stress–strain tests may be conducted if in-service forces are of this type. A compression test is conducted in a manner similar to the tensile test, except that the force is compressive and the specimen contracts along the direction of the stress. Equations 7.1 and 7.2 are utilized to compute compressive stress and strain, respectively. By convention, a compressive force is taken to be negative, which yields a negative stress. Furthermore, because *l*0 is greater than *li* , compressive strains computed from Equation 7.2 are necessarily also negative. Tensile tests are more common because they are easier to perform; also, for most materials used in structural applications, very little additional information is obtained from compressive tests. Compressive tests are used when a material's behavior under large and permanent (i.e., plastic) strains is desired, as in manufacturing applications, or when the material is brittle in tension.

# **Shear and Torsional Tests<sup>4</sup>**

For tests performed using a pure shear force as shown in Figure 7.1*c*, the shear stress *τ* is computed according to

$$
\tau = \frac{F}{A_0} \tag{7.3}
$$

where *F* is the load or force imposed parallel to the upper and lower faces, each of which has an area of *A*0. The shear strain *γ* is defined as the tangent of the strain angle *θ*, as indicated in the figure. The units for shear stress and strain are the same as for their tensile counterparts.

*Torsion* is a variation of pure shear in which a structural member is twisted in the manner of Figure 7.1*d*; torsional forces produce a rotational motion about the longitudinal axis of one end of the member relative to the other end. Examples of torsion are found for machine axles and drive shafts as well as for twist drills. Torsional tests are normally performed on cylindrical solid shafts or tubes. A shear stress *τ* is a function of the applied torque *T*, whereas shear strain *γ* is related to the angle of twist, *ϕ* in Figure 7.1*d*.

# **Geometric Considerations of the Stress State**

Stresses that are computed from the tensile, compressive, shear, and torsional force states represented in Figure 7.1 act either parallel or perpendicular to planar faces of the bodies represented in these illustrations. Note that the stress state is a function of the orientations of the planes upon which the stresses are taken to act. For example, consider the cylindrical tensile specimen of Figure 7.4 that is subjected to a tensile stress *σ* applied parallel to its axis. Furthermore, consider also the plane *p*-*p*′ that is oriented at some arbitrary angle *θ* relative to the plane of the specimen endface. Upon this plane *p*-*p*′, the applied stress is no longer a pure tensile one. Rather,

3 ASTM Standard E9, "Standard Test Methods of Compression Testing of Metallic Materials at Room Temperature." 4 ASTM Standard E143, "Standard Test Method for Shear Modulus at Room Temperature."

Definition of shear stress

![](_page_5_Figure_13.jpeg)

# **Figure 7.4**

Schematic representation showing normal (*σ*′) and shear (*τ*′) stresses that act on a plane oriented at an angle *θ* relative to the plane taken perpendicular to the direction along which a pure tensile stress (*σ*) is applied.

a more complex stress state is present that consists of a tensile (or normal) stress *σ*′ that acts normal to the *p*-*p*′ plane and, in addition, a shear stress *τ*′ that acts parallel to this plane; both of these stresses are represented in the figure. Using mechanicsof-materials principles,<sup>5</sup> it is possible to develop equations for *σ*′ and *τ*′ in terms of *σ* and *θ*, as follows:

$$
\sigma' = \sigma \cos^2 \theta = \sigma \left( \frac{1 + \cos 2\theta}{2} \right) \tag{7.4a}
$$

$$
\tau' = \sigma \sin \theta \cos \theta = \sigma \left( \frac{\sin 2\theta}{2} \right) \tag{7.4b}
$$

These same mechanics principles allow the transformation of stress components from one coordinate system to another coordinate system with a different orientation. Such treatments are beyond the scope of the present discussion.

# Elastic Deformation

# **7.3 STRESS–STRAIN BEHAVIOR**

Hooke's law relationship between engineering stress and engineering strain for elastic deformation (tension and compression)

### **modulus of elasticity**

# **elastic deformation**

![](_page_6_Picture_10.jpeg)

 **:** VMSE Metal Alloys

Tutorial Video: Calculating Elastic Modulus Using a Stress vs. Strain Curve

The degree to which a structure deforms or strains depends on the magnitude of an imposed stress. For most metals that are stressed in tension and at relatively low levels, stress and strain are proportional to each other through the relationship

$$
\sigma = E \varepsilon \tag{7.5}
$$

This is known as *Hooke's law*, and the constant of proportionality *E* (GPa or psi)6 is the **modulus of elasticity,** or *Young's modulus*. For most typical metals, the magnitude of this modulus ranges between 45 GPa (6.5 × 106 psi), for magnesium, and 407 GPa (59 × 106 psi), for tungsten. The moduli of elasticity are slightly higher for ceramic materials and range between about 70 and 500 GPa (10 × 106 and 70 × 106 psi). Polymers have modulus values that are smaller than those of both metals and ceramics and lie in the range 0.007 to 4 GPa (103 to 0.6 × 106 psi). Room-temperature modulus of elasticity values for a number of metals, ceramics, and polymers are presented in Table 7.1. A more comprehensive modulus list is provided in Table B.2, Appendix B.

Deformation in which stress and strain are proportional is called **elastic deformation;** a plot of stress (ordinate) versus strain (abscissa) results in a linear relationship, as shown in Figure 7.5. The slope of this linear segment corresponds to the modulus of elasticity *E*. This modulus may be thought of as stiffness, or a material's resistance to elastic deformation. The greater the modulus, the stiffer is the material, or the smaller is the elastic strain that results from the application of a given stress. The modulus is an important design parameter for computing elastic deflections.

Elastic deformation is nonpermanent, which means that when the applied load is released, the piece returns to its original shape. As shown in the stress–strain plot (Figure 7.5), application of the load corresponds to moving from the origin up and along the straight line. Upon release of the load, the line is traversed in the opposite direction, back to the origin.

5 See, for example, W. F. Riley, L. D. Sturges, and D. H. Morris, *Mechanics of Materials,* 6th edition, Wiley, Hoboken, NJ, 2006.

6 The SI unit for the modulus of elasticity is gigapascal (GPa) where 1 GPa = 109 N/m2 = 103 MPa.

|                                    | Modulus of Elasticity |                   | Shear Modulus |            |                 |
|------------------------------------|-----------------------|-------------------|---------------|------------|-----------------|
| Material                           | GPa                   | 106<br>psi        | GPa           | 106<br>psi | Poisson's Ratio |
|                                    |                       | Metal Alloys      |               |            |                 |
| Tungsten                           | 407                   | 59                | 160           | 23.2       | 0.28            |
| Steel                              | 207                   | 30                | 83            | 12.0       | 0.30            |
| Nickel                             | 207                   | 30                | 76            | 11.0       | 0.31            |
| Titanium                           | 107                   | 15.5              | 45            | 6.5        | 0.34            |
| Copper                             | 110                   | 16                | 46            | 6.7        | 0.34            |
| Brass                              | 97                    | 14                | 37            | 5.4        | 0.34            |
| Aluminum                           | 69                    | 10                | 25            | 3.6        | 0.33            |
| Magnesium                          | 45                    | 6.5               | 17            | 2.5        | 0.35            |
|                                    |                       | Ceramic Materials |               |            |                 |
| Aluminum oxide (Al2O3)             | 393                   | 57                | —             | —          | 0.22            |
| Silicon carbide (SiC)              | 345                   | 50                | —             | —          | 0.17            |
| Silicon nitride (Si3N4)            | 304                   | 44                | —             | —          | 0.30            |
| Spinel (MgAl2O4)                   | 260                   | 38                | —             | —          | —               |
| Magnesium oxide (MgO)              | 225                   | 33                | —             | —          | 0.18            |
| a<br>Zirconia (ZrO2)               | 205                   | 30                | —             | —          | 0.31            |
| Mullite (3Al2O3-2SiO2)             | 145                   | 21                | —             | —          | 0.24            |
| Glass–ceramic (Pyroceram)          | 120                   | 17                | —             | —          | 0.25            |
| Fused silica (SiO2)                | 73                    | 11                | —             | —          | 0.17            |
| Soda–lime glass                    | 69                    | 10                | —             | —          | 0.23            |
|                                    |                       | Polymers b        |               |            |                 |
| Phenol-formaldehyde                | 2.76–4.83             | 0.40–0.70         | —             | —          | —               |
| Poly(vinyl chloride) (PVC)         | 2.41–4.14             | 0.35–0.60         | —             | —          | 0.38            |
| Poly(ethylene terephthalate) (PET) | 2.76–4.14             | 0.40–0.60         | —             | —          | 0.33            |
| Polystyrene (PS)                   | 2.28–3.28             | 0.33–0.48         | —             | —          | 0.33            |
| Poly(methyl methacrylate) (PMMA)   | 2.24–3.24             | 0.33–0.47         | —             | —          | 0.37–0.44       |
| Polycarbonate (PC)                 | 2.38                  | 0.35              | —             | —          | 0.36            |
| Nylon 6,6                          | 1.59–3.79             | 0.23–0.55         | —             | —          | 0.39            |
| Polypropylene (PP)                 | 1.14–1.55             | 0.17–0.23         | —             | —          | 0.40            |
| Polyethylene—high density (HDPE)   | 1.08                  | 0.16              | —             | —          | 0.46            |
| Polytetrafluoroethylene (PTFE)     | 0.40–0.55             | 0.058–0.080       | —             | —          | 0.46            |
| Polyethylene—low density (LDPE)    | 0.17–0.28             | 0.025–0.041       | —             | —          | 0.33–0.40       |

**Table 7.1** Room-Temperature Elastic and Shear Moduli and Poisson's Ratio for Various Materials

*a* Partially stabilized with 3 mol% Y2O3.

*b Modern Plastics Encyclopedia '96*, McGraw-Hill, New York, 1995.

> There are some materials (i.e., gray cast iron, concrete, and many polymers) for which this elastic portion of the stress–strain curve is not linear (Figure 7.6); hence, it is not possible to determine a modulus of elasticity as described previously. For this nonlinear behavior, either the *tangent* or *secant modulus* is normally used. The tangent modulus is taken as the slope of the stress–strain curve at some specified level of stress, whereas

![](_page_8_Figure_1.jpeg)

the secant modulus represents the slope of a secant drawn from the origin to some given point of the *σ*–*ε* curve. The determination of these moduli is illustrated in Figure 7.6.

On an atomic scale, macroscopic elastic strain is manifested as small changes in the interatomic spacing and the stretching of interatomic bonds. As a consequence, the magnitude of the modulus of elasticity is a measure of the resistance to separation of adjacent atoms, that is, the interatomic bonding forces. Furthermore, this modulus is proportional to the slope of the interatomic force–separation curve (Figure 2.10*a*) at the equilibrium spacing:

$$
E \propto \left(\frac{dF}{dr}\right)_{r_0} \tag{7.6}
$$

Figure 7.7 shows the force–separation curves for materials having both strong and weak interatomic bonds; the slope at *r*0 is indicated for each.

![](_page_8_Figure_6.jpeg)

![](_page_9_Figure_1.jpeg)

**Figure 7.8** Plot of modulus of elasticity versus temperature for tungsten, steel, and aluminum.

(Adapted from K. M. Ralls, T. H. Courtney, and J. Wulff, *Introduction to Materials Science and Engineering*. Copyright © 1976 by John Wiley & Sons, New York. Reprinted by permission of John Wiley & Sons, Inc.)

Differences in modulus values among metals, ceramics, and polymers are a direct consequence of the different types of atomic bonding that exist for the three materials types. Furthermore, with increasing temperature, the modulus of elasticity decreases for all but some of the rubber materials; this effect is shown for several metals in Figure 7.8.

As would be expected, the imposition of compressive, shear, or torsional stresses also evokes elastic behavior. The stress–strain characteristics at low stress levels are virtually the same for both tensile and compressive situations, to include the magnitude of the modulus of elasticity. Shear stress and strain are proportional to each other through the expression

Relationship between shear stress and shear strain for elastic deformation

$$
\tau = G\gamma \tag{7.7}
$$

where *G* is the *shear modulus—*the slope of the linear elastic region of the shear stress–strain curve. Table 7.1 also gives the shear moduli for a number of common metals.

# **7.4 ANELASTICITY**

To this point, it has been assumed that elastic deformation is time independent that is, that an applied stress produces an instantaneous elastic strain that remains constant over the period of time the stress is maintained. It has also been assumed that upon release of the load, the strain is totally recovered—that is, that the strain immediately returns to zero. In most engineering materials, however, there will also exist a time-dependent elastic strain component—that is, elastic deformation will continue after the stress application, and upon load release, some finite time is required for complete recovery. This time-dependent elastic behavior is known as **anelasticity,** and it is due to time-dependent microscopic and atomistic processes that are attendant to the deformation. For metals, the anelastic component is normally small and is often neglected. However, for some polymeric materials, its magnitude is significant; in this case it is termed *viscoelastic behavior,* which is the discussion topic of Section 7.15.

**anelasticity**

# **EXAMPLE PROBLEM 7.1**

# **Elongation (Elastic) Computation**

A piece of copper originally 305 mm (12 in.) long is pulled in tension with a stress of 276 MPa (40,000 psi). If the deformation is entirely elastic, what will be the resultant elongation?

### *Solution*

Because the deformation is elastic, strain is dependent on stress according to Equation 7.5. Furthermore, the elongation Δ*l* is related to the original length *l*0 through Equation 7.2. Combining these two expressions and solving for Δ*l* yields

$$
\sigma = \varepsilon E = \left(\frac{\Delta l}{l_0}\right) E
$$
$$
\Delta l = \frac{\sigma l_0}{E}
$$

The values of *σ* and *l*0 are given as 276 MPa and 305 mm, respectively, and the magnitude of *E* for copper from Table 7.1 is 110 GPa (16 × 10<sup>6</sup> psi). Elongation is obtained by substitution into the preceding expression as

$$
\Delta l = \frac{(276 \text{ MPa})(305 \text{ mm})}{110 \times 10^3 \text{ MPa}} = 0.77 \text{ mm} (0.03 \text{ in.})
$$

# **7.5 ELASTIC PROPERTIES OF MATERIALS**

When a tensile stress is imposed on a metal specimen, an elastic elongation and accompanying strain *εz* result in the direction of the applied stress (arbitrarily taken to be the *z* direction), as indicated in Figure 7.9. As a result of this elongation, there will be constrictions in the lateral (*x* and *y*) directions perpendicular to the applied stress; from these contractions, the compressive strains *εx* and *εy* may be determined. If the applied stress is uniaxial (only in the *z* direction) and the material is isotropic, then *ε<sup>x</sup>* = *εy*. A parameter termed **Poisson's ratio** *ν* is defined as the ratio of the lateral and axial strains, or

### **Poisson's ratio**

Definition of Poisson's ratio in terms of lateral and axial strains

Relationship among elastic parameters modulus of elasticity, shear modulus, and Poisson's ratio

$$
\nu = -\frac{\varepsilon_x}{\varepsilon_z} = -\frac{\varepsilon_y}{\varepsilon_z} \tag{7.8}
$$

For virtually all structural materials, *εx* and *εz* will be of opposite sign; therefore, the negative sign is included in the preceding expression to ensure that *ν* is positive.7

Theoretically, Poisson's ratio for isotropic materials should be <sup>1</sup> <sup>4</sup>; furthermore, the maximum value for *ν* (or the value for which there is no net volume change) is 0.50. For many metals and other alloys, values of Poisson's ratio range between 0.25 and 0.35. Table 7.1 shows *ν* values for several common materials; a more comprehensive list is given in Table B.3 of Appendix B.

For isotropic materials, shear and elastic moduli are related to each other and to Poisson's ratio according to

$$
E = 2G(1+\nu) \tag{7.9}
$$

<sup>7</sup> Some materials (e.g., specially prepared polymer foams), when pulled in tension, actually expand in the transverse direction. In these materials, both *εx* and *εz* of Equation 7.8 are positive, and thus Poisson's ratio is negative. Materials that exhibit this effect are termed *auxetics.*

### **7.5 Elastic Properties of Materials • 227**

![](_page_11_Figure_1.jpeg)

In most metals *G* is about 0.4*E*; thus, if the value of one modulus is known, the other may be approximated.

Many materials are elastically anisotropic; that is, the elastic behavior (e.g., the magnitude of *E*) varies with crystallographic direction (see Table 3.8). For these materials, the elastic properties are completely characterized only by the specification of several elastic constants, their number depending on characteristics of the crystal structure. Even for isotropic materials, for complete characterization of the elastic properties, at least two constants must be given. Because the grain orientation is random in most polycrystalline materials, these may be considered to be isotropic; inorganic ceramic glasses are also isotropic. The remaining discussion of mechanical behavior assumes isotropy and polycrystallinity (for metals and ceramics) because this is the character of most engineering materials.

# **EXAMPLE PROBLEM 7.2**

# **Computation of Load to Produce Specified Diameter Change**

A tensile stress is to be applied along the long axis of a cylindrical brass rod that has a diameter of 10 mm (0.4 in.). Determine the magnitude of the load required to produce a 2.5 × 10<sup>−</sup><sup>3</sup> -mm (10<sup>−</sup><sup>4</sup> -in.) change in diameter if the deformation is entirely elastic.

![](_page_11_Figure_7.jpeg)

F

### *Solution*

This deformation situation is represented in the accompanying drawing.

 When the force *F* is applied, the specimen will elongate in the *z* direction and at the same

time experience a reduction in diameter, Δ*d*, of 2.5 × 10<sup>−</sup><sup>3</sup> mm in the *x* direction. For the strain in the *x* direction,

$$
\varepsilon_{x} = \frac{\Delta d}{d_0} = \frac{-2.5 \times 10^{-3} \text{ mm}}{10 \text{ mm}} = -2.5 \times 10^{-4}
$$

which is negative because the diameter is reduced.

 It next becomes necessary to calculate the strain in the *z* direction using Equation 7.8. The value for Poisson's ratio for brass is 0.34 (Table 7.1), and thus

$$
\varepsilon_z = -\frac{\varepsilon_x}{\nu} = -\frac{(-2.5 \times 10^{-4})}{0.34} = 7.35 \times 10^{-4}
$$

The applied stress may now be computed using Equation 7.5 and the modulus of elasticity, given in Table 7.1 as 97 GPa (14 × 106 psi), as

$$
\sigma = \varepsilon_z E = (7.35 \times 10^{-4})(97 \times 10^3 \text{ MPa}) = 71.3 \text{ MPa}
$$

Finally, from Equation 7.1, the applied force may be determined as

$$
F = \sigma A_0 = \sigma \left(\frac{d_0}{2}\right)^2 \pi
$$
  
=  $(71.3 \times 10^6 \,\text{N/m}^2) \left(\frac{10 \times 10^{-3} \,\text{m}}{2}\right)^2 \pi = 5600 \,\text{N} \ (1293 \,\text{lb}_f)$ 

# Mechanical Behavior—Metals

For most metallic materials, elastic deformation persists only to strains of about 0.005. As the material is deformed beyond this point, the stress is no longer proportional to strain (Hooke's law, Equation 7.5, ceases to be valid), and permanent, nonrecoverable, **plastic deformation** or **plastic deformation** occurs. Figure 7.10*a* plots schematically the tensile stress–strain

**Figure 7.10** (*a*) Typical stress– strain behavior for a metal, showing elastic and plastic deformations, the proportional limit *P*, and the yield strength *σy*, as determined using the 0.002 strain offset method. (*b*) Representative stress–strain behavior found for some steels, demonstrating

![](_page_12_Figure_14.jpeg)

behavior into the plastic region for a typical metal. The transition from elastic to plastic is a gradual one for most metals; some curvature results at the onset of plastic deformation, which increases more rapidly with rising stress.

From an atomic perspective, plastic deformation corresponds to the breaking of bonds with original atom neighbors and then the re-forming of bonds with new neighbors as large numbers of atoms or molecules move relative to one another; upon removal of the stress, they do not return to their original positions. This permanent deformation for metals is accomplished by means of a process called *slip,* which involves the motion of dislocations as discussed in Section 8.3.

# **7.6 TENSILE PROPERTIES**

**Yielding and Yield Strength**

![](_page_13_Picture_4.jpeg)

**yielding :** VMSE Metal Alloys

**proportional limit**

**yield strength**

Most structures are designed to ensure that only elastic deformation will result when a stress is applied. A structure or component that has plastically deformed—or experienced a permanent change in shape—may not be capable of functioning as intended. It is therefore desirable to know the stress level at which plastic deformation begins, or where the phenomenon of **yielding** occurs. For metals that experience this gradual elastic–plastic transition, the point of yielding may be determined as the initial departure from linearity of the stress–strain curve; this is sometimes called the **proportional limit,** as indicated by point *P* in Figure 7.10*a*, and represents the onset of plastic deformation on a microscopic level. The position of this point *P* is difficult to measure precisely. As a consequence, a convention has been established by which a straight line is constructed parallel to the elastic portion of the stress–strain curve at some specified strain offset, usually 0.002. The stress corresponding to the intersection of this line and the stress– strain curve as it bends over in the plastic region is defined as the **yield strength** *σy*. 8 This is demonstrated in Figure 7.10*a*. The units of yield strength are MPa or psi.<sup>9</sup>

For materials having a nonlinear elastic region (Figure 7.6), use of the strain offset method is not possible, and the usual practice is to define the yield strength as the stress required to produce some amount of strain (e.g., *ε* = 0.005).

Some steels and other materials exhibit the tensile stress–strain behavior shown in Figure 7.10*b*. The elastic–plastic transition is very well defined and occurs abruptly in what is termed a *yield-point phenomenon*. At the upper yield point, plastic deformation is initiated with an apparent decrease in engineering stress. Continued deformation fluctuates slightly about some constant stress value, termed the *lower yield point*; stress subsequently rises with increasing strain. For metals that display this effect, the yield strength is taken as the average stress that is associated with the lower yield point because it is well defined and relatively insensitive to the testing procedure.10 Thus, it is not necessary to employ the strain offset method for these materials.

The magnitude of the yield strength for a metal is a measure of its resistance to plastic deformation. Yield strengths range from 35 MPa (5000 psi) for a low-strength aluminum to greater than 1400 MPa (200,000 psi) for high-strength steels.

<sup>8</sup> *Strength* is used in lieu of *stress* because strength is a property of the metal, whereas stress is related to the magnitude of the applied load.

<sup>9</sup> For customary U.S. units, the unit of kilopounds per square inch (ksi) is sometimes used for the sake of convenience, where 1 ksi = 1000 psi.

<sup>10</sup>Note that to observe the yield point phenomenon, a "stiff" tensile-testing apparatus must be used; by "stiff," it is meant that there is very little elastic deformation of the machine during loading.

![](_page_14_Figure_1.jpeg)

**Figure 7.11** Typical engineering stress–strain behavior to fracture, point *F*. The tensile strength *TS* is indicated at point *M*. The circular insets represent the geometry of the deformed specimen at various points along the curve.

# **Tensile Strength**

**tensile strength**

After yielding, the stress necessary to continue plastic deformation in metals increases to a maximum, point *M* in Figure 7.11, and then decreases to the eventual fracture, point *F*. The **tensile strength** *TS* (MPa or psi) is the stress at the maximum on the engineering stress–strain curve (Figure 7.11). This corresponds to the maximum stress that can be sustained by a structure in tension; if this stress is applied and maintained, fracture will result. All deformation to this point is uniform throughout the narrow region of the tensile specimen. However, at this maximum stress, a small constriction or neck begins to form at some point, and all subsequent deformation is confined at this neck, as indicated by the schematic specimen insets in Figure 7.11. This phenomenon is termed *necking,* and fracture ultimately occurs at the neck.11 The fracture strength corresponds to the stress at fracture.

Tensile strengths vary from 50 MPa (7000 psi) for aluminum to as high as 3000 MPa (450,000 psi) for the high-strength steels. Typically, when the strength of a metal is cited for design purposes, the yield strength is used, because by the time a stress corresponding to the tensile strength has been applied, often a structure has experienced so much plastic deformation that it is useless. Furthermore, fracture strengths are not normally specified for engineering design purposes.

<sup>11</sup>The apparent decrease in engineering stress with continued deformation past the maximum point of Figure 7.11 is due to the necking phenomenon. As explained in Section 7.7, the true stress (within the neck) actually increases.

# **EXAMPLE PROBLEM 7.3**

# **Mechanical Property Determinations from Stress–Strain Plot**

From the tensile stress–strain behavior for the brass specimen shown in Figure 7.12, determine the following:

- **(a)** The modulus of elasticity
- **(b)** The yield strength at a strain offset of 0.002
- **(c)** The maximum load that can be sustained by a cylindrical specimen having an original diameter of 12.8 mm (0.505 in.)
- **(d)** The change in length of a specimen originally 250 mm (10 in.) long that is subjected to a tensile stress of 345 MPa (50,000 psi)

### *Solution*

**(a)** The modulus of elasticity is the slope of the elastic or initial linear portion of the stress– strain curve. The strain axis has been expanded in the inset of Figure 7.12 to facilitate this computation. The slope of this linear region is the rise over the run, or the change in stress divided by the corresponding change in strain; in mathematical terms,

$$
E = \text{slope} = \frac{\Delta \sigma}{\Delta \varepsilon} = \frac{\sigma_2 - \sigma_1}{\varepsilon_2 - \varepsilon_1} \tag{7.10}
$$

Inasmuch as the line segment passes through the origin, it is convenient to take both *σ*1 and *ε*<sup>1</sup> as zero. If *σ*2 is arbitrarily taken as 150 MPa, then *ε*2 will have a value of 0.0016. Therefore,

$$
E = \frac{(150 - 0) \text{ MPa}}{0.0016 - 0} = 93.8 \text{ GPa} (13.6 \times 10^6 \text{ psi})
$$

which is very close to the value of 97 GPa (14 × 106 psi) given for brass in Table 7.1.

![](_page_15_Figure_14.jpeg)

**Figure 7.12** The stress–strain behavior for the brass specimen discussed in Example Problem 7.3.

- **(b)** The 0.002 strain offset line is constructed as shown in the inset; its intersection with the stress–strain curve is at approximately 250 MPa (36,000 psi), which is the yield strength of the brass.
- **(c)** The maximum load that can be sustained by the specimen is calculated by using Equation 7.1, in which *σ* is taken to be the tensile strength—from Figure 7.12, 450 MPa (65,000 psi). Solving for *F*, the maximum load, yields

$$
F = \sigma A_0 = \sigma \left(\frac{d_0}{2}\right)^2 \pi
$$
  
=  $(450 \times 10^6 \,\text{N/m}^2) \left(\frac{12.8 \times 10^{-3} \,\text{m}}{2}\right)^2 \pi = 57,900 \,\text{N} \ (13,000 \,\text{lb}_f)$ 

**(d)** To compute the change in length, Δ*l*, in Equation 7.2, it is first necessary to determine the strain that is produced by a stress of 345 MPa. This is accomplished by locating the stress point on the stress–strain curve, point *A*, and reading the corresponding strain from the strain axis, which is approximately 0.06. Inasmuch as *l*<sup>0</sup> = 250 mm, we have

$$
\Delta l = \varepsilon l_0 = (0.06)(250 \text{ mm}) = 15 \text{ mm} (0.6 \text{ in.})
$$

# **Ductility**

**ductility**

**Ductility** is another important mechanical property. It is a measure of the degree of plastic deformation that has been sustained at fracture. A metal that experiences very little or no plastic deformation upon fracture is termed *brittle*. The tensile stress– strain behaviors for both ductile and brittle metals are schematically illustrated in Figure 7.13.

Ductility may be expressed quantitatively as either *percent elongation* or *percent reduction in area*. Percent elongation (%EL) is the percentage of plastic strain at fracture, or

Ductility, as percent elongation

$$
\%EL = \left(\frac{l_f - l_0}{l_0}\right) \times 100\tag{7.11}
$$

![](_page_16_Figure_12.jpeg)

![](_page_16_Figure_13.jpeg)

where *lf* is the fracture length12 and *l*0 is the original gauge length as given earlier. Inasmuch as a significant proportion of the plastic deformation at fracture is confined to the neck region, the magnitude of %EL will depend on specimen gauge length. The shorter *l*0, the greater is the fraction of total elongation from the neck and, consequently, the higher is the value of %EL. Therefore, *l*0 should be specified when percent elongation values are cited; it is commonly 50 mm (2 in.).

Percent reduction in area (%RA) is defined as

Ductility, as percent reduction in area

Tutorial Video: How do I determine ductility in percent elongation and percent reduction in area?

$$
\%RA = \left(\frac{A_0 - A_f}{A_0}\right) \times 100\tag{7.12}
$$

where *A*0 is the original cross-sectional area and *Af* is the cross-sectional area at the point of fracture.12 Values of percent reduction in area are independent of both *l*0 and *A*0. Furthermore, for a given material, the magnitudes of %EL and %RA will, in general, be different. Most metals possess at least a moderate degree of ductility at room temperature; however, some become brittle as the temperature is lowered (Section 9.8).

Knowledge of the ductility of materials is important for at least two reasons. First, it indicates to a designer the degree to which a structure will deform plastically before fracture. Second, it specifies the degree of allowable deformation during fabrication operations. We sometimes refer to relatively ductile materials as being "forgiving," in the sense that they may experience local deformation without fracture, should there be an error in the magnitude of the design stress calculation.

Brittle materials are *approximately* considered to be those having a fracture strain of less than about 5%.

Thus, several important mechanical properties of metals may be determined from tensile stress–strain tests. Table 7.2 presents some typical room-temperature values of yield strength, tensile strength, and ductility for several common metals (and also for a number of polymers and ceramics). These properties are sensitive to any prior deformation, the presence of impurities, and/or any heat treatment to which the metal has been subjected. The modulus of elasticity is one mechanical parameter that is insensitive to these treatments. As with modulus of elasticity, the magnitudes of both yield and tensile strengths decline with increasing temperature; just the reverse holds for ductility—it usually increases with temperature. Figure 7.14 shows how the stress–strain behavior of iron varies with temperature.

# **Resilience**

**Resilience** is the capacity of a material to absorb energy when it is deformed elastically and then, upon unloading, to have this energy recovered. The associated property is the *modulus of resilience, Ur*, which is the strain energy per unit volume required to stress a material from an unloaded state up to the point of yielding.

Computationally, the modulus of resilience for a specimen subjected to a uniaxial tension test is just the area under the engineering stress–strain curve taken to yielding (Figure 7.15), or

Definition of modulus of resilience

**resilience**

$$
U_r = \int_0^{\varepsilon_r} \sigma d\varepsilon \tag{7.13a}
$$

<sup>12</sup>Both *lf* and *Af* are measured subsequent to fracture and after the two broken ends have been repositioned back together.

|                                    | Yield Strength |                    | Tensile Strength |           | Ductility, %EL         |
|------------------------------------|----------------|--------------------|------------------|-----------|------------------------|
| Material                           | MPa            | ksi                | MPa              | ksi       | [in 50 mm<br>(2 in.)]a |
|                                    |                | Metal Alloysb      |                  |           |                        |
| Molybdenum                         | 565            | 82                 | 655              | 95        | 35                     |
| Titanium                           | 450            | 65                 | 520              | 75        | 25                     |
| Steel (1020)                       | 180            | 26                 | 380              | 55        | 25                     |
| Nickel                             | 138            | 20                 | 480              | 70        | 40                     |
| Iron                               | 130            | 19                 | 262              | 38        | 45                     |
| Brass (70 Cu–30 Zn)                | 75             | 11                 | 300              | 44        | 68                     |
| Copper                             | 69             | 10                 | 200              | 29        | 45                     |
| Aluminum                           | 35             | 5                  | 90               | 13        | 40                     |
|                                    |                | Ceramic Materialsc |                  |           |                        |
| d<br>Zirconia (ZrO2)               | —              | —                  | 800–1500         | 115–215   | —                      |
| Silicon nitride (Si3N4)            | —              | —                  | 250–1000         | 35–145    | —                      |
| Aluminum oxide (Al2O3)             | —              | —                  | 275–700          | 40–100    | —                      |
| Silicon carbide (SiC)              | —              | —                  | 100–820          | 15–120    | —                      |
| Glass–ceramic (Pyroceram)          | —              | —                  | 247              | 36        | —                      |
| Mullite (3Al2O3–2SiO2)             | —              | —                  | 185              | 27        | —                      |
| Spinel (MgAl2O4)                   | —              | —                  | 110–245          | 16–36     | —                      |
| Fused silica (SiO2)                | —              | —                  | 110              | 16        | —                      |
| Magnesium oxide (MgO)e             | —              | —                  | 105              | 15        | —                      |
| Soda–lime glass                    | —              | —                  | 69               | 10        | —                      |
|                                    |                | Polymers           |                  |           |                        |
| Nylon 6,6                          | 44.8–82.8      | 6.5–12             | 75.9–94.5        | 11.0–13.7 | 15–300                 |
| Polycarbonate (PC)                 | 62.1           | 9.0                | 62.8–72.4        | 9.1–10.5  | 110–150                |
| Poly(ethylene terephthalate) (PET) | 59.3           | 8.6                | 48.3–72.4        | 7.0–10.5  | 30–300                 |
| Poly(methyl methacrylate) (PMMA)   | 53.8–73.1      | 7.8–10.6           | 48.3–72.4        | 7.0–10.5  | 2.0–5.5                |
| Poly(vinyl chloride) (PVC)         | 40.7–44.8      | 5.9–6.5            | 40.7–51.7        | 5.9–7.5   | 40–80                  |
| Phenol-formaldehyde                | —              | —                  | 34.5–62.1        | 5.0–9.0   | 1.5–2.0                |
| Polystyrene (PS)                   | 25.0–69.0      | 3.63–10.0          | 35.9–51.7        | 5.2–7.5   | 1.2–2.5                |
| Polypropylene (PP)                 | 31.0–37.2      | 4.5–5.4            | 31.0–41.4        | 4.5–6.0   | 100–600                |
| Polyethylene—high density (HDPE)   | 26.2–33.1      | 3.8–4.8            | 22.1–31.0        | 3.2–4.5   | 10–1200                |
| Polytetrafluoroethylene (PTFE)     | 13.8–15.2      | 2.0–2.2            | 20.7–34.5        | 3.0–5.0   | 200–400                |
| Polyethylene—low density (LDPE)    | 9.0–14.5       | 1.3–2.1            | 8.3–31.4         | 1.2–4.55  | 100–650                |

| Table 7.2 | Room-Temperature Mechanical Properties (in Tension) for Various Materials |  |  |  |
|-----------|---------------------------------------------------------------------------|--|--|--|
|-----------|---------------------------------------------------------------------------|--|--|--|

*a* For polymers, percent elongation at break.

*b* Property values are for metal alloys in an annealed state.

*c* The tensile strength of ceramic materials is taken as flexural strength (Section 7.10).

*d* Partially stabilized with 3 mol% Y2O3.

*e* Sintered and containing approximately 5% porosity.

![](_page_19_Figure_1.jpeg)

**Figure 7.14** Engineering stress–strain behavior for iron at three temperatures.

Assuming a linear elastic region, we have

Modulus of resilience for linear elastic behavior

$$
U_r = \frac{1}{2} \sigma_y \varepsilon_y \tag{7.13b}
$$

in which *εy* is the strain at yielding.

The units of resilience are the product of the units from each of the two axes of the stress–strain plot. For SI units, this is joules per cubic meter (J/m<sup>3</sup> , equivalent to Pa), whereas with customary U.S. units it is inch-pounds force per cubic inch (in.-lbf/in.3 , equivalent to psi). Both joules and inch-pounds force are units of energy, and thus this area under the stress–strain curve represents energy absorption per unit volume (in cubic meters or cubic inches) of material.

Incorporation of Equation 7.5 into Equation 7.13b yields

Modulus of resilience for linear elastic behavior, incorporating Hooke's law

$$
U_r = \frac{1}{2} \sigma_y \varepsilon_y = \frac{1}{2} \sigma_y \left(\frac{\sigma_y}{E}\right) = \frac{\sigma_y^2}{2E}
$$
 (7.14)

Thus, resilient materials are those having high yield strengths and low moduli of elasticity; such alloys are used in spring applications.

# **Toughness**

**Toughness** is a mechanical term that may be used in several contexts. For one, toughness (or more specifically, *fracture toughness*) is a property that is indicative of a material's resistance to fracture when a crack (or other stress-concentrating defect) is present (as discussed in Section 9.5). Because it is nearly impossible (as well as costly) to manufacture materials with zero defects (or to prevent damage during service), fracture toughness is a major consideration for all structural materials.

### **toughness**

![](_page_19_Figure_15.jpeg)

![](_page_19_Figure_16.jpeg)

| Material | Yield<br>Strength (MPa) | Tensile<br>Strength (MPa) | Strain<br>at Fracture | Fracture<br>Strength (MPa) | Elastic<br>Modulus (GPa) |
|----------|-------------------------|---------------------------|-----------------------|----------------------------|--------------------------|
| A        | 310                     | 340                       | 0.23                  | 265                        | 210                      |
| B        | 100                     | 120                       | 0.40                  | 105                        | 150                      |
| C        | 415                     | 550                       | 0.15                  | 500                        | 310                      |
| D        | 700                     | 850                       | 0.14                  | 720                        | 210                      |
| E        |                         | Fractures before yielding |                       | 650                        | 350                      |

**Table 7.3** Tensile Stress–Strain Data for Several Hypothetical Metals to Be Used with Concept Checks 7.1 and 7.6

Tutorial Video: What is toughness and how do I determine its value?

and plastically deform before fracturing. For dynamic (high strain rate) loading conditions and when a notch (or point of stress concentration) is present, *notch toughness* is assessed by using an impact test, as discussed in Section 9.8.

Tutorial Video: Mechanical Property Calculations from Tensile Test Measurements

For the static (low strain rate) situation, a measure of toughness in metals (derived from plastic deformation) may be ascertained from the results of a tensile stress–strain test. It is the area under the *σ*−*ε* curve up to the point of fracture. The units are the same as for resilience (i.e., energy per unit volume of material). For a metal to be tough, it must display both strength and ductility. This is demonstrated in Figure 7.13, in which the stress–strain curves are plotted for both metal types. Hence, even though the brittle metal has higher yield and tensile strengths, it has a lower toughness than the ductile one, as can be seen by comparing the areas *ABC* and *AB*′*C*′ in Figure 7.13.

Another way of defining toughness is as the ability of a material to absorb energy

*Concept Check 7.1* Of those metals listed in Table 7.3:

- **(a)** Which will experience the greatest percentage reduction in area? Why?
- **(b)** Which is the strongest? Why?
- **(c)** Which is the stiffest? Why?

(The answer is available in *WileyPLUS*.)

# **7.7 TRUE STRESS AND STRAIN**

From Figure 7.11, the decline in the stress necessary to continue deformation past the maximum—point *M*—seems to indicate that the metal is becoming weaker. This is not at all the case; as a matter of fact, it is increasing in strength. However, the crosssectional area is decreasing rapidly within the neck region, where deformation is occurring. This results in a reduction in the load-bearing capacity of the specimen. The stress, as computed from Equation 7.1, is on the basis of the original cross-sectional area before any deformation and does not take into account this reduction in area at the neck.

**true stress**

Sometimes it is more meaningful to use a true stress–true strain scheme. **True stress**  *σT* is defined as the load *F* divided by the instantaneous cross-sectional area *Ai* over which deformation is occurring (i.e., the neck, past the tensile point), or

Definition of true stress

$$
\sigma_T = \frac{F}{A_i} \tag{7.15}
$$

![](_page_21_Figure_1.jpeg)

**Figure 7.16** A comparison of typical tensile engineering stress–strain and true stress–strain behaviors. Necking begins at point *M* on the engineering curve, which corresponds to *M*′ on the true curve. The "corrected" true stress–strain curve takes into account the complex stress state within the neck region.

**true strain**

Furthermore, it is occasionally more convenient to represent strain as **true strain**  *εT*, defined by

Definition of true strain

$$
\varepsilon_T = \ln \frac{l_i}{l_0} \tag{7.16}
$$

If no volume change occurs during deformation—that is, if

$$
A_i l_i = A_0 l_0 \tag{7.17}
$$

—then true and engineering stress and strain are related according to

Conversion of engineering stress to true stress

Conversion of engineering strain to true strain

True stress–true strain relationship in the plastic region of deformation (to the point of necking)

$$
\sigma_T = \sigma (1 + \varepsilon) \tag{7.18a}
$$

$$
\varepsilon_T = \ln(1 + \varepsilon) \tag{7.18b}
$$

Equations 7.18a and 7.18b are valid only to the onset of necking; beyond this point true stress and strain should be computed from actual load, cross-sectional area, and gauge length measurements.

A schematic comparison of engineering and true stress–strain behaviors is made in Figure 7.16. It is worth noting that the true stress necessary to sustain increasing strain continues to rise past the tensile point *M*′.

Coincident with the formation of a neck is the introduction of a complex stress state within the neck region (i.e., the existence of other stress components in addition to the axial stress). As a consequence, the correct stress (*axial*) within the neck is slightly lower than the stress computed from the applied load and neck cross-sectional area. This leads to the "corrected" curve in Figure 7.16.

For some metals and alloys the region of the true stress–strain curve from the onset of plastic deformation to the point at which necking begins may be approximated by

$$
\sigma_T = K \varepsilon_T^n \tag{7.19}
$$

In this expression, *K* and *n* are constants; these values vary from alloy to alloy and also depend on the condition of the material (whether it has been plastically deformed, heat-treated, etc.). The parameter *n* is often termed the *strain-hardening exponent* and has a value less than unity. Values of *n* and *K* for several alloys are given in Table 7.4.

## **Table 7.4**

The *n* and *K* Values (Equation 7.19) for Several Alloys

|                                       |      | K    |         |  |
|---------------------------------------|------|------|---------|--|
| Material                              | n    | MPa  | psi     |  |
| Low-carbon steel (annealed)           | 0.21 | 600  | 87,000  |  |
| 4340 steel alloy (tempered at 315°C)  | 0.12 | 2650 | 385,000 |  |
| 304 stainless steel (annealed)        | 0.44 | 1400 | 205,000 |  |
| Copper (annealed)                     | 0.44 | 530  | 76,500  |  |
| Naval brass (annealed)                | 0.21 | 585  | 85,000  |  |
| 2024 aluminum alloy (heat-treated—T3) | 0.17 | 780  | 113,000 |  |
| AZ-31B magnesium alloy (annealed)     | 0.16 | 450  | 66,000  |  |

# **EXAMPLE PROBLEM 7.4**

# **Ductility and True-Stress-at-Fracture Computations**

A cylindrical specimen of steel having an original diameter of 12.8 mm (0.505 in.) is tensile tested to fracture and found to have an engineering fracture strength *σf* of 460 MPa (67,000 psi). If its cross-sectional diameter at fracture is 10.7 mm (0.422 in.), determine

- **(a)** The ductility in terms of percentage reduction in area
- **(b)** The true stress at fracture

### *Solution*

**(a)** Ductility is computed, using Equation 7.12, as

$$
\%RA = \frac{\left(\frac{12.8 \text{ mm}}{2}\right)^2 \pi - \left(\frac{10.7 \text{ mm}}{2}\right)^2 \pi}{\left(\frac{12.8 \text{ mm}}{2}\right)^2 \pi} \times 100
$$
$$
= \frac{128.7 \text{ mm}^2 - 89.9 \text{ mm}^2}{128.7 \text{ mm}^2} \times 100 = 30\%
$$

**(b)** True stress is defined by Equation 7.15, where, in this case, the area is taken as the fracture area *Af*. However, the load at fracture must first be computed from the fracture strength as

$$
F = \sigma_f A_0 = (460 \times 10^6 \,\text{N/m}^2)(128.7 \,\text{mm}^2) \left(\frac{1 \,\text{m}^2}{10^6 \,\text{mm}^2}\right) = 59{,}200 \,\text{N}
$$

Thus, the true stress is calculated as

$$
\sigma_T = \frac{F}{A_f} = \frac{59,200 \text{ N}}{(89.9 \text{ mm}^2) \left(\frac{1 \text{ m}^2}{10^6 \text{ mm}^2}\right)}
$$
$$
= 6.6 \times 10^8 \text{ N/m}^2 = 660 \text{ MPa } (95,700 \text{ psi})
$$

# **EXAMPLE PROBLEM 7.5**

# **Calculation of Strain-Hardening Exponent**

Compute the strain-hardening exponent *n* in Equation 7.19 for an alloy in which a true stress of 415 MPa (60,000 psi) produces a true strain of 0.10; assume a value of 1035 MPa (150,000 psi) for *K*.

### *Solution*

This requires some algebraic manipulation of Equation 7.19 so that *n* becomes the dependent parameter. This is accomplished by taking logarithms and rearranging. Solving for *n* yields

$$
n = \frac{\log \sigma_T - \log K}{\log \varepsilon_T}
$$
$$
= \frac{\log(415 \text{ MPa}) - \log(1035 \text{ MPa})}{\log(0.1)} = 0.40
$$

# **7.8 ELASTIC RECOVERY AFTER PLASTIC DEFORMATION**

Upon release of the load during the course of a stress–strain test, some fraction of the total deformation is recovered as elastic strain. This behavior is demonstrated in Figure 7.17, a schematic engineering stress–strain plot. During the unloading cycle, the curve traces a near straight-line path from the point of unloading (point *D*), and its slope is virtually identical to the modulus of elasticity, or parallel to the initial elastic portion of the curve. The magnitude of this elastic strain, which is regained during unloading, corresponds to the strain recovery, as shown in Figure 7.17. If the load is reapplied, the curve will traverse essentially the same linear portion in the direction opposite to unloading; yielding will again occur at the unloading stress level where the unloading began. There will also be an elastic strain recovery associated with fracture.

# **7.9 COMPRESSIVE, SHEAR, AND TORSIONAL DEFORMATIONS**

Of course, metals may experience plastic deformation under the influence of applied compressive, shear, and torsional loads. The resulting stress–strain behavior into the plastic region is similar to the tensile counterpart (Figure 7.10*a*: yielding and the associated curvature). However, for compression, there is no maximum because necking does not occur; furthermore, the mode of fracture is different from that for tension.

*Concept Check 7.2* Make a schematic plot showing the tensile engineering stress–strain behavior for a typical metal alloy to the point of fracture. Now superimpose on this plot a schematic compressive engineering stress–strain curve for the same alloy. Explain any differences between the two curves.

(The answer is available in *WileyPLUS*.)

![](_page_24_Figure_1.jpeg)

**Figure 7.17** Schematic tensile stress–strain diagram showing the phenomena of elastic strain recovery and strain hardening. The initial yield strength is designated as *σ<sup>y</sup>*<sup>0</sup> ; *σyi* is the yield strength after releasing the load at point *D* and

![](_page_24_Figure_3.jpeg)

**Figure 7.18** A three-point loading scheme for measuring the stress–strain behavior and flexural strength of brittle ceramics, including expressions for computing stress for rectangular and circular cross sections.

# Mechanical Behavior—Ceramics

Ceramic materials are somewhat limited in applicability by their mechanical properties, which in many respects are inferior to those of metals. The principal drawback is a disposition to catastrophic fracture in a brittle manner with very little energy absorption. In this section we explore the salient mechanical characteristics of these materials and how these properties are measured.

# **7.10 FLEXURAL STRENGTH**

The stress–strain behavior of brittle ceramics is not usually ascertained by a tensile test as outlined in Section 7.2, for three reasons. First, it is difficult to prepare and test specimens having the required geometry. Second, it is difficult to grip brittle materials without fracturing them. Third, ceramics fail after only about 0.1% strain, which necessitates that tensile specimens be perfectly aligned to avoid the presence of bending stresses, which are not easily calculated. Therefore, a more suitable transverse bending test is most frequently used in which a rod specimen having either a circular or rectangular cross section is bent until fracture using a three- or four-point loading technique.13 The three-point loading scheme is illustrated in Figure 7.18. At the point of loading, the top surface of the specimen is placed in a state of compression, whereas the bottom surface is in tension. Stress is computed from the specimen thickness, the bending moment, and the moment of inertia of the cross section; these parameters are noted in Figure 7.18

<sup>13</sup>ASTM Standard C1161, "Standard Test Method for Flexural Strength of Advanced Ceramics at Ambient Temperature."

### **7.12 Influence of Porosity on the Mechanical Properties of Ceramics • 241**

for rectangular and circular cross sections. The maximum tensile stress (as determined using these stress expressions) exists at the bottom specimen surface directly below the point of load application. Because the tensile strengths of ceramics are about one-tenth of their compressive strengths, and because fracture occurs on the tensile specimen face, the flexure test is a reasonable substitute for the tensile test.

The stress at fracture using this flexure test is known as the **flexural strength,** *modulus of rupture, fracture strength,* or *bend strength,* an important mechanical parameter for brittle ceramics. For a rectangular cross section, the flexural strength *σfs* is given by

**flexural strength**

Flexural strength for a specimen having a rectangular cross section

Flexural strength for a specimen having a circular cross section

*<sup>σ</sup>fs* <sup>=</sup> <sup>3</sup>*Ff <sup>L</sup>* 2*bd*<sup>2</sup> (7.20a)

where *Ff* is the load at fracture, *L* is the distance between support points, and the other parameters are as indicated in Figure 7.18. When the cross section is circular, then

$$
\sigma_{fs} = \frac{F_f L}{\pi R^3} \tag{7.20b}
$$

where *R* is the specimen radius.

Characteristic flexural strength values for several ceramic materials are given in Table 7.2. Furthermore, *σfs* depends on specimen size; as explained in Section 9.6, with increasing specimen volume (i.e., specimen volume exposed to a tensile stress) there is an increase in the probability of the existence of a crack-producing flaw and, consequently, a decrease in flexural strength. In addition, the magnitude of flexural strength for a specific ceramic material is greater than its fracture strength measured from a tensile test. This phenomenon may be explained by differences in specimen volume that are exposed to tensile stresses: the entirety of a tensile specimen is under tensile stress, whereas only some volume fraction of a flexural specimen is subjected to tensile stresses—those regions in the vicinity of the specimen surface opposite to the point of load application (see Figure 7.18).

# **7.11 ELASTIC BEHAVIOR**

The elastic stress–strain behavior for ceramic materials using these flexure tests is similar to the tensile test results for metals: a linear relationship exists between stress and strain. Figure 7.19 compares the stress–strain behavior to fracture for aluminum oxide and glass. Again, the slope in the elastic region is the modulus of elasticity; the moduli of elasticity for ceramic materials are slightly higher than for metals (Table 7.1 and Table B.2, Appendix B). From Figure 7.19 note that neither glass nor aluminum oxide experiences plastic deformation prior to fracture.

# **7.12 INFLUENCE OF POROSITY ON THE MECHANICAL PROPERTIES OF CERAMICS**

For some ceramic fabrication techniques (Sections 14.8 and 14.9), the precursor material is in the form of a powder. Subsequent to compaction or forming of these powder particles into the desired shape, pores or void spaces exist between the powder particles. During the ensuing heat treatment, much of this porosity will be eliminated; however, often this pore elimination process is incomplete and some residual porosity will remain

**Figure 7.19** Typical stress–strain behavior to fracture for aluminum oxide and glass.

![](_page_26_Figure_2.jpeg)

(Figure 14.27). Any residual porosity will have a deleterious influence on both the elastic properties and strength. For example, for some ceramic materials the magnitude of the modulus of elasticity *E* decreases with volume fraction porosity *P* according to

$$
E = E_0(1 - 1.9P + 0.9P^2)
$$
\n(7.21)

where *E*0 is the modulus of elasticity of the nonporous material. The influence of volume fraction porosity on the modulus of elasticity for aluminum oxide is shown in Figure 7.20; the curve in the figure is according to Equation 7.21.

Porosity is deleterious to the flexural strength for two reasons: (1) pores reduce the cross-sectional area across which a load is applied, and (2) they also act as stress concentrators—for an isolated spherical pore, an applied tensile stress is amplified by a factor of 2. The influence of porosity on strength is rather dramatic; for example,

**Figure 7.20** The influence of porosity on the modulus of elasticity for aluminum oxide at room temperature. The curve drawn is according to Equation 7.21. (From R. L. Coble and W. D. Kingery, "Effect of Porosity on Physical Properties of Sintered Alumina," *J. Am. Ceram. Soc.,* **39,** 11, Nov. 1956, p. 381. Reprinted by permission of the American Ceramic Society.)

![](_page_26_Figure_8.jpeg)

Dependence of modulus of elasticity on volume fraction porosity

**Figure 7.21** The influence of porosity on the flexural strength of aluminum oxide at room temperature.

(From R. L. Coble and W. D. Kingery, "Effect of Porosity on Physical Properties of Sintered Alumina," *J. Am. Ceram. Soc.,* **39,** 11, Nov. 1956, p. 382. Reprinted by permission of the American Ceramic Society.)

![](_page_27_Figure_3.jpeg)

10 vol% porosity often decreases the flexural strength by 50% from the measured value for the nonporous material. The degree of the influence of pore volume on flexural strength is demonstrated in Figure 7.21, again for aluminum oxide. Experimentally, it has been shown that the flexural strength decreases exponentially with volume fraction porosity (*P*) as

*σfs* = *σ*<sup>0</sup> exp (−*nP*) (7.22)

Dependence of flexural strength on volume fraction porosity

where *σ*0 and *n* are experimental constants.

# Mechanical Behavior—Polymers

# **7.13 STRESS–STRAIN BEHAVIOR**

The mechanical properties of polymers are specified with many of the same parameters that are used for metals—that is, modulus of elasticity and yield and tensile strengths. For many polymeric materials, the simple stress–strain test is used to characterize some of these mechanical parameters.14 The mechanical characteristics of polymers, for the most part, are highly sensitive to the rate of deformation (strain rate), the temperature, and the chemical nature of the environment (the presence of water, oxygen, organic solvents, etc.). Some modifications of the testing techniques and specimen configurations used for metals are necessary with polymers, especially for highly elastic materials, such as rubbers.

![](_page_27_Picture_11.jpeg)

 **:** VMSE Polymers

Three typically different types of stress–strain behavior are found for polymeric materials, as represented in Figure 7.22. Curve *A* illustrates the stress–strain character for a brittle polymer, which fractures while deforming elastically. The behavior for a plastic material, curve *B*, is similar to that for many metallic materials; the initial deformation is elastic, which is followed by yielding and a region of plastic deformation. Finally, the deformation displayed by curve *C* is totally elastic; this rubber-like elasticity (large

<sup>14</sup>ASTM Standard D638, "Standard Test Method for Tensile Properties of Plastics."

![](_page_28_Figure_1.jpeg)

![](_page_28_Figure_2.jpeg)

**Figure 7.22** The stress–strain behavior for brittle (curve *A*), plastic (curve *B*), and highly elastic (elastomeric) (curve *C*) polymers.

**Figure 7.23** Schematic stress–strain curve for a plastic polymer showing how yield and tensile strengths are determined.

recoverable strains produced at low stress levels) is displayed by a class of polymers termed the **elastomers.**

Modulus of elasticity (termed *tensile modulus* or sometimes just *modulus* for polymers) and ductility in percent elongation are determined for polymers in the same manner as for metals (Section 7.6). For plastic polymers (curve *B*, Figure 7.22), the yield point is taken as a maximum on the curve, which occurs just beyond the termination of the linear-elastic region (Figure 7.23). The stress at this maximum is the yield strength (*σy*). Furthermore, tensile strength (*TS*) corresponds to the stress at which fracture occurs (Figure 7.23); *TS* may be greater than or less than *σy*. For these plastic polymers, strength is normally taken as tensile strength. Table 7.2 and Tables B.2 to B.4 in Appendix B give these mechanical properties for a number of polymeric materials.

In many respects, polymers are mechanically dissimilar to metals and ceramic materials (Figures 1.5 to 1.7). For example, the modulus for highly elastic polymeric materials may be as low as 7 MPa (103 psi), but it may run as high as 4 GPa (0.6 × 106 psi) for some very stiff polymers; modulus values for metals are much larger (Table 7.1). Maximum tensile strengths for polymers are about 100 MPa (15,000 psi), whereas for some metal alloys they are 4100 MPa (600,000 psi). Furthermore, whereas metals rarely elongate plastically to more than 100%, some highly elastic polymers may experience elongations to greater than 1000%.

In addition, the mechanical characteristics of polymers are much more sensitive to temperature changes near room temperature. Consider the stress–strain behavior for poly(methyl methacrylate) at several temperatures between 4°C and 60°C (40°F and 140°F) (Figure 7.24). Increasing the temperature produces (1) a decrease in elastic modulus, (2) a reduction in tensile strength, and (3) an enhancement of ductility—at 4°C (40°F) the material is totally brittle, whereas there is considerable plastic deformation at both 50°C and 60°C (122°F and 140°F).

The influence of strain rate on the mechanical behavior may also be important. In general, decreasing the rate of deformation has the same influence on the stress–strain characteristics as increasing the temperature: that is, the material becomes softer and more ductile.

![](_page_29_Figure_1.jpeg)

![](_page_29_Figure_2.jpeg)

**Figure 7.24** The influence of temperature on the stress–strain characteristics of poly(methyl methacrylate). (From T. S. Carswell and H. K. Nason, "Effect of Environmental Conditions on the Mechanical Properties of Organic Plastics," in *Symposium on Plastics,* American Society for Testing and Materials, Philadelphia, 1944. Copyright, ASTM, 1916 Race Street, Philadelphia, PA 19103. Reprinted with permission.)

**Figure 7.25** Schematic tensile stress–strain curve for a semicrystalline polymer. Specimen contours at several stages of deformation are included.

# **7.14 MACROSCOPIC DEFORMATION**

![](_page_29_Picture_6.jpeg)

 **:** VMSE Polymers Some aspects of the macroscopic deformation of semicrystalline polymers deserve our attention. The tensile stress–strain curve for a semicrystalline material that was initially undeformed is shown in Figure 7.25; also included in the figure are schematic representations of the specimen profiles at various stages of deformation. Both upper and lower yield points are evident on the curve. At the upper yield point, a small neck forms within the gauge section of the specimen. Within this neck, the chains become oriented (i.e., chain axes become aligned parallel to the elongation direction, a condition that is represented schematically in Figure 8.28*d*), which leads to localized strengthening. Consequently, there is a resistance to continued deformation at this point, and specimen elongation proceeds by the propagation of this neck region along the gauge length; the chain-orientation phenomenon (Figure 8.28*d*) accompanies this neck extension. This tensile behavior may be contrasted to that found for ductile metals (Section 7.6), in which once a neck has formed, all subsequent deformation is confined to within the neck region.

*Concept Check 7.3* When citing the ductility as percent elongation for semicrystalline polymers, it is not necessary to specify the specimen gauge length, as is the case with metals. Why is this so?

(The answer is available in *WileyPLUS*.)

**Figure 7.26** (*a*) Load versus time, where load is applied instantaneously at time *ta* and released at *tr*. For the load–time cycle in (*a*), the strain-versus-time responses are for totally elastic (*b*), viscoelastic (*c*), and viscous (*d*) behaviors.

![](_page_30_Figure_2.jpeg)

# **7.15 VISCOELASTIC DEFORMATION**

An amorphous polymer may behave like a glass at low temperatures, a rubbery solid at intermediate temperatures [above the glass transition temperature (Section 11.15)], and a viscous liquid as the temperature is raised further. For relatively small deformations, the mechanical behavior at low temperatures may be elastic—that is, in conformity to Hooke's law, *σ* = *Eε*. At the highest temperatures, viscous or liquid-like behavior prevails. For intermediate temperatures the polymer is a rubbery solid that exhibits the combined mechanical characteristics of these two extremes; the condition is termed **viscoelasticity.**

Elastic deformation is instantaneous, which means that total deformation (or strain) occurs the instant the stress is applied or released (i.e., the strain is independent of time). In addition, upon release of the external stress, the deformation is totally recovered the specimen assumes its original dimensions. This behavior is represented in Figure 7.26*b* as strain versus time for the instantaneous load–time curve, shown in Figure 7.26*a*.

By way of contrast, for totally viscous behavior, deformation or strain is not instantaneous; that is, in response to an applied stress, deformation is delayed or dependent on time. Also, this deformation is not reversible or completely recovered after the stress is released. This phenomenon is demonstrated in Figure 7.26*d*.

For the intermediate viscoelastic behavior, the imposition of a stress in the manner of Figure 7.26*a* results in an instantaneous elastic strain, which is followed by a viscous, time-dependent strain, a form of anelasticity (Section 7.4); this behavior is illustrated in Figure 7.26*c*.

A familiar example of these viscoelastic extremes is found in a silicone polymer that is sold as a novelty and known as Silly Putty. When rolled into a ball and dropped onto a horizontal surface, it bounces elastically—the rate of deformation during the bounce is very rapid. However, if pulled in tension with a gradually increasing applied stress, the material elongates or flows like a highly viscous liquid. For this and other viscoelastic materials, the rate of strain determines whether the deformation is elastic or viscous.

# **Viscoelastic Relaxation Modulus**

The viscoelastic behavior of polymeric materials is dependent on both time and temperature; several experimental techniques may be used to measure and quantify this

**viscoelasticity**

behavior. *Stress relaxation* measurements represent one possibility. With these tests, a specimen is initially strained rapidly in tension to a predetermined and relatively low strain level. The stress necessary to maintain this strain is measured as a function of time while temperature is held constant. Stress is found to decrease with time because of molecular relaxation processes that take place within the polymer. We may define a **relaxation modulus** *Er*(*t*), a time-dependent elastic modulus for viscoelastic polymers, as

### **relaxation modulus**

Relaxation modulus—ratio of time-dependent stress and constant strain value

$$
E_r(t) = \frac{\sigma(t)}{\varepsilon_0} \tag{7.23}
$$

where *σ*(*t*) is the measured time-dependent stress and *ε*0 is the strain level, which is maintained constant.

Furthermore, the magnitude of the relaxation modulus is a function of temperature; to more fully characterize the viscoelastic behavior of a polymer, isothermal stress relaxation measurements must be conducted over a range of temperatures. Figure 7.27 is a schematic log *Er*(*t*)-versus-log time plot for a polymer that exhibits viscoelastic behavior. Curves generated at a variety of temperatures are included. Key features of this plot are that (1) the magnitude of *Er*(*t*) decreases with time (corresponding to the decay of stress, Equation 7.23), and (2) the curves are displaced to lower *Er*(*t*) levels with increasing temperature.

To represent the influence of temperature, data points are taken at a specific time from the log *Er*(*t*)-versus-log time plot—for example, *t*1 in Figure 7.27—and then crossplotted as log *Er*(*t*1) versus temperature. Figure 7.28 is such a plot for an amorphous (atactic) polystyrene; in this case, *t*1 was arbitrarily taken 10 s after the load application. Several distinct regions may be noted on the curve shown in this figure. At the lowest temperatures, in the glassy region, the material is rigid and brittle, and the value of *Er*(10) is that of the elastic modulus, which initially is virtually independent of temperature. Over this temperature range, the strain–time characteristics are as represented in Figure 7.26*b*. On a molecular level, the long molecular chains are essentially frozen in position at these temperatures.

As the temperature is increased, *Er*(10) drops abruptly by about a factor of 10<sup>3</sup> within a 20°C (35°F) temperature span; this is sometimes called the *leathery*, or *glass transition region*, and the glass transition temperature (*Tg*; Section 11.16) lies near the upper temperature extremity; for polystyrene (Figure 7.28), *Tg* = 100°C (212°F). Within this temperature region, a polymer specimen will be leathery; that is, deformation will be time dependent and not totally recoverable on release of an applied load, characteristics that are depicted in Figure 7.26*c*.

Within the rubbery plateau temperature region (Figure 7.28), the material deforms in a rubbery manner; here, both elastic and viscous components are present, and deformation is easy to produce because the relaxation modulus is relatively low.

The final two high-temperature regions are rubbery flow and viscous flow. Upon heating through these temperatures, the material experiences a gradual transition to a soft, rubbery state and finally to a viscous liquid. In the rubbery flow region, the polymer is a very viscous liquid that exhibits both elastic and viscous flow components. Within the viscous flow region, the modulus decreases dramatically with increasing temperature; again, the strain–time behavior is as represented in Figure 7.26*d*. From a molecular standpoint, chain motion intensifies so greatly that for viscous flow, the chain segments experience vibration and rotational motion largely independently of one another. At these temperatures, any deformation is entirely viscous and essentially no elastic behavior occurs.

Normally, the deformation behavior of a viscous polymer is specified in terms of viscosity, a measure of a material's resistance to flow by shear forces. Viscosity is discussed for the inorganic glasses in Section 8.16.

![](_page_32_Figure_1.jpeg)

![](_page_32_Figure_2.jpeg)

![](_page_32_Figure_3.jpeg)

**Figure 7.28** Logarithm of the relaxation modulus versus temperature for amorphous polystyrene, showing the five different regions of viscoelastic behavior. (From A. V. Tobolsky, *Properties and Structures of Polymers.* Copyright © 1960 by John Wiley & Sons, New York. Reprinted by permission of

The rate of stress application also influences the viscoelastic characteristics. Increasing the loading rate has the same influence as lowering the temperature.

John Wiley & Sons, Inc.)

The log *Er*(10)-versus-temperature behavior for polystyrene materials having several molecular configurations is plotted in Figure 7.29. The curve for the amorphous material (curve *C*) is the same as in Figure 7.28. For a lightly crosslinked atactic polystyrene (curve *B*), the rubbery region forms a plateau that extends to the temperature at which the polymer decomposes; this material will not experience melting. For increased crosslinking, the magnitude of the plateau *Er*(10) value will also increase. Rubber or elastomeric materials display this type of behavior and are ordinarily used at temperatures within this plateau range.

Also shown in Figure 7.29 is the temperature dependence for an almost totally crystalline isotactic polystyrene (curve *A*). The decrease in *Er*(10) at *Tg* is much less pronounced than for the other polystyrene materials because only a small volume fraction of this material is amorphous and experiences the glass transition. Furthermore, the relaxation modulus is maintained at a relatively high value with increasing temperature until its melting temperature *Tm* is approached. From Figure 7.29, the melting temperature of this isotactic polystyrene is about 240°C (460°F).

![](_page_33_Figure_1.jpeg)

**Figure 7.29** Logarithm of the relaxation modulus versus temperature for crystalline isotactic (curve *A*), lightly crosslinked atactic (curve *B*), and amorphous (curve *C*) polystyrene.

(From A. V. Tobolsky, *Properties and Structures of Polymers.* Copyright © 1960 by John Wiley & Sons, New York. Reprinted by permission of John Wiley & Sons, Inc.)

# **Viscoelastic Creep**

Many polymeric materials are susceptible to time-dependent deformation when the stress level is maintained constant; such deformation is termed *viscoelastic creep.* This type of deformation may be significant even at room temperature and under modest stresses that lie below the yield strength of the material. For example, automobile tires may develop flat spots on their contact surfaces when the automobile is parked for prolonged time periods. Creep tests on polymers are conducted in the same manner as for metals (Chapter 9); that is, a stress (normally tensile) is applied instantaneously and is maintained at a constant level while strain is measured as a function of time. Furthermore, the tests are performed under isothermal conditions. Creep results are represented as a time-dependent *creep modulus Ec*(*t*), defined by<sup>15</sup>

$$
E_c(t) = \frac{\sigma_0}{\varepsilon(t)}\tag{7.24}
$$

where *σ*0 is the constant applied stress and *ε*(*t*) is the time-dependent strain. The creep modulus is also temperature sensitive and decreases with increasing temperature.

With regard to the influence of molecular structure on the creep characteristics, as a general rule the susceptibility to creep decreases [i.e., *Ec*(*t*) increases] as the degree of crystallinity increases.

*Concept Check 7.4* Cite the primary differences among elastic, anelastic, viscoelastic, and plastic deformation behaviors.

*Concept Check 7.5* An amorphous polystyrene that is deformed at 120°C will exhibit which of the behaviors shown in Figure 7.26?

(The answers are available in *WileyPLUS*.)

<sup>15</sup>*Creep compliance*, *Jc*(*t*), the reciprocal of the creep modulus, is also sometimes used in this context.

# Hardness and Other Mechanical Property Considerations

# **7.16 HARDNESS**

**hardness**

Another mechanical property that may be important to consider is **hardness,** which is a measure of a material's resistance to localized plastic deformation (e.g., a small dent or a scratch). Early hardness tests were based on natural minerals with a scale constructed solely on the ability of one material to scratch another that was softer. A qualitative and somewhat arbitrary hardness indexing scheme was devised, termed the Mohs scale, which ranged from 1 on the soft end for talc to 10 for diamond. Quantitative hardness techniques have been developed over the years in which a small indenter is forced into the surface of a material to be tested under controlled conditions of load and rate of application. The depth or size of the resulting indentation is measured and related to a hardness number; the softer the material, the larger and deeper the indentation, and the lower the hardness index number. Measured hardnesses are only relative (rather than absolute), and care should be exercised when comparing values determined by different techniques.

Hardness tests are performed more frequently than any other mechanical test for several reasons:

- **1.** They are simple and inexpensive—typically, no special specimen need be prepared, and the testing apparatus is relatively inexpensive.
- **2.** The test is nondestructive—the specimen is neither fractured nor excessively deformed; a small indentation is the only deformation.
- **3.** Other mechanical properties often may be estimated from hardness data, such as tensile strength (see Figure 7.31).

# **Rockwell Hardness Tests16**

The Rockwell tests constitute the most common method used to measure hardness because they are so simple to perform and require no special skills. Several different scales may be used from possible combinations of various indenters and different loads, a process that permits the testing of virtually all metal alloys (as well as some polymers). Indenters include spherical tungsten carbide balls having diameters of <sup>1</sup> 16, 1 8, 1 4, and <sup>1</sup> <sup>2</sup> in. (1.588, 3.175, 6.350, and 12.70 mm, respectively), as well as a conical diamond (Brale) indenter, which is used for the hardest materials.

With this system, a hardness number is determined by the difference in depth of penetration resulting from the application of an initial minor load followed by a larger major load; utilization of a minor load enhances test accuracy. On the basis of the magnitude of both major and minor loads, there are two types of tests: Rockwell and superficial Rockwell. For the Rockwell test, the minor load is 10 kg, whereas major loads are 60, 100, and 150 kg. Each scale is represented by a letter of the alphabet; several are listed with the corresponding indenter and load in Tables 7.5 and 7.6a. For superficial tests, 3 kg is the minor load; 15, 30, and 45 kg are the possible major load values. These scales are identified by a 15, 30, or 45 (according to load), followed by N, T, W, X, or Y, depending on the indenter. Superficial tests are frequently performed on thin specimens. Table 7.6b presents several superficial scales.

When specifying Rockwell and superficial hardnesses, both hardness number and scale symbol must be indicated. The scale is designated by the symbol HR followed

<sup>16</sup>ASTM Standard E18, "Standard Test Methods for Rockwell Hardness of Metallic Materials."

|                             | Formula for          | mber a<br>Nu<br>Hardness | d2]<br>−<br>√D2<br>2P<br>−<br>D<br>πD[<br>=<br>HB       | 1.854P/d21<br>=<br>HV      | HK = 14.2 P/l 2               |                                                                                                                                                       |
|-----------------------------|----------------------|--------------------------|---------------------------------------------------------|----------------------------|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
|                             |                      | Load                     | P                                                       | P                          | P                             | } Superficial Rockwell<br>} Rockwell<br>60 kg<br>100 kg<br>150 kg<br>15 kg<br>30 kg<br>45 kg                                                          |
|                             |                      | View<br>Top              | d                                                       | d1<br>d1                   | b<br>l                        |                                                                                                                                                       |
|                             | Shape of Indentation | View<br>Side             | D<br>d                                                  | 136°                       | t<br>b/t = 4.00<br>l/b = 7.11 | 120°                                                                                                                                                  |
| Hardness-Testing Techniques |                      | Indenter                 | tungsten carbide<br>m sphere<br>of steel or<br>m<br>10- | mid<br>mond<br>pyra<br>Dia | mid<br>mond<br>pyra<br>Dia    | tungsten carbide<br>- in.<br>mond cone;<br>1<br>2<br>,<br>meter<br>-<br>1<br>4<br>spheres<br>,<br>-<br>1<br>8<br>,<br>dia<br>-<br>16<br>Dia<br>1<br>{ |
| Table 7.5                   |                      | Test                     | Brinell                                                 | microhardness<br>Vickers   | microhardness<br>Knoop        | Rockwell and<br>superficial<br>Rockwell                                                                                                               |

*a*For the hardness formulas given, *P* (the applied load) is in kg and *D, d, d*1, and *l* are all in mm.

**Source:** Adapted from H. W. Hayden, W. G. Moffatt, and J. Wulff, *The Structure and Properties of Materials,* Vol. III, *Mechanical Behavior*. Copyright © 1965 by John Wiley & Sons, New York. Reprinted by permission of John Wiley & Sons, Inc.

# **• 251**

**Table 7.6a** Rockwell Hardness Scales

| Scale Symbol | Indenter          | Major Load (kg) |
|--------------|-------------------|-----------------|
| A            | Diamond           | 60              |
| B            | 1<br>16 -in. ball | 100             |
| C            | Diamond           | 150             |
| D            | Diamond           | 100             |
| E            | 1<br>8 -in. ball  | 100             |
| F            | 1<br>16 -in. ball | 60              |
| G            | 1<br>16 -in. ball | 150             |
| H            | 1<br>8 -in. ball  | 60              |
| K            | 1<br>8 -in. ball  | 150             |

### **Table 7.6b** Superficial Rockwell Hardness Scales

| Scale Symbol | Indenter          | Major Load (kg) |
|--------------|-------------------|-----------------|
| 15N          | Diamond           | 15              |
| 30N          | Diamond           | 30              |
| 45N          | Diamond           | 45              |
| 15T          | 1<br>16 -in. ball | 15              |
| 30T          | 1<br>16 -in. ball | 30              |
| 45T          | 1<br>16 -in. ball | 45              |
| 15W          | 1<br>8 -in. ball  | 15              |
| 30W          | 1<br>8 -in. ball  | 30              |
| 45W          | 1<br>8 -in. ball  | 45              |

by the appropriate scale identification.17 For example, 80 HRB represents a Rockwell hardness of 80 on the B scale, and 60 HR30W indicates a superficial hardness of 60 on the 30W scale.

For each scale, hardnesses may range up to 130; however, as hardness values rise above 100 or drop below 20 on any scale, they become inaccurate, and because the scales have some overlap, in such a situation it is best to utilize the next-harder or nextsofter scale.

Inaccuracies also result if the test specimen is too thin, if an indentation is made too near a specimen edge, or if two indentations are made too close to one another. Specimen thickness should be at least 10 times the indentation depth, whereas allowance should be made for at least three indentation diameters between the center of one indentation and the specimen edge, or to the center of a second indentation. Furthermore, testing of specimens stacked one on top of another is not recommended. Also, accuracy is dependent on the indentation being made into a smooth, flat surface.

The modern apparatus for making Rockwell hardness measurements is automated and very simple to use; hardness is read directly, and each measurement requires only a few seconds. The modern testing apparatus also permits a variation in the time of load application. This variable must also be considered in interpreting hardness data.

# **Brinell Hardness Tests<sup>18</sup>**

In Brinell tests, as in Rockwell measurements, a hard, spherical indenter is forced into the surface of the metal to be tested. The diameter of the hardened steel (or tungsten carbide) indenter is 10.00 mm (0.394 in.). Standard loads range between 500 and 3000 kg in 500-kg increments; during a test, the load is maintained constant for a specified time (between 10 and 30 s). Harder materials require greater applied loads. The Brinell hardness number, HB, is a function of both the magnitude of the load and the diameter of the resulting indentation (see Table 7.5).19 This diameter is measured with a special low-power microscope, using a scale that is etched on the eyepiece. The measured diameter is then converted to the appropriate HB number using a chart; only one scale is employed with this technique.

<sup>17</sup>Rockwell scales are also frequently designated by an R with the appropriate scale letter as a subscript; for example, RC denotes the Rockwell C scale.

<sup>18</sup>ASTM Standard E10, "Standard Test Method for Brinell Hardness of Metallic Materials."

<sup>19</sup>The Brinell hardness number is also represented by BHN.

Semiautomatic techniques for measuring Brinell hardness are available. These employ optical scanning systems consisting of a digital camera mounted on a flexible probe, which allows positioning of the camera over the indentation. Data from the camera are transferred to a computer that analyzes the indentation, determines its size, and then calculates the Brinell hardness number. For this technique, surface finish requirements are normally more stringent than those for manual measurements.

Maximum specimen thickness and indentation position (relative to specimen edges) as well as minimum indentation spacing requirements are the same as for Rockwell tests. In addition, a well-defined indentation is required; this necessitates a smooth, flat surface in which the indentation is made.

# **Knoop and Vickers Microindentation Hardness Tests<sup>20</sup>**

Two other hardness-testing techniques are the Knoop (pronounced *nпp*) and Vickers tests (sometimes also called *diamond pyramid*). For each test, a very small diamond indenter having pyramidal geometry is forced into the surface of the specimen. Applied loads are much smaller than for the Rockwell and Brinell tests, ranging between 1 and 1000 g. The resulting impression is observed under a microscope and measured; this measurement is then converted into a hardness number (Table 7.5). Careful specimen surface preparation (grinding and polishing) may be necessary to ensure a well-defined indentation that may be measured accurately. The Knoop and Vickers hardness numbers are designated by HK and HV, respectively,21 and hardness scales for both techniques are approximately equivalent. The Knoop and Vickers techniques are referred to as microindentation-testing methods on the basis of indenter size. Both are well suited for measuring the hardness of small, selected specimen regions; furthermore, the Knoop technique is used for testing brittle materials such as ceramics.

Modern microindentation hardness-testing equipment has been automated by coupling the indenter apparatus to an image analyzer that incorporates a computer and software package. The software controls important system functions including indent location, indent spacing, computation of hardness values, and plotting of data.

Other hardness-testing techniques are frequently employed but will not be discussed here; these include ultrasonic microhardness, dynamic (Scleroscope), durometer (for plastic and elastomeric materials), and scratch hardness tests. These are described in references provided at the end of the chapter.

# **Hardness Conversion**

The facility to convert the hardness measured on one scale to that of another is most desirable. However, because hardness is not a well-defined material property, and because of the experimental dissimilarities among the various techniques, a comprehensive conversion scheme has not been devised. Hardness conversion data have been determined experimentally and found to be dependent on material type and characteristics. The most reliable conversion data exist for steels, some of which are presented in Figure 7.30 for Knoop, Vickers, Brinell, and two Rockwell scales; the Mohs scale is also included. Detailed conversion tables for various other metals and alloys are contained in ASTM Standard E140, "Standard Hardness Conversion Tables for Metals." In light of the preceding discussion, care should be exercised in extrapolation of conversion data from one alloy system to another.

<sup>20</sup>ASTM Standard E92, "Standard Test Method for Vickers Hardness of Metallic Materials," and ASTM Standard E384, "Standard Test for Microindentation Hardness of Materials."

<sup>21</sup>Sometimes KHN and VHN are used to denote Knoop and Vickers hardness numbers, respectively.

![](_page_38_Figure_1.jpeg)

# **Correlation Between Hardness and Tensile Strength**

Both tensile strength and hardness are indicators of a metal's resistance to plastic deformation. Consequently, they are roughly proportional, as shown in Figure 7.31 for tensile strength as a function of the HB for cast iron, steel, and brass. The same proportionality relationship does not hold for all metals, as Figure 7.31 indicates. As a rule of thumb, for most steels, the HB and the tensile strength are related according to

For steel alloys, conversion of Brinell hardness to tensile strength

$$
TS(MPa) = 3.45 \times HB \tag{7.25a}
$$

$$
TS (psi) = 500 \times HB
$$
 (7.25b)

*Concept Check 7.6* Of those metals listed in Table 7.3, which is the hardest? Why? (The answer is available in *WileyPLUS*.)

![](_page_39_Figure_0.jpeg)

## **7.17 Hardness of Ceramic Materials • 255**

**Figure 7.31** Relationships among hardness and tensile strength for steel, brass, and cast iron. [Data taken from *Metals Handbook: Properties and Selection: Irons and Steels*, Vol. 1, 9th edition, B. Bardes (Editor), American Society for Metals, 1978, pp. 36 and 461; and *Metals Handbook: Properties and Selection: Nonferrous Alloys and Pure Metals*, Vol. 2, 9th edition, H. Baker (Managing Editor), American Society for Metals, 1979, p. 327.]

# **7.17 HARDNESS OF CERAMIC MATERIALS**

Accurate hardness measurements on ceramic materials are difficult to conduct inasmuch as ceramic materials are brittle and highly susceptible to cracking when indenters are forced into their surfaces; extensive crack formation leads to inaccurate readings. Spherical indenters (as with Rockwell and Brinell tests) are normally not used for ceramic materials because they produce severe cracking. Rather, hardnesses of this class of materials are measured using Vickers and Knoop techniques.22 The Vickers test is widely used for measuring hardnesses of ceramics; however, for very brittle ceramic materials, the Knoop test is often preferred. Furthermore, for both techniques, hardness decreases with increasing load (or indentation size) but ultimately reaches a constant plateau that is independent of load; the value of hardness at this plateau varies from ceramic to ceramic. An ideal hardness test would use a sufficiently large load that lies near this plateau yet be of magnitude that does not introduce excessive cracking.

Possibly the most desirable mechanical characteristic of ceramics is their hardness; the hardest known materials belong to this group. A number of different ceramic materials are listed according to Vickers hardness in Table 7.7.23 These materials are often utilized when an abrasive or grinding action is required (Section 13.8).

<sup>22</sup>ASTM Standard C1326, "Standard Test Method for Knoop Indentation Hardness of Advanced Ceramics," and Standard C1327, "Standard Test Method for Vickers Indentation Hardness of Advanced Ceramics."

<sup>23</sup>In the past the units for Vickers hardness were kg/mm2 ; in Table 7.7 we use the SI unit of GPa.

| Material                                  | Vickers Hardness<br>(GPa) | Knoop Hardness<br>(GPa) | Comments                                   |
|-------------------------------------------|---------------------------|-------------------------|--------------------------------------------|
| Diamond (carbon)                          | 130                       | 103                     | Single crystal, (100) face                 |
| Boron carbide (B4C)                       | 44.2                      | —                       | Polycrystalline, sintered                  |
| Aluminum oxide (Al2O3)                    | 26.5                      | —                       | Polycrystalline, sintered, 99.7% pure      |
| Silicon carbide (SiC)                     | 25.4                      | 19.8                    | Polycrystalline, reaction bonded, sintered |
| Tungsten carbide (WC)                     | 22.1                      | —                       | Fused                                      |
| Silicon nitride (Si3N4)                   | 16.0                      | 17.2                    | Polycrystalline, hot pressed               |
| Zirconia (ZrO2) (partially<br>stabilized) | 11.7                      | —                       | Polycrystalline, 9 mol% Y2O3               |
| Soda–lime glass                           | 6.1                       | —                       |                                            |

| Table 7.7 |  |  | Vickers (and Knoop) Hardnesses for Eight Ceramic Materials |
|-----------|--|--|------------------------------------------------------------|
|-----------|--|--|------------------------------------------------------------|

# **7.18 TEAR STRENGTH AND HARDNESS OF POLYMERS**

Mechanical properties that are sometimes influential in the suitability of a polymer for some particular application include tear resistance and hardness. The ability to resist tearing is an important property of some plastics, especially those used for thin films in packaging. *Tear strength,* the mechanical parameter measured, is the energy required to tear apart a cut specimen of a standard geometry. The magnitudes of tensile and tear strengths are related.

Polymers are softer than metals and ceramics, and most hardness tests are conducted by penetration techniques similar to those described for metals in Section 7.16. Rockwell tests are frequently used for polymers.24 Other indentation techniques employed are the Durometer and Barcol tests.<sup>25</sup>

This concludes our discussions on the mechanical properties of metals, ceramics, and polymers. By way of summary, Table 7.8 lists these properties, their symbols, and their characteristics (qualitatively).

| Table 7.8                           | Property              | Symbol                   | Measure of                                  |
|-------------------------------------|-----------------------|--------------------------|---------------------------------------------|
| Summary of<br>Mechanical Properties | Modulus of elasticity | E                        | Stiffness—resistance to elastic deformation |
|                                     | Yield strength        | σy                       | Resistance to plastic deformation           |
|                                     | Tensile strength      | TS                       | Maximum load-bearing capacity               |
|                                     | Ductility             | %EL, %RA                 | Degree of plastic deformation at fracture   |
|                                     | Modulus of resilience | Ur                       | Energy absorption—elastic deformation       |
|                                     | Toughness (static)    | —                        | Energy absorption—plastic deformation       |
|                                     | Hardness              | e.g., HB, HRC,<br>HV, HK | Resistance to localized surface deformation |
|                                     | Flexural strength     | σfs                      | Stress at fracture (ceramics)               |
|                                     | Relaxation modulus    | Er<br>(t)                | Time-dependent elastic modulus (polymers)   |
|                                     |                       |                          |                                             |

<sup>24</sup>ASTM Standard D785, "Standard Testing Method for Rockwell Hardness of Plastics and Electrical Insulating Materials."

<sup>25</sup>ASTM Standard D2240, "Standard Test Method for Rubber Property—Durometer Hardness," and ASTM Standard D2583, "Standard Test Method for Indentation Hardness of Rigid Plastics by Means of a Barcol Impressor."

# Property Variability and Design/Safety Factors

# **7.19 VARIABILITY OF MATERIAL PROPERTIES**

At this point, it is worthwhile to discuss an issue that sometimes proves troublesome to many engineering students—namely, that measured material properties are not exact quantities. That is, even if we have a most precise measuring apparatus and a highly controlled test procedure, there will always be some scatter or variability in the data that are collected from specimens of the same material. For example, consider a number of identical tensile samples that are prepared from a single bar of some metal alloy, which samples are subsequently stress–strain tested in the same apparatus. We would most likely observe that each resulting stress–strain plot is slightly different from the others. This would lead to a variety of modulus of elasticity, yield strength, and tensile strength values. A number of factors lead to uncertainties in measured data, including the test method, variations in specimen fabrication procedures, operator bias, and apparatus calibration. Furthermore, there might be inhomogeneities within the same lot of material and/or slight compositional and other differences from lot to lot. Of course, appropriate measures should be taken to minimize the possibility of measurement error and mitigate those factors that lead to data variability.

It should also be mentioned that scatter exists for other measured material properties, such as density, electrical conductivity, and coefficient of thermal expansion.

It is important for the design engineer to realize that scatter and variability of materials properties are inevitable and must be dealt with appropriately. On occasion, data must be subjected to statistical treatments and probabilities determined. For example, instead of asking, "What is the fracture strength of this alloy?" the engineer should become accustomed to asking, "What is the probability of failure of this alloy under these given circumstances?"

It is often desirable to specify a typical value and degree of dispersion (or scatter) for some measured property; this is commonly accomplished by taking the average and the standard deviation, respectively.

# **Computation of Average and Standard Deviation Values**

An *average value* is obtained by dividing the sum of all measured values by the number of measurements taken. In mathematical terms, the average *x* of some parameter *x* is

$$
\overline{x} = \frac{\sum_{i=1}^{n} x_i}{n} \tag{7.26}
$$

Computation of average value

> where *n* is the number of observations or measurements and *xi* is the value of a discrete measurement.

Furthermore, the standard deviation *s* is determined using the following expression:

$$
s = \left[\frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n - 1}\right]^{1/2}
$$
 (7.27)

where *xi* , *x*, and *n* were defined earlier. A large value of the standard deviation corresponds to a high degree of scatter.

Computation of standard deviation

# **EXAMPLE PROBLEM 7.6**

# **Average and Standard Deviation Computations**

The following tensile strengths were measured for four specimens of the same steel alloy:

| Sample Number | Tensile Strength (MPa) |
|---------------|------------------------|
| 1             | 520                    |
| 2             | 512                    |
| 3             | 515                    |
| 4             | 522                    |

**(a)** Compute the average tensile strength.

**(b)** Determine the standard deviation.

### *Solution*

**(a)** The average tensile strength (*TS*) is computed using Equation 7.26 with *n* = 4:

$$
\overline{TS} = \frac{\sum_{i=1}^{4} (TS)_i}{4}
$$
$$
= \frac{520 + 512 + 515 + 522}{4}
$$
$$
= 517 \text{ MPa}
$$

**(b)** For the standard deviation, using Equation 7.27, we obtain

$$
s = \left[\frac{\sum_{i=1}^{4} \left\{ (TS)_i - \overline{TS} \right\}^2}{4 - 1} \right]^{1/2}
$$
  
= 
$$
\left[ \frac{(520 - 517)^2 + (512 - 517)^2 + (515 - 517)^2 + (522 - 517)^2}{4 - 1} \right]^{1/2}
$$
  
= 4.6 MPa

 Figure 7.32 presents the tensile strength by specimen number for this example problem and also how the data may be represented in graphical form. The tensile strength data point (Figure 7.32*b*) corresponds to the average value *TS* and scatter is depicted by error bars (short horizontal lines) situated above and below the data point symbol and connected to this symbol by vertical lines. The upper error bar is positioned at a value of the average value plus the standard deviation (*TS* + *s*), and the lower error bar corresponds to the average minus the standard deviation (*TS* − *s*).

![](_page_43_Figure_1.jpeg)

**Figure 7.32** (*a*) Tensile strength data associated with Example Problem 7.6. (*b*) The manner in which these data could be plotted. The data point corresponds to the average value of the tensile strength (*TS*); error bars that indicate the degree of scatter correspond to the average value plus and minus the standard deviation (*TS* ± *s*).

# **7.20 DESIGN/SAFETY FACTORS**

There will always be uncertainties in characterizing the magnitude of applied loads and their associated stress levels for in-service applications; typically, load calculations are only approximate. Furthermore, as noted in Section 7.19, virtually all engineering materials exhibit a variability in their measured mechanical properties, have imperfections that were introduced during manufacture, and, in some instances, will have sustained damage during service. Consequently, design approaches must be employed to protect against unanticipated failure. During the 20th century, the protocol was to reduce the applied stress by a *design safety factor*. Although this is still an acceptable procedure for some structural applications, it does not provide adequate safety for critical applications such as those found in aircraft and bridge structural components. The current approach for these critical structural applications is to utilize materials that have adequate toughnesses and also offer redundancy in the structural design (i.e., excess or duplicate structures), provided there are regular inspections to detect the presence of flaws and, when necessary, safely remove or repair components. (These topics are discussed in Chapter 9, *Failure*—specifically Section 9.5.)

**design stress**

For less critical static situations and when tough materials are used, a **design stress**, 
$$
\sigma_d
$$
, is taken as the calculated stress level  $\sigma_c$  (on the basis of the estimated maximum load) multiplied by a *design factor*, *N'*; that is,

$$
\sigma_d = N' \sigma_c \tag{7.28}
$$

where *N*′ is greater than unity. Thus, the material to be used for the particular application is chosen so as to have a yield strength at least as high as this value of *σd*.

**safe stress**

Alternatively, a **safe stress** or *working stress, σw*, is used instead of design stress. This safe stress is based on the yield strength of the material and is defined as the yield strength divided by a *factor of safety, N*, or

Computation of safe (or working) stress

$$
\sigma_w = \frac{\sigma_y}{N} \tag{7.29}
$$

Utilization of design stress (Equation 7.28) is usually preferred because it is based on the anticipated maximum applied stress instead of the yield strength of the material; normally there is a greater uncertainty in estimating this stress level than in the specification of the yield strength. However, in the discussion of this text, we are concerned with factors that influence the yield strengths of metal alloys and not in the determination of applied stresses; therefore, the succeeding discussion deals with working stresses and factors of safety.

The choice of an appropriate value of *N* is necessary. If *N* is too large, then component overdesign will result; that is, either too much material or an alloy having a higher-than-necessary strength will be used. Values normally range between 1.2 and 4.0. Selection of *N* will depend on a number of factors, including economics, previous experience, the accuracy with which mechanical forces and material properties may be determined, and, most important, the consequences of failure in terms of loss of life and/ or property damage. Because large *N* values lead to increased material cost and weight, structural designers are moving toward using tougher materials with redundant (and inspectable) designs, where economically feasible.

# **DESIGN EXAMPLE 7.1**

### **Specification of Support Post Diameter**

A tensile-testing apparatus is to be constructed that must withstand a maximum load of 220,000 N (50,000 lbf). The design calls for two cylindrical support posts, each of which is to support half of the maximum load. Furthermore, plain-carbon (1045) steel ground and polished shafting rounds are to be used; the minimum yield and tensile strengths of this alloy are 310 MPa (45,000 psi) and 565 MPa (82,000 psi), respectively. Specify a suitable diameter for these support posts.

## *Solution*

The first step in this design process is to decide on a factor of safety, *N*, which then allows determination of a working stress according to Equation 7.29. In addition, to ensure that the apparatus will be safe to operate, we also want to minimize any elastic deflection of the rods during testing; therefore, a relatively conservative factor of safety is to be used, say *N* = 5. Thus, the working stress *σw* is just

$$
\sigma_w = \frac{\sigma_y}{N}
$$
  
= 
$$
\frac{310 \text{ MPa}}{5} = 62 \text{ MPa} (9000 \text{ psi})
$$

From the definition of stress, Equation 7.1,

$$
A_0 = \left(\frac{d}{2}\right)^2 \pi = \frac{F}{\sigma_w}
$$

where *d* is the rod diameter and *F* is the applied force; furthermore, each of the two rods must support half of the total force, or 110,000 N (25,000 psi). Solving for *d* leads to

$$
d = 2\sqrt{\frac{F}{\pi \sigma_w}}
$$
  
=  $2\sqrt{\frac{110,000 \text{ N}}{\pi (62 \times 10^6 \text{ N/m}^2)}}$   
= 4.75 × 10<sup>-2</sup> m = 47.5 mm (1.87 in.)

Therefore, the diameter of each of the two rods should be 47.5 mm, or 1.87 in.

# **DESIGN EXAMPLE 7.2**

### **Materials Specification for a Pressurized Cylindrical Tube**

**(a)** Consider a thin-walled cylindrical tube having a radius of 50 mm and wall thickness 2 mm that is to be used to transport pressurized gas. If inside and outside tube pressures are 20 and 0.5 atm (2.027 and 0.057 MPa), respectively, which of the metals and alloys listed in Table 7.9 are suitable candidates? Assume a factor of safety of 4.0.

For a thin-walled cylinder, the circumferential (or "hoop") stress (*σ*) depends on pressure difference (Δ*p*), cylinder radius (*ri* ), and tube wall thickness (*t*) as follows:

$$
\sigma = \frac{r_i \Delta p}{t} \tag{7.30}
$$

These parameters are noted on the schematic sketch of a cylinder presented in Figure 7.33.

**(b)** Determine which of the alloys that satisfy the criterion of part (**a**) can be used to produce a tube with the lowest cost.

### *Solution*

**(a)** In order for this tube to transport the gas in a satisfactory and safe manner, we want to minimize the likelihood of plastic deformation. To accomplish this, we replace the circumferential stress in Equation 7.30 with the yield strength of the tube material divided by the factor of safety, *N*—that is,

$$
\frac{\sigma_y}{N} = \frac{r_i \Delta p}{t}
$$

And solving this expression for *σy* leads to

$$
\sigma_{y} = \frac{Nr_i \Delta p}{t} \tag{7.31}
$$

**Table 7.9** Yield Strengths, Densities, and Costs per Unit Mass for Metal Alloys That Are the Subjects of Design Example 7.2

| Alloy     | Yield Strength,<br>(MPa)<br>𝝈y | Density,<br>𝝆 (g/cm3<br>) | Unit Mass Cost, c<br>(\$US/kg) |
|-----------|--------------------------------|---------------------------|--------------------------------|
| Steel     | 325                            | 7.8                       | 1.25                           |
| Aluminum  | 125                            | 2.7                       | 3.50                           |
| Copper    | 225                            | 8.9                       | 6.25                           |
| Brass     | 275                            | 8.5                       | 7.50                           |
| Magnesium | 175                            | 1.8                       | 14.00                          |
| Titanium  | 700                            | 4.5                       | 40.00                          |

We now incorporate into this equation values of *N*, *ri* , Δ*p*, and *t* given in the problem statement and solve for *σy*. Alloys in Table 7.9 that have yield strengths greater than this value are suitable candidates for the tubing. Therefore,

$$
\sigma_y = \frac{(4.0)(50 \times 10^{-3} \text{ m})(2.027 \text{ MPa} - 0.057 \text{ MPa})}{(2 \times 10^{-3} \text{ m})} = 197 \text{ MPa}
$$

Four of the six alloys in Table 7.9 have yield strengths greater than 197 MPa and satisfy the design criterion for this tube that is, steel, copper, brass, and titanium.

**(b)** To determine the tube cost for each alloy, it is fi rst necessary to compute the tube volume *V*, which is equal to the product of cross-sectional area *A* and length *L*—that is,

$$
V = AL
$$
  
=  $\pi (r_o^2 - r_i^2)L$  (7.32)

Here, *ro* and *ri* are, respectively, the tube outside and inside radii. From Figure 7.33, it may be observed that *ro* = *ri* + *t*, or that

![](_page_46_Figure_7.jpeg)

**Figure 7.33** Schematic representation of a cylindrical tube, the subject of Design Example 7.2.

$$
V = \pi (r_o^2 - r_i^2)L = \pi [(r_i + t)^2 - r_i^2]L
$$
  
=  $\pi (r_i^2 + 2r_i t + t^2 - r_i^2)L$   
=  $\pi (2r_i t + t^2)L$  (7.33)

Because the tube length *L* has not been specifi ed, for the sake of convenience, we assume a value of 1.0 m. Incorporating values for *ri* and *t*, provided in the problem statement leads to the following value for *V*:

$$
V = \pi [(2)(50 \times 10^{-3} \text{ m})(2 \times 10^{-3} \text{ m}) + (2 \times 10^{-3} \text{ m})^2](1 \text{ m})
$$
  
= 6.28 × 10<sup>-4</sup> m<sup>3</sup> = 628 cm<sup>3</sup>

Next, it is necessary to determine the mass of each alloy (in kilograms) by multiplying this value of *V* by the alloy's density, *ρ* (Table 7.9) and then dividing by 1000, which is a unit-conversion factor because 1000 mm = 1 m. Finally, cost of each alloy (in \$US) is computed from the product of this mass and the unit mass cost (*c*) (Table 7.9). This procedure is expressed in equation form as follows:

$$
Cost = \left(\frac{V\rho}{1000}\right)(\bar{c})\tag{7.34}
$$

For example, for steel,

Cost (steel) = 
$$
\left[\frac{(628 \text{ cm}^3)(7.8 \text{ g/cm}^3)}{(1000 \text{ g/kg})}\right](1.25 \text{ $US/kg$}) = $6.10
$$

Cost values for steel and the other three alloys, as determined in the same manner, are tabulated below.

| Alloy    | Cost (\$US) |
|----------|-------------|
| Steel    | 6.10        |
| Copper   | 35.00       |
| Brass    | 40.00       |
| Titanium | 113.00      |

Hence, steel is by far the least expensive alloy to use for the pressurized tube.

![](_page_46_Picture_19.jpeg)

| SUMMARY                            |                                                                                                                                                                                                                                                                                                                                       |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Introduction                       | • Three factors that should be considered in designing laboratory tests to assess the<br>mechanical characteristics of materials for service use are the nature of the applied<br>load (i.e., tension, compression, shear), load duration, and environmental conditions.                                                              |
| Concepts of Stress<br>and Strain   | • For loading in tension and compression:<br>Engineering stress σ is defined as the instantaneous load divided by the original<br>specimen cross-sectional area (Equation 7.1).<br>Engineering strain ε is expressed as the change in length (in the direction of load<br>application) divided by the original length (Equation 7.2). |
| Stress–Strain<br>Behavior          | • A material that is stressed first undergoes elastic, or nonpermanent, deformation.<br>• When most materials are deformed elastically, stress and strain are proportional—<br>that is, a plot of stress versus strain is linear.                                                                                                     |
|                                    | • For tensile and compressive loading, the slope of the linear elastic region of the<br>stress–strain curve is the modulus of elasticity (E), per Hooke's law (Equation 7.5).<br>• For a material that exhibits nonlinear elastic behavior, tangent and secant moduli are                                                             |
|                                    | used.<br>• On an atomic level, elastic deformation of a material corresponds to the stretching of<br>interatomic bonds and corresponding slight atomic displacements.                                                                                                                                                                 |
|                                    | • For shear elastic deformations, shear stress (τ) and shear strain (γ) are propor<br>tional to one another (Equation 7.7). The constant of proportionality is the shear<br>modulus (G).                                                                                                                                              |
|                                    | • Elastic deformation that is dependent on time is termed anelastic.                                                                                                                                                                                                                                                                  |
| Elastic Properties of<br>Materials | • Another elastic parameter, Poisson's ratio (v), represents the negative ratio of trans<br>verse and longitudinal strains (εx and εz, respectively)—Equation 7.8. Typical values<br>of ν for metals lie within the range of about 0.25 to 0.35.                                                                                      |
|                                    | • For an isotropic material, shear and elastic moduli and Poisson's ratio are related<br>according to Equation 7.9.                                                                                                                                                                                                                   |
| Tensile Properties                 | • The phenomenon of yielding occurs at the onset of plastic or permanent deformation.                                                                                                                                                                                                                                                 |
| (Metals)                           | • Yield strength is indicative of the stress at which plastic deformation begins. For most<br>materials, yield strength is determined from a stress–strain plot using the 0.002 strain<br>offset technique.                                                                                                                           |
|                                    | • Tensile strength is taken as the stress level at the maximum point on the engineering<br>stress–strain curve; it represents the maximum tensile stress that can be sustained by<br>a specimen.                                                                                                                                      |
|                                    | • For most metallic materials, at the maxima on their stress–strain curves, a small<br>constriction or "neck" begins to form at some point on the deforming specimen. All<br>subsequent deformation ensues by the narrowing of this neck region, at which point<br>fracture ultimately occurs.                                        |
|                                    | • Ductility is a measure of the degree to which a material plastically deforms by the<br>time fracture occurs.                                                                                                                                                                                                                        |
|                                    | • Quantitatively, ductility is measured in terms of percents elongation and reduction in                                                                                                                                                                                                                                              |
|                                    | area.<br>Percent elongation (%EL) is a measure of the plastic strain at fracture<br>(Equation 7.11).                                                                                                                                                                                                                                  |
|                                    | Percent reduction in area (%RA) may be calculated according to Equation 7.12.                                                                                                                                                                                                                                                         |

- Yield and tensile strengths and ductility are sensitive to any prior deformation, the presence of impurities, and/or any heat treatment. Modulus of elasticity is relatively insensitive to these conditions.
- With increasing temperature, values of elastic modulus and tensile and yield strengths decrease, whereas the ductility increases.
- *Modulus of resilience* is the strain energy per unit volume of material required to stress a material to the point of yielding—or the area under the elastic portion of the engineering stress–strain curve. For a metal that displays linear-elastic behavior, its value may be determined using Equation 7.14.
- A measure of toughness is the energy absorbed during the fracture of a material, as measured by the area under the entire engineering stress–strain curve. Ductile metals are normally tougher than brittle ones.
- *True stress* (*σT*) is defined as the instantaneous applied load divided by the instantaneous cross-sectional area (Equation 7.15). True Stress and Strain
  - *True strain* (*εT*) is equal to the natural logarithm of the ratio of instantaneous and original specimen lengths per Equation 7.16.
  - For some metals, from the onset of plastic deformation to the onset of necking, true stress and true strain are related by Equation 7.19.
- For a specimen that has been plastically deformed, elastic strain recovery occurs if the load is released. This phenomenon is illustrated by the stress–strain plot of Figure 7.17. Elastic Recovery after Plastic Deformation

• The stress–strain behaviors and fracture strengths of ceramic materials are determined using transverse bending tests. Flexural Strength (Ceramics)

- Flexural strengths as measured from three-point transverse bending tests may be determined for rectangular and circular cross sections using, respectively, Equations 7.20a and 7.20b.
- Many ceramic bodies contain residual porosity, which is deleterious to both their moduli of elasticity and fracture strengths. Influence of Porosity (Ceramics)
  - Modulus of elasticity depends on and decreases with volume fraction porosity according to Equation 7.21.
  - The decrease of flexural strength with volume fraction porosity is described by Equation 7.22.

Stress–Strain Behavior (Polymers)

- On the basis of stress–strain behavior, polymers fall within three general classifications (Figure 7.22): brittle (curve *A*), plastic (curve *B*), and highly elastic (curve *C*).
- Polymers are neither as strong nor as stiff as metals. However, their high flexibilities, low densities, and resistance to corrosion make them the materials of choice for many applications.
- The mechanical properties of polymers are sensitive to changes in temperature and strain rate. With either rising temperature or decreasing strain rate, modulus of elasticity diminishes, tensile strength decreases, and ductility increases.

## Viscoelastic Deformation (Polymers)

- Viscoelastic mechanical behavior, intermediate between totally elastic and totally viscous, is displayed by a number of polymeric materials.
- This behavior is characterized by the relaxation modulus, a time-dependent modulus of elasticity.

- The magnitude of the relaxation modulus is very sensitive to temperature. Glassy, leathery, rubbery, and viscous flow regions may be identified on a plot of logarithm of relaxation modulus versus temperature (Figure 7.28).
- The logarithm of relaxation modulus versus temperature behavior depends on molecular configuration—degree of crystallinity, presence of crosslinking, and so on (Figure 7.29).
- Hardness is a measure of a material's resistance to localized plastic deformation. Hardness
  - The two most common hardness testing techniques are the Rockwell and Brinell tests. Several scales are available for the Rockwell test; for the Brinell test there is a single scale.

Brinell hardness is determined from indentation size; the Rockwell test is based on the difference in indentation depth from the imposition of minor and major loads.

- The two microindentation hardness-testing techniques are the Knoop and Vickers tests. Small indenters and relatively light loads are employed for these two techniques. They are used to measure the hardnesses of brittle materials (such as ceramics) and also of very small specimen regions.
- For some metals, a plot of hardness versus tensile strength is linear—that is, these two parameters are proportional to one another.
- The hardness of ceramic materials is difficult to measure because of their brittleness and susceptibility to cracking when indented. Hardness of Ceramics
  - Microindentation Knoop and Vickers techniques are normally used.
  - The hardest known materials are ceramics, which characteristic makes them especially attractive for use as abrasives (Section 13.8).

### • Five factors that can lead to scatter in measured material properties are the following: test method, variations in specimen fabrication procedure, operator bias, apparatus calibration, and inhomogeneities and/or compositional variations from sample to sample. Variability of Material Properties

- A typical material property is often specified in terms of an average value (*x*), whereas magnitude of scatter may be expressed as a standard deviation (*s*). Equations 7.26 and 7.27, respectively, are used to calculate values for these parameters.
- As a result of uncertainties in both measured mechanical properties and in-service applied stresses, design or safe stresses are normally utilized for design purposes. For ductile materials, safe (or working) stress *σw* is dependent on yield strength and factor of safety as described in Equation 7.29. Design/Safety Factors

| Equation<br>Number | Equation                                    | Solving For        | Page<br>Number |
|--------------------|---------------------------------------------|--------------------|----------------|
| 7.1                | F<br>σ =<br>A0                              | Engineering stress | 220            |
| 7.2                | −<br>Δl<br>li<br>l0<br>ε =<br>=<br>l0<br>l0 | Engineering strain | 220            |

# **Equation Summary**

(*continued*)

| Equation<br>Number | Equation                                           | Solving For                                                                | Page<br>Number |
|--------------------|----------------------------------------------------|----------------------------------------------------------------------------|----------------|
| 7.5                | σ =<br>Eε                                          | Modulus of elasticity (Hooke's law)                                        | 222            |
| 7.8                | −εy<br>−εx<br>ν =<br>=<br>εz<br>εz                 | Poisson's ratio                                                            | 226            |
| 7.11               | −<br>lf<br>l0<br>%EL =<br>×<br>100<br>(<br>)<br>l0 | Ductility, percent elongation                                              | 232            |
| 7.12               | −<br>A0<br>Af<br>%RA =<br>×<br>100<br>(<br>)<br>A0 | Ductility, percent reduction in area                                       | 233            |
| 7.15               | F<br>=<br>σT<br>Ai                                 | True stress                                                                | 236            |
| 7.16               | li<br>=<br>εT<br>ln<br>l0                          | True strain                                                                | 237            |
| 7.19               | =<br>Kε n<br>σT<br>T                               | True stress and true strain (plastic<br>region to point of necking)        | 237            |
| 7.20a              | 3FfL<br>=<br>σfs<br>2bd2                           | Flexural strength for a bar specimen<br>having a rectangular cross section | 241            |

Flexural strength for a bar specimen 241 having a circular cross section

7.22 *σfs* = *σ*0 exp (−*nP*) Flexural strength of a porous ceramic 243

7.25b *TS* (psi) = 500 × HB 254

# **266 • Chapter 7 / Mechanical Properties**

7.20b *<sup>σ</sup>fs* <sup>=</sup> *FfL*

7.23 *Er* (*t*) <sup>=</sup> *<sup>σ</sup>*(*t*)

7.29 *σ<sup>w</sup>* <sup>=</sup> *<sup>σ</sup><sup>y</sup>*

7.21 *E* = *E*<sup>0</sup> (1 − 1.9*P* + 0.9*P*<sup>2</sup>

7.25a *TS* (MPa) = 3.45 × HB

# **List of Symbols**

*πR*<sup>3</sup>

*ε*0

| Symbol | Meaning                                                                     |  |
|--------|-----------------------------------------------------------------------------|--|
| A0     | Specimen cross-sectional area prior to load application                     |  |
| Af     | Specimen cross-sectional area at the point of fracture                      |  |
| Ai     | Instantaneous specimen cross-sectional area during load application         |  |
| b, d   | Width and height of flexural specimen having a rectangular cross<br>section |  |
| E      | Modulus of elasticity (tension and compression)                             |  |
| E0     | Modulus of elasticity of a nonporous ceramic                                |  |
| F      | Applied force                                                               |  |
| Ff     | Applied load at fracture                                                    |  |

) Elastic modulus of a porous ceramic 242

Relaxation modulus 247

Tensile strength from Brinell hardness

*<sup>N</sup>* Safe (working) stress 260

(*continued*)

254

| Symbol | Meaning                                                                                              |
|--------|------------------------------------------------------------------------------------------------------|
| HB     | Brinell hardness                                                                                     |
| K      | Material constant                                                                                    |
| L      | Distance between support points for flexural specimen                                                |
| l0     | Specimen length prior to load application                                                            |
| lf     | Specimen fracture length                                                                             |
| li     | Instantaneous specimen length during load application                                                |
| N      | Factor of safety                                                                                     |
| n      | Strain-hardening exponent                                                                            |
| n      | Experimental constant                                                                                |
| P      | Volume fraction porosity                                                                             |
| TS     | Tensile strength                                                                                     |
| ε0     | Strain level—maintained constant during viscoelastic relaxation<br>modulus tests                     |
| εx, εy | Strain values perpendicular to the direction of load application<br>(i.e., the transverse direction) |
| εz     | Strain value in the direction of load application (i.e., the longitudinal<br>direction)              |
| σ0     | Flexural strength of a nonporous ceramic                                                             |
| σ(t)   | Time-dependent stress—measured during viscoelastic relaxation<br>modulus tests                       |
| σy     | Yield strength                                                                                       |

# **Important Terms and Concepts**

anelasticity design stress ductility elastic deformation elastic recovery elastomer engineering strain engineering stress flexural strength

hardness modulus of elasticity plastic deformation Poisson's ratio proportional limit relaxation modulus resilience safe stress

shear tensile strength toughness true strain true stress viscoelasticity yielding yield strength

# **REFERENCES**

- *ASM Handbook*, Vol. 8, *Mechanical Testing and Evaluation*, ASM International, Materials Park, OH, 2000.
- Billmeyer, F. W., Jr., *Textbook of Polymer Science,* 3rd edition, Wiley-Interscience, New York, 1984.
- Bowman, K., *Mechanical Behavior of Materials*, Wiley, Hoboken, NJ, 2004.
- Boyer, H. E. (Editor), *Atlas of Stress–Strain Curves*, 2nd edition, ASM International, Materials Park, OH, 2002.
- Brazel, C. S., and S. L. Rosen, *Fundamental Principles of Polymeric Materials*, 3rd edition, Wiley, Hoboken, NJ, 2012.
- Chandler, H. (Editor), *Hardness Testing*, 2nd edition, ASM International, Materials Park, OH, 2000.
- Courtney, T. H., *Mechanical Behavior of Materials*, 2nd edition, Waveland Press, Long Grove, IL, 2005.

- Davis, J. R. (Editor), *Tensile Testing*, 2nd edition, ASM International, Materials Park, OH, 2004.
- Dieter, G. E., *Mechanical Metallurgy*, 3rd edition, McGraw-Hill, New York, 1986.
- Dowling, N. E., *Mechanical Behavior of Materials,* 4th edition, Prentice Hall (Pearson Education), Upper Saddle River, NJ, 2013.
- *Engineered Materials Handbook,* Vol. 2, *Engineering Plastics,*  ASM International, Metals Park, OH, 1988.
- *Engineered Materials Handbook,* Vol. 4, *Ceramics and Glasses,*  ASM International, Materials Park, OH, 1991.
- Green, D. J., *An Introduction to the Mechanical Properties of Ceramics,* Cambridge University Press, Cambridge, 1998.

- Hosford, W. F., *Mechanical Behavior of Materials,* 2nd edition, Cambridge University Press, New York, 2010.
- Kingery, W. D., H. K. Bowen, and D. R. Uhlmann, *Introduction to Ceramics,* 2nd edition, Wiley, New York, 1976. Chapter 15.
- Lakes, R., *Viscoelastic Materials*, Cambridge University Press, New York, 2009.
- Landel, R. F. (Editor), *Mechanical Properties of Polymers and Composites,* 2nd edition, Marcel Dekker, New York, 1994.
- Meyers, M. A., and K. K. Chawla, *Mechanical Behavior of Materials,* 2nd edition, Cambridge University Press, Cambridge, 2009.

# **QUESTIONS AND PROBLEMS**

### *Concepts of Stress and Strain*

- **7.1** Using mechanics-of-materials principles (i.e., equations of mechanical equilibrium applied to a free-body diagram), derive Equations 7.4a and 7.4b.
- **7.2 (a)** Equations 7.4a and 7.4b are expressions for normal (*σ*′) and shear (*τ*′) stresses, respectively, as a function of the applied tensile stress (*σ*) and the inclination angle of the plane on which these stresses are taken (*θ* of Figure 7.4). Make a plot showing the orientation parameters of these expressions (i.e., cos2 *θ* and sin *θ* cos *θ*) versus *θ*.

 **(b)** From this plot, at what angle of inclination is the normal stress a maximum?

 **(c)** At what inclination angle is the shear stress a maximum?

### *Stress–Strain Behavior*

- **7.3** A specimen of copper having a rectangular cross section 15.2 mm × 19.1 mm (0.60 in. × 0.75 in.) is pulled in tension with 44,500 N (10,000 lbf) force, producing only elastic deformation. Calculate the resulting strain.
- **7.4** A cylindrical specimen of a nickel alloy having an elastic modulus of 207 GPa (30 × 10<sup>6</sup> psi) and an original diameter of 10.2 mm (0.40 in.) experiences only elastic deformation when a tensile load of 8900 N (2000 lbf) is applied. Compute the maximum length of the specimen before deformation if the maximum allowable elongation is 0.25 mm (0.010 in.).
- **7.5** An aluminum bar 125 mm (5.0 in.) long and having a square cross section 16.5 mm (0.65 in.) on an edge is pulled in tension with a load of 66,700 N (15,000 lbf) and experiences an elongation of 0.43 mm (1.7 × 10<sup>−</sup><sup>2</sup> in.). Assuming that the deformation is entirely elastic, calculate the modulus of elasticity of the aluminum.

- Richerson, D. W., *Modern Ceramic Engineering,* 3rd edition, CRC Press, Boca Raton, FL, 2006.
- Tobolsky, A. V., *Properties and Structures of Polymers,* Wiley, New York, 1960. Advanced treatment.
- Wachtman, J. B., W. R. Cannon, and M. J. Matthewson, *Mechanical Properties of Ceramics,* 2nd edition, Wiley, Hoboken, NJ, 2009.
- Ward, I. M., and J. Sweeney, *Mechanical Properties of Solid Polymers,* 3rd edition, Wiley, Chichester, UK, 2013.

- **7.6** Consider a cylindrical nickel wire 2.0 mm (0.08 in.) in diameter and 3 × 104 mm (1200 in.) long. Calculate its elongation when a load of 300 N (67 lbf) is applied. Assume that the deformation is totally elastic.
- **7.7** For a brass alloy, the stress at which plastic deformation begins is 345 MPa (50,000 psi), and the modulus of elasticity is 103 GPa (15.0 × 106 psi).

 **(a)** What is the maximum load that can be applied to a specimen with a cross-sectional area of 130 mm2 (0.2 in.2 ) without plastic deformation?

 **(b)** If the original specimen length is 76 mm (3.0 in.), what is the maximum length to which it can be stretched without causing plastic deformation?

- **7.8** A cylindrical rod of steel (*E* = 207 GPa, 30 × 10<sup>6</sup> psi) having a yield strength of 310 MPa (45,000 psi) is to be subjected to a load of 11,100 N (2500 lbf). If the length of the rod is 500 mm (20.0 in.), what must be the diameter to allow an elongation of 0.38 mm (0.015 in.)?
- **7.9** Compute the elastic moduli for the following
- metal alloys, whose stress–strain behaviors may be observed in the Tensile Tests module of *Virtual Materials Science and Engineering (VMSE)*  (which is found in *WileyPLUS*)*:* **(a)** titanium, **(b)**  tempered steel, **(c)** aluminum, and **(d)** carbon steel. How do these values compare with those presented in Table 7.1 for the same metals?
- **7.10** Consider a cylindrical specimen of a steel alloy (Figure 7.34) 8.5 mm (0.33 in.) in diameter and 80 mm (3.15 in.) long that is pulled in tension. Determine its elongation when a load of 65,250 N (14,500 lbf) is applied.
- **7.11** Figure 7.35 shows the tensile engineering stress– strain curve in the elastic region for a gray cast iron. Determine **(a)** the tangent modulus at 25 MPa (3625 psi) and **(b)** the secant modulus taken to 35 MPa (5000 psi).

![](_page_53_Figure_1.jpeg)

**Figure 7.34** Tensile stress-strain behavior for an alloy steel.

**7.12** As noted in Section 3.19, for single crystals of some substances, the physical properties are anisotropic—that is, they depend on crystallographic direction. One such property is the modulus of elasticity. For cubic single crystals, the modulus of elasticity in a general [*uvw*] direction, *Euvw*, is described by the relationship

$$
\frac{1}{E_{uvw}} = \frac{1}{E_{\langle 100 \rangle}} - 3\left(\frac{1}{E_{\langle 100 \rangle}} - \frac{1}{E_{\langle 111 \rangle}}\right)
$$
$$
(\alpha^2 \beta^2 + \beta^2 \gamma^2 + \gamma^2 \alpha^2) \tag{7.35}
$$

 where *E*〈100〉 and *E*〈111〉 are the moduli of elasticity in the [100] and [111] directions, respectively; , *β*, and *γ* are the cosines of the angles between [*uvw*] and the respective [100], [010], and [001] directions. Verify that the *E*〈110〉 values for aluminum, copper, and iron in Table 3.8 are correct.

**7.13** In Section 2.6 it was noted that the net bonding energy *EN* between two isolated positive and negative ions is a function of interionic distance *r* as follows:

$$
E_N = -\frac{A}{r} + \frac{B}{r^n} \tag{7.36}
$$

 where *A*, *B*, and *n* are constants for the particular ion pair. Equation 7.36 is also valid for the bonding energy between adjacent ions in solid materials. The modulus of elasticity *E* is proportional to the slope of the interionic force–separation curve at the equilibrium interionic separation; that is,

$$
E \propto \left(\frac{dF}{dr}\right)_{r_0}
$$

![](_page_53_Figure_10.jpeg)

**Figure 7.35** Tensile stress–strain behavior for a gray cast iron.

 Derive an expression for the dependence of the modulus of elasticity on these *A*, *B*, and *n* parameters (for the two-ion system), using the following procedure:

 **1.** Establish a relationship for the force *F* as a function of *r*, realizing that

$$
F=\frac{dE_N}{dr}
$$

 **2.** Now take the derivative *dF*/*dr*.

 **3.** Develop an expression for *r*0, the equilibrium separation. Because *r*0 corresponds to the value of *r* at the minimum of the *EN*-versus-*r* curve (Figure 2.10*b*), take the derivative *dEN*/*dr*, set it equal to zero, and solve for *r*, which corresponds to *r*0.

- **4.** Finally, substitute this expression for *r*0 into the relationship obtained by taking *dF*/*dr*.
- **7.14** Using the solution to Problem 7.13, rank the magnitudes of the moduli of elasticity for the following hypothetical X, Y, and Z materials from the greatest to the least. The appropriate *A*, *B*, and *n* parameters (Equation 7.36) for these three materials are shown in the following table; they yield *EN* in units of electron volts and *r* in nanometers:

| Material | A   | B          | n |
|----------|-----|------------|---|
| X        | 1.5 | 7.0 × 10−6 | 8 |
| Y        | 2.0 | 1.0 × 10−5 | 9 |
| Z        | 3.5 | 4.0 × 10−6 | 7 |

# *Elastic Properties of Materials*

**7.15** A cylindrical specimen of steel having a diameter of 15.2 mm (0.60 in.) and length of 250 mm (10.0 in.) is deformed elastically in tension with a force of 48,900 N (11,000 lbf). Using the data contained in Table 7.1, determine the following:

 **(a)** The amount by which this specimen will elongate in the direction of the applied stress.

 **(b)** The change in diameter of the specimen. Will the diameter increase or decrease?

- **7.16** A cylindrical bar of aluminum 19 mm (0.75 in.) in diameter is to be deformed elastically by application of a force along the bar axis. Using the data in Table 7.1, determine the force that produces an elastic reduction of 2.5 × 10<sup>−</sup><sup>3</sup> mm (1.0 × 10<sup>−</sup><sup>4</sup> in.) in the diameter.
- **7.17** A cylindrical specimen of a metal alloy 10 mm (0.4 in.) in diameter is stressed elastically in tension. A force of 15,000 N (3370 lbf) produces a reduction in specimen diameter of 7 × 10<sup>−</sup><sup>3</sup> mm (2.8 × 10<sup>−</sup><sup>4</sup> in.). Compute Poisson's ratio for this material if its elastic modulus is 100 GPa (14.5 × 10<sup>6</sup> psi).
- **7.18** A cylindrical specimen of a hypothetical metal alloy is stressed in compression. If its original and final diameters are 30.00 and 30.04 mm, respectively, and its final length is 105.20 mm, compute its original length if the deformation is totally elastic. The elastic and shear moduli for this alloy are 65.5 and 25.4 GPa, respectively.
- **7.19** Consider a cylindrical specimen of some hypothetical metal alloy that has a diameter of 10.0 mm (0.39 in.). A tensile force of 1500 N (340 lbf) produces an elastic reduction in diameter of 6.7 × 10<sup>−</sup><sup>4</sup> mm (2.64 × 10<sup>−</sup><sup>5</sup> in.). Compute the elastic modulus of this alloy, given that Poisson's ratio is 0.35.
- **7.20** A brass alloy is known to have a yield strength of 240 MPa (35,000 psi), a tensile strength of 310 MPa (45,000 psi), and an elastic modulus of 110 GPa (16.0 × 10<sup>6</sup> psi). A cylindrical specimen of this alloy 15.2 mm (0.60 in.) in diameter and 380 mm (15.0 in.) long is stressed in tension and found to elongate 1.9 mm (0.075 in.). On the basis of the information given, is it possible to compute the magnitude of the load necessary to produce this change in length? If so, calculate the load; if not, explain why.

**7.21** A cylindrical metal specimen 15.0 mm (0.59 in.) in diameter and 150 mm (5.9 in.) long is to be subjected to a tensile stress of 50 MPa (7250 psi); at this stress level, the resulting deformation will be totally elastic.

 **(a)** If the elongation must be less than 0.072 mm (2.83 × 10<sup>−</sup><sup>3</sup> in.), which of the metals in Table 7.1 are suitable candidates? Why?

 **(b)** If, in addition, the maximum permissible diameter decrease is 2.3 × 10<sup>−</sup><sup>3</sup> mm (9.1 × 10<sup>−</sup><sup>5</sup> in.) when the tensile stress of 50 MPa is applied, which of the metals that satisfy the criterion in part (a) are suitable candidates? Why?

**7.22** A cylindrical metal specimen 10.7000 mm in diameter and 95.000 mm long is to be subjected to a tensile force of 6300 N; at this force level, the resulting deformation will be totally elastic.

 **(a)** If the final length must be less than 95.040 mm, which of the metals in Table 7.1 are suitable candidates? Why?

 **(b)** If, in addition, the diameter must be no greater than 10.698 mm while the tensile force of 6300 N is applied, which of the metals that satisfy the criterion in part (a) are suitable candidates? Why?

- **7.23** Consider the brass alloy for which the stress– strain behavior is shown in Figure 7.12. A cylindrical specimen of this material 10.0 mm (0.39 in.) in diameter and 101.6 mm (4.0 in.) long is pulled in tension with a force of 10,000 N (2250 lbf). If it is known that this alloy has a value for Poisson's ratio of 0.35, compute **(a)** the specimen elongation and **(b)** the reduction in specimen diameter.
- **7.24** A cylindrical rod 120 mm long and having a diameter of 15.0 mm is to be deformed using a tensile load of 35,000 N. It must not experience either plastic deformation or a diameter reduction of more than 1.2 × 10<sup>−</sup><sup>2</sup> mm. Of the following materials listed, which are possible candidates? Justify your choice(s).

| Material        | Modulus of<br>Elasticity<br>(GPa) | Yield<br>Strength<br>(MPa) | Poisson's<br>Ratio |
|-----------------|-----------------------------------|----------------------------|--------------------|
| Aluminum alloy  | 70                                | 250                        | 0.33               |
| Titanium alloy  | 105                               | 850                        | 0.36               |
| Steel alloy     | 205                               | 550                        | 0.27               |
| Magnesium alloy | 45                                | 170                        | 0.35               |

**7.25** A cylindrical rod 500 mm (20.0 in.) long and having a diameter of 12.7 mm (0.50 in.) is to be subjected to a tensile load. If the rod is to experience neither plastic deformation nor an elongation of more than 1.3 mm (0.05 in.) when the applied load is 29,000 N (6500 lbf), which of the four metals or alloys listed in the following table are possible candidates? Justify your choice(s).

| Material       | Modulus of<br>Elasticity<br>(GPa) | Yield<br>Strength<br>(MPa) | Tensile<br>Strength<br>(MPa) |
|----------------|-----------------------------------|----------------------------|------------------------------|
| Aluminum alloy | 70                                | 255                        | 420                          |
| Brass alloy    | 100                               | 345                        | 420                          |
| Copper         | 110                               | 210                        | 275                          |
| Steel alloy    | 207                               | 450                        | 550                          |

# *Tensile Properties*

- **7.26** Figure 7.34 shows the tensile engineering stress– strain behavior for a steel alloy.
- **(a)** What is the modulus of elasticity?
- **(b)** What is the proportional limit?
- **(c)** What is the yield strength at a strain offset of 0.002?
- **(d)** What is the tensile strength?
- **7.27** A cylindrical specimen of a brass alloy having a length of 100 mm (4 in.) must elongate only 5 mm (0.2 in.) when a tensile load of 100,000 N (22,500 lbf) is applied. Under these circumstances, what must be the radius of the specimen? Consider this brass alloy to have the stress–strain behavior shown in Figure 7.12.
- **7.28** A load of 140,000 N (31,500 lbf) is applied to a cylindrical specimen of a steel alloy (displaying the stress–strain behavior shown in Figure 7.34) that has a cross-sectional diameter of 10 mm (0.40 in.).

 **(a)** Will the specimen experience elastic and/or plastic deformation? Why?

 **(b)** If the original specimen length is 500 mm (20 in.), how much will it increase in length when this load is applied?

**7.29** A bar of a steel alloy that exhibits the stress– strain behavior shown in Figure 7.34 is subjected to a tensile load; the specimen is 375 mm (14.8 in.) long and has a square cross section 5.5 mm (0.22 in.) on a side.

 **(a)** Compute the magnitude of the load necessary to produce an elongation of 2.25 mm (0.088 in.).

 **(b)** What will be the deformation after the load has been released?

**7.30** A cylindrical specimen of stainless steel having a diameter of 12.8 mm (0.505 in.) and a gauge length of 50.800 mm (2.000 in.) is pulled in tension. Use the load–elongation characteristics shown in the following table to complete parts (a) through (f).

| Load    |          |        | Length |
|---------|----------|--------|--------|
| N       | lbf      | mm     | in.    |
| 0       | 0        | 50.800 | 2.000  |
| 12,700  | 2,850    | 50.825 | 2.001  |
| 25,400  | 5,710    | 50.851 | 2.002  |
| 38,100  | 8,560    | 50.876 | 2.003  |
| 50,800  | 11,400   | 50.902 | 2.004  |
| 76,200  | 17,100   | 50.952 | 2.006  |
| 89,100  | 20,000   | 51.003 | 2.008  |
| 92,700  | 20,800   | 51.054 | 2.010  |
| 102,500 | 23,000   | 51.181 | 2.015  |
| 107,800 | 24,200   | 51.308 | 2.020  |
| 119,400 | 26,800   | 51.562 | 2.030  |
| 128,300 | 28,800   | 51.816 | 2.040  |
| 149,700 | 33,650   | 52.832 | 2.080  |
| 159,000 | 35,750   | 53.848 | 2.120  |
| 160,400 | 36,000   | 54.356 | 2.140  |
| 159,500 | 35,850   | 54.864 | 2.160  |
| 151,500 | 34,050   | 55.880 | 2.200  |
| 124,700 | 28,000   | 56.642 | 2.230  |
|         | Fracture |        |        |

 **(a)** Plot the data as engineering stress versus engineering strain.

 **(b)** Compute the modulus of elasticity.

 **(c)** Determine the yield strength at a strain offset of 0.002.

 **(d)** Determine the tensile strength of this alloy.

 **(e)** What is the approximate ductility, in percent elongation?

 **(f)** Compute the modulus of resilience.

**7.31** A specimen of magnesium having a rectangular cross section of dimensions 3.2 mm × 19.1 mm ( 1 <sup>8</sup> in. <sup>×</sup> <sup>3</sup> <sup>4</sup> in.) is deformed in tension. Using the load–elongation data shown in the following table, complete parts (a) through (f).

| Load |          | Length |       |
|------|----------|--------|-------|
| lbf  | N        | in.    | mm    |
| 0    | 0        | 2.500  | 63.50 |
| 310  | 1380     | 2.501  | 63.53 |
| 625  | 2780     | 2.502  | 63.56 |
| 1265 | 5630     | 2.505  | 63.62 |
| 1670 | 7430     | 2.508  | 63.70 |
| 1830 | 8140     | 2.510  | 63.75 |
| 2220 | 9870     | 2.525  | 64.14 |
| 2890 | 12,850   | 2.575  | 65.41 |
| 3170 | 14,100   | 2.625  | 66.68 |
| 3225 | 14,340   | 2.675  | 67.95 |
| 3110 | 13,830   | 2.725  | 69.22 |
| 2810 | 12,500   | 2.775  | 70.49 |
|      | Fracture |        |       |

 **(a)** Plot the data as engineering stress versus engineering strain.

 **(b)** Compute the modulus of elasticity.

 **(c)** Determine the yield strength at a strain offset of 0.002.

- **(d)** Determine the tensile strength of this alloy.
- **(e)** Compute the modulus of resilience.
- **(f)** What is the ductility, in percent elongation?
- **7.32** A cylindrical metal specimen 15.00 mm in diameter and 120 mm long is to be subjected to a tensile force of 15,000 N.

 **(a)** If this metal must not experience any plastic deformation, which of aluminum, copper, brass, nickel, steel, and titanium (Table 7.2) are suitable candidates? Why?

 **(b)** If, in addition, the specimen must elongate no more than 0.070 mm, which of the metals that satisfy the criterion in part (a) are suitable candidates? Why? Base your choices on data found in Table 7.1.

**7.33** For the titanium alloy whose stress–strain behavior can be observed in the Tensile Tests module of *Virtual Materials Science and Engineering*  (*VMSE*) (which is found in *WileyPLUS*), determine the following:

 **(a)** the approximate yield strength (0.002 strain offset)

- **(b)** the tensile strength
- **(c)** the approximate ductility, in percent elongation

 How do these values compare with those for the two Ti-6Al-4V alloys presented in Table B.4 of Appendix B?

**7.34** For the tempered steel alloy whose stress–strain behavior can be observed in the Tensile Tests mod-

ule of *Virtual Materials Science and Engineering*  (*VMSE*) (which is found in *WileyPLUS*), determine the following:

 **(a)** the approximate yield strength (0.002 strain offset)

 **(b)** the tensile strength

 **(c)** the approximate ductility, in percent elongation

 How do these values compare with those for the oil-quenched and tempered 4140 and 4340 steel alloys presented in Table B.4 of Appendix B?

**7.35** For the aluminum alloy whose stress–strain be-

havior can be observed in the Tensile Tests module of *Virtual Materials Science and Engineering*  (*VMSE*) (which is found in *WileyPLUS*), determine the following:

 **(a)** the approximate yield strength (0.002 strain offset)

 **(b)** the tensile strength

 **(c)** the approximate ductility, in percent elongation How do these values compare with those for the 2024 aluminum alloy (T351 temper) presented in Table B.4 of Appendix B?

**7.36** For the (plain) carbon steel alloy whose stress– strain behavior can be observed in the Tensile Tests module of *Virtual Materials Science and Engineering* (*VMSE*) (which is found in *WileyPLUS*), determine the following:

- **(a)** the approximate yield strength
- **(b)** the tensile strength
- **(c)** the approximate ductility, in percent elongation
- **7.37** A cylindrical metal specimen having an original diameter of 12.8 mm (0.505 in.) and gauge length of 50.80 mm (2.000 in.) is pulled in tension until fracture occurs. The diameter at the point of fracture is 8.13 mm (0.320 in.), and the fractured gauge length is 74.17 mm (2.920 in.). Calculate the ductility in terms of percent reduction in area and percent elongation.
- **7.38** Calculate the moduli of resilience for the materials having the stress–strain behaviors shown in Figures 7.12 and 7.34.
- **7.39** Determine the modulus of resilience for each of the following alloys:

| Material       | Yield Strength |         |  |
|----------------|----------------|---------|--|
|                | MPa            | psi     |  |
| Steel alloy    | 830            | 120,000 |  |
| Brass alloy    | 380            | 55,000  |  |
| Aluminum alloy | 275            | 40,000  |  |
| Titanium alloy | 690            | 100,000 |  |

Use the modulus of elasticity values in Table 7.1.

- **7.40** A steel alloy to be used for a spring application must have a modulus of resilience of at least 2.07 MPa (300 psi). What must be its minimum yield strength?
- **7.41** Using data found in Appendix B, estimate the modulus of resilience (in MPa) of annealed 17-4PH stainless steel.

# *True Stress and Strain*

- **7.42** Show that Equations 7.18a and 7.18b are valid when there is no volume change during deformation.
- **7.43** Demonstrate that Equation 7.16, the expression defining true strain, may also be represented by

$$
\varepsilon_T = \ln\!\left(\!\frac{A_0}{A_i}\!\right)
$$

 when the specimen volume remains constant during deformation. Which of these two expressions is more valid during necking? Why?

**7.44** Using the data in Problem 7.30 and Equations 7.15, 7.16, and 7.18a, generate a true stress–true strain plot for stainless steel. Equation 7.18a becomes invalid past the point at which necking begins; therefore, measured diameters are given in the following table for the last three data points, which should be used in true stress computations.

|         | Load   |        | Length |       | Diameter |
|---------|--------|--------|--------|-------|----------|
| N       | lbf    | mm     | in.    | mm    | in.      |
| 159,500 | 35,850 | 54.864 | 2.160  | 12.22 | 0.481    |
| 151,500 | 34,050 | 55.880 | 2.200  | 11.80 | 0.464    |
| 124,700 | 28,000 | 56.642 | 2.230  | 10.65 | 0.419    |

- **7.45** A tensile test is performed on a metal specimen, and it is found that a true plastic strain of 0.16 is produced when a true stress of 500 MPa (72,500 psi) is applied; for the same metal, the value of *K* in Equation 7.19 is 825 MPa (120,000 psi). Calculate the true strain that results from the application of a true stress of 600 MPa (87,000 psi).
- **7.46** For some metal alloy, a true stress of 345 MPa (50,000 psi) produces a plastic true strain of 0.02. How much does a specimen of this material elongate

when a true stress of 415 MPa (60,000 psi) is applied if the original length is 500 mm (20 in.)? Assume a value of 0.22 for the strain-hardening exponent, *n*.

**7.47** The following true stresses produce the corresponding true plastic strains for a brass alloy:

| True Stress (psi) | True Strain |
|-------------------|-------------|
| 60,000            | 0.15        |
| 70,000            | 0.25        |

 What true stress is necessary to produce a true plastic strain of 0.21?

**7.48** For a brass alloy, the following engineering stresses produce the corresponding plastic engineering strains prior to necking:

| Engineering<br>Stress (MPa) | Engineering<br>Strain |
|-----------------------------|-----------------------|
| 315                         | 0.105                 |
| 340                         | 0.220                 |

 On the basis of this information, compute the *engineering* stress necessary to produce an *engineering* strain of 0.28.

- **7.49** Find the toughness (or energy to cause fracture) for a metal that experiences both elastic and plastic deformation. Assume Equation 7.5 for elastic deformation, that the modulus of elasticity is 103 GPa (15 × 106 psi), and that elastic deformation terminates at a strain of 0.007. For plastic deformation, assume that the relationship between stress and strain is described by Equation 7.19, in which the values for *K* and *n* are 1520 MPa (221,000 psi) and 0.15, respectively. Furthermore, plastic deformation occurs between strain values of 0.007 and 0.60, at which point fracture occurs.
- **7.50** For a tensile test, it can be demonstrated that necking begins when

$$
\frac{d\sigma_T}{d\varepsilon_T} = \sigma_T \tag{7.37}
$$

 Using Equation 7.19, determine an expression for the value of the true strain at this onset of necking.

**7.51** Taking the logarithm of both sides of Equation 7.19 yields

$$
\log \sigma_T = \log K + n \log \varepsilon_T \tag{7.38}
$$

 Thus, a plot of log *σT* versus log *εT* in the plastic region to the point of necking should yield a straight line having a slope of *n* and an intercept (at log *σ<sup>T</sup>* = 0) of log *K*.

 Using the appropriate data tabulated in Problem 7.30, make a plot of log *σT* versus log

*εT* and determine the values of *n* and *K*. It will be necessary to convert engineering stresses and strains to true stresses and strains using Equations 7.18a and 7.18b.

### *Elastic Recovery after Plastic Deformation*

- **7.52** A cylindrical specimen of a brass alloy 10.0 mm (0.39 in.) in diameter and 120.0 mm (4.72 in.) long is pulled in tension with a force of 11,750 N (2640 lbf); the force is subsequently released.
- **(a)** Compute the final length of the specimen at this time. The tensile stress–strain behavior for this alloy is shown in Figure 7.12.
- **(b)** Compute the final specimen length when the load is increased to 23,500 N (5280 lbf) and then released.
- **7.53** A steel alloy specimen having a rectangular cross section of dimensions 19 mm × 3.2 mm (<sup>3</sup> <sup>4</sup> in. <sup>×</sup> <sup>1</sup> <sup>8</sup> in.) has the stress–strain behavior shown in Figure 7.34. This specimen is subjected to a tensile force of 110,000 N (25,000 lbf).
- **(a)** Determine the elastic and plastic strain values.
- **(b)** If its original length is 610 mm (24.0 in.), what will be its final length after the load in part (a) is applied and then released?

# *Flexural Strength (Ceramics)*

**7.54** A three-point bending test is performed on a spinel (MgAl2O4) specimen having a rectangular cross section of height *d* = 3.8 mm (0.15 in.) and width *b* = 9 mm (0.35 in.); the distance between support points is 25 mm (1.0 in.).

 **(a)** Compute the flexural strength if the load at fracture is 350 N (80 lbf).

 **(b)** The point of maximum deflection Δ*y* occurs at the center of the specimen and is described by

$$
\Delta y = \frac{FL^3}{48EI} \tag{7.39}
$$

 where *E* is the modulus of elasticity and *I* is the cross-sectional moment of inertia. Compute Δ*y* at a load of 310 N (70 lbf).

- **7.55** A circular specimen of MgO is loaded using a three-point bending mode. Compute the minimum possible radius of the specimen without fracture, given that the applied load is 5560 N (1250 lbf), the flexural strength is 105 MPa (15,000 psi), and the separation between load points is 45 mm (1.75 in.).
- **7.56** A three-point bending test was performed on an aluminum oxide specimen having a circular cross

section of radius 5.0 mm (0.20 in.); the specimen fractured at a load of 3000 N (675 lbf) when the distance between the support points was 40 mm (1.6 in.). Another test is to be performed on a specimen of this same material, but one that has a square cross section of 15 mm (0.6 in.) length on each edge. At what load would you expect this specimen to fracture if the support point separation is maintained at 40 mm (1.6 in.)?

**7.57 (a)** A three-point transverse bending test is conducted on a cylindrical specimen of aluminum oxide having a reported flexural strength of 300 MPa (43,500 psi). If the specimen radius is 5.0 mm (0.20 in.) and the support point separation distance is 15.0 mm (0.61 in.), would you expect the specimen to fracture when a load of 7500 N (1690 lbf) is applied? Justify your answer.

 **(b)** Would you be 100% certain of the answer in part (a)? Why or why not?

# *Influence of Porosity on the Mechanical Properties of Ceramics*

- **7.58** The modulus of elasticity for spinel (MgAl2O4) having 5 vol% porosity is 240 GPa (35 × 106 psi).
- **(a)** Compute the modulus of elasticity for the nonporous material.
- **(b)** Compute the modulus of elasticity for 15 vol% porosity.
- **7.59** The modulus of elasticity for titanium carbide (TiC) having 5 vol% porosity is 310 GPa (45 × 106 psi).

 **(a)** Compute the modulus of elasticity for the nonporous material.

 **(b)** At what volume percent porosity will the modulus of elasticity be 240 GPa (35 × 106 psi)?

**7.60** Using the data in Table 7.2, do the following:

 **(a)** Determine the flexural strength for nonporous MgO, assuming a value of 3.75 for *n* in Equation 7.22.

 **(b)** Compute the volume fraction porosity at which the flexural strength for MgO is 74 MPa (10,700 psi).

**7.61** The flexural strength and associated volume fraction porosity for two specimens of the same ceramic material are as follows:

| σfs<br>(MPa) | P    |
|--------------|------|
| 70           | 0.10 |
| 60           | 0.15 |

 **(a)** Compute the flexural strength for a completely nonporous specimen of this material.

 **(b)** Compute the flexural strength for a 0.20 volume fraction porosity.

### *Stress–Strain Behavior (Polymers)*

**7.62** From the stress–strain data for poly(methyl methacrylate) shown in Figure 7.24, determine the modulus of elasticity and tensile strength at room temperature [20°C (68°F)], and compare these values with those given in Tables 7.1 and 7.2.

**7.63** Compute the elastic moduli for the following

- polymers, whose stress–strain behaviors can be observed in the Tensile Tests module of *Virtual Materials Science and Engineering* (*VMSE*) (which is found in *WileyPLUS*):
- **(a)** high-density polyethylene
- **(b)** nylon
- **(c)** phenol-formaldehyde (Bakelite)

How do these values compare with those presented in Table 7.1 for the same polymers?

- **7.64** For the nylon polymer whose stress–strain behavior can be observed in the Tensile Tests mod
  - ule of *Virtual Materials Science and Engineering*  (*VMSE*) (which is found in *WileyPLUS*), determine the following:
- **(a)** The yield strength

 **(b)** The approximate ductility, in percent elongation

 How do these values compare with those for the nylon material presented in Table 7.2?

**7.65** For the phenol-formaldehyde (Bakelite) polymer whose stress–strain behavior can be observed in the Tensile Tests module of *Virtual Material Science and Engineering (VMSE)* (which is found in *WileyPLUS*), determine the following:

- **(a)** The tensile strength
- **(b)** The approximate ductility, in percent elongation

 How do these values compare with those for the phenol-formaldehyde material presented in Table 7.2?

# *Viscoelastic Deformation*

- **7.66** In your own words, briefly describe the phenomenon of *viscoelasticity*.
- **7.67** For some viscoelastic polymers that are subjected to stress relaxation tests, the stress decays with time according to

![](_page_59_Figure_23.jpeg)

**Figure 7.36** Logarithm of relaxation modulus versus logarithm of time for poly(methyl methacrylate) between 40°C and 135°C.

(From J. R. McLoughlin and A. V. Tobolsky, *J. Colloid Sci.,* **7,** 555, 1952. Reprinted with permission.)

$$
\sigma(t) = \sigma(0) \exp\left(-\frac{t}{\tau}\right) \tag{7.40}
$$

 where *σ*(*t*) and *σ*(0) represent the time-dependent and initial (i.e., time = 0) stresses, respectively, and *t* and *τ* denote elapsed time and the relaxation time, respectively; *τ* is a time-independent constant characteristic of the material. A specimen of a viscoelastic polymer whose stress relaxation obeys Equation 7.40 was suddenly pulled in tension to a measured strain of 0.5; the stress necessary to maintain this constant strain was measured as a function of time. Determine *Er*(10) for this material if the initial stress level was 3.5 MPa (500 psi), which dropped to 0.5 MPa (70 psi) after 30 s.

- **7.68** In Figure 7.36, the logarithm of *Er*(*t*) versus the logarithm of time is plotted for PMMA at a variety of temperatures. Plot log *Er*(10) versus temperature and then estimate its *Tg*.
- **7.69** On the basis of the curves in Figure 7.26, sketch schematic strain–time plots for the

following polystyrene materials at the specified temperatures:

- **(a)** Crystalline at 70°C
- **(b)** Amorphous at 180°C
- **(c)** Crosslinked at 180°C
- **(d)** Amorphous at 100°C
- **7.70 (a)** Contrast the manner in which stress relaxation and viscoelastic creep tests are conducted.

 **(b)** For each of these tests, cite the experimental parameter of interest and how it is determined.

**7.71** Make two schematic plots of the logarithm of relaxation modulus versus temperature for an amorphous polymer (curve *C* in Figure 7.29).

 **(a)** On one of these plots, demonstrate how the behavior changes with increasing molecular weight.

 **(b)** On the other plot, indicate the change in behavior with increasing crosslinking.

### *Hardness*

**7.72 (a)** A 10-mm-diameter Brinell hardness indenter produced an indentation 2.50 mm in diameter in a steel alloy when a load of 1000 kg was used. Compute the HB of this material.

 **(b)** What will be the diameter of an indentation to yield a hardness of 300 HB when a 500-kg load is used?

**7.73 (a)** Calculate the Knoop hardness when a 500-g load yields an indentation diagonal length of 100 μm.

**(b)** The measured HK of some material is 200. Compute the applied load if the indentation diagonal length is 0.25 mm.

**7.74 (a)** What is the indentation diagonal length when a load of 0.60 kg produces a Vickers HV of 400?

**(b)** Calculate the Vickers hardness when a 700-g load yields an indentation diagonal length of 0.050 mm.

**7.75** Estimate the Brinell and Rockwell hardnesses for the following:

 **(a)** The naval brass for which the stress–strain behavior is shown in Figure 7.12.

 **(b)** The steel alloy for which the stress–strain behavior is shown in Figure 7.34.

**7.76** Using the data represented in Figure 7.31, specify equations relating tensile strength and Brinell hardness for brass and nodular cast iron, similar to Equations 7.25a and 7.25b for steels.

# *Variability of Material Properties*

**7.77** Cite five factors that lead to scatter in measured material properties.

**7.78** The following table gives a number of Rockwell G hardness values that were measured on a single steel specimen. Compute average and standard deviation hardness values.

| 47.3 | 48.7 | 47.1 |
|------|------|------|
| 52.1 | 50.0 | 50.4 |
| 45.6 | 46.2 | 45.9 |
| 49.9 | 48.3 | 46.4 |
| 47.6 | 51.1 | 48.5 |
| 50.4 | 46.7 | 49.7 |

**7.79** The following table gives a number of yield strength values (in MPa) that were measured on the same aluminum alloy. Compute average and standard deviation yield strength values.

| 274.3 | 277.1 | 263.8 |
|-------|-------|-------|
| 267.5 | 258.6 | 271.2 |
| 255.4 | 266.9 | 257.6 |
| 270.8 | 260.1 | 264.3 |
| 261.7 | 279.4 | 260.5 |

# *Design/Safety Factors*

- **7.80** Upon what three criteria are factors of safety based?
- **7.81** Determine working stresses for the two alloys that have the stress–strain behaviors shown in Figures 7.12 and 7.34.

# *Spreadsheet Problem*

**7.1SS** For a cylindrical metal specimen loaded in tension to fracture, given a set of load and corresponding length data, as well as the predeformation diameter and length, generate a spreadsheet that will allow the user to plot **(a)** engineering stress versus engineering strain, and **(b)** true stress versus true strain to the point of necking.

# DESIGN PROBLEMS

- **7.D1** A large tower is to be supported by a series of steel wires; it is estimated that the load on each wire will be 13,300 N (3000 lbf). Determine the minimum required wire diameter, assuming a factor of safety of 2.0 and a yield strength of 860 MPa (125,000 psi) for the steel.
- **7.D2** (a) Consider a thin-walled cylindrical tube having a radius of 65 mm that is to be used to transport pressurized gas. If inside and outside tube pressures are 100 and 2.0 atm (10.13 and 0.2026 MPa), respectively, compute the minimum required thickness for each of the following metal alloys. Assume a factor of safety of 3.5.

| Alloy         | Yield<br>Strength,<br>σy (MPa) | Density,<br>ρ (g/cm3<br>) | Unit Mass<br>Cost, c<br>(\$US/kg) |
|---------------|--------------------------------|---------------------------|-----------------------------------|
| Steel (plain) | 375                            | 7.8                       | 1.50                              |
| Steel (alloy) | 1000                           | 7.8                       | 2.75                              |
| Cast iron     | 225                            | 7.1                       | 3.50                              |
| Aluminum      | 275                            | 2.7                       | 5.00                              |
| Magnesium     | 175                            | 1.8                       | 16.00                             |

**(b)** A tube constructed of which of the alloys will cost the least amount?

**7.D3 (a)** Gaseous hydrogen at a constant pressure of 0.658 MPa (5 atm) is to flow within the inside of a thin-walled cylindrical tube of nickel that has a radius of 0.125 m. The temperature of the tube is to be 350°C and the pressure of hydrogen outside of the tube will be maintained at 0.0127 MPa (0.125 atm). Calculate the minimum wall thickness if the diffusion flux is to be no greater than 1.25 × 10<sup>−</sup><sup>7</sup> mol/ m2 ∙ s. The concentration of hydrogen in the nickel, *C*H (in moles hydrogen per cubic meter of Ni), is a function of hydrogen pressure, *P*H2 (in MPa), and absolute temperature *T* according to

$$
C_{\rm H} = 30.8 \sqrt{p_{\rm H_2}} \exp\left(-\frac{12,300 \, \text{J/mol}}{RT}\right) \tag{7.41}
$$

 Furthermore, the diffusion coefficient for the diffusion of H in Ni depends on temperature as

$$
D_{\rm H}(\rm m^2/s) = 4.76 \times 10^{-7} \exp\left(-\frac{39,560 \text{ J/mol}}{RT}\right)
$$
\n(7.42)

 **(b)** For thin-walled cylindrical tubes that are pressurized, the circumferential stress is a function of the pressure difference across the wall (Δ*p*), cylinder radius (*r*), and tube thickness (Δ*x*) according to Equation 7.30—that is,

$$
\sigma = \frac{r \Delta p}{\Delta x} \tag{7.30a}
$$

 Compute the circumferential stress to which the walls of this pressurized cylinder are exposed. [*Note:* The symbol *t* is used for cylinder wall thickness in Equation 7.30 found in Design Example 7.2; in this version of Equation 7.30 (i.e., 7.30a) we denote the wall thickness by Δ*x*.]

 **(c)** The room-temperature yield strength of Ni is 100 MPa (15,000 psi), and *σy* diminishes about 5 MPa for every 50°C rise in temperature. Would you expect the wall thickness computed in part (b) to be suitable for this Ni cylinder at 350°C? Why or why not?

- **(d)** If this thickness is found to be suitable, compute the minimum thickness that could be used without any deformation of the tube walls. How much would the diffusion flux increase with this reduction in thickness? However, if the thickness determined in part (c) is found to be unsuitable, then specify a minimum thickness that you would use. In this case, how much of a decrease in diffusion flux would result?
- **7.D4** Consider the steady-state diffusion of hydrogen through the walls of a cylindrical nickel tube as described in Problem 7.D3. One design calls for a diffusion flux of 2.5 × 10<sup>−</sup><sup>8</sup> mol/m2 ∙ s, a tube radius of 0.100 m, and inside and outside pressures of 1.015 MPa (10 atm) and 0.01015 MPa (0.1 atm), respectively; the maximum allowable temperature is 300°C. Specify a suitable temperature and wall thickness to give this diffusion flux and yet ensure that the tube walls will not experience any permanent deformation.
- **7.D5** It is necessary to select a ceramic material to be stressed using a three-point loading scheme (Figure 7.18). The specimen must have a circular cross section, a radius of 3.8 mm (0.15 in.) and must not experience fracture or a deflection of more than 0.021 mm (8.5 × 10<sup>−</sup><sup>4</sup> in.) at its center when a load of 445 N (100 lbf) is applied. If the distance between support points is 50.8 mm (2 in.), which of the materials in Table 7.2 are candidates? The magnitude of the centerpoint deflection may be computed using Equation 7.39.

# **FUNDAMENTALS OF ENGINEERING QUESTIONS AND PROBLEMS**

- **7.1FE** A steel rod is pulled in tension with a stress that is less than the yield strength. The modulus of elasticity may be calculated as
- (A) Axial stress divided by axial strain
- (B) Axial stress divided by change in length
- (C) Axial stress times axial strain
- (D) Axial load divided by change in length
- **7.2FE** A cylindrical specimen of brass that has a diameter of 20 mm, a tensile modulus of 110 GPa, and a Poisson's ratio of 0.35 is pulled in tension with force of 40,000 N. If the deformation is totally elastic, what is the strain experienced by the specimen?

| (A) 0.00116 | (C) 0.00463 |
|-------------|-------------|
|-------------|-------------|

(B) 0.00029 (D) 0.01350

**7.3FE** The following figure shows the tensile stressstrain curve for a plain-carbon steel.

- **(a)** What is this alloy's tensile strength?
- (A) 650 MPa (C) 570 MPa
- (B) 300 MPa (D) 3,000 MPa
  - **(b)** What is its modulus of elasticity?
- (A) 320 GPa (C) 500 GPa
- (B) 400 GPa (D) 215 GPa
  - **(c)** What is the yield strength?
- (A) 550 MPa (C) 600 MPa
- (B) 420 MPa (D) 1000 MPa

![](_page_62_Figure_11.jpeg)

Reprinted with permission of John Wiley & Sons, Inc.

- **7.4FE** A specimen of steel has a rectangular cross section 20 mm wide and 40 mm thick, an elastic modulus of 207 GPa, and a Poisson's ratio of 0.30. If this specimen is pulled in tension with a force of 60,000 N, what is the change in width if deformation is totally elastic?
- (A) Increase in width of 3.62 × 10<sup>−</sup><sup>6</sup> m
- (B) Decrease in width of 7.24 × 10<sup>−</sup><sup>6</sup> m
- (C) Increase in width of 7.24 × 10<sup>−</sup><sup>6</sup> m
- (D) Decrease in width of 2.18 × 10<sup>−</sup><sup>6</sup> m
- **7.5FE** A cylindrical specimen of undeformed brass that has a radius of 300 mm is elastically deformed to a tensile strain of 0.001. If Poisson's ratio for this brass is 0.35, what is the change in specimen diameter?
- (A) Increase by 0.028 mm
- (B) Decrease by 1.05 × 10<sup>−</sup><sup>4</sup> m
- (C) Decrease by 3.00 × 10<sup>−</sup><sup>4</sup> m
- (D) Increase by 1.05 × 10<sup>−</sup><sup>4</sup> m