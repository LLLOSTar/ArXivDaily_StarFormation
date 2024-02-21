# New submissions for Wed, 21 Feb 24
Auto update Star Formation & Molecular Cloud papers at about 2:30am UTC (10:30am Beijing time) every weekday.


阅读 `Usage.md`了解如何使用此repo实现个性化的Arxiv论文推送

See `Usage.md` for instructions on how to personalize the repo. 


Keyword list: ['star formation', 'star-forming', 'molecular cloud', 'interstellar medium', 'cloud', 'clump', 'core', 'filament', 'atomic gas', 'N-PDF']


Excluded: ['galaxies', 'galaxy cluster', ' AGN ']


### Today: 13papers 
#### Emulating the interstellar medium chemistry with neural operators
 - **Authors:** Lorenzo Branca, Andrea Pallottini
 - **Subjects:** Astrophysics of Galaxies (astro-ph.GA); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2402.12435
 - **Pdf link:** https://arxiv.org/pdf/2402.12435
 - **Abstract**
 Galaxy formation and evolution critically depend on understanding the complex photo-chemical processes that govern the evolution and thermodynamics of the InterStellar Medium (ISM). Computationally, solving chemistry is among the most heavy tasks in cosmological and astrophysical simulations. The evolution of such non-equilibrium photo-chemical network relies on implicit, precise, computationally costly, ordinary differential equations (ODE) solvers. Here, we aim at substituting such procedural solvers with fast, pre-trained, emulators based on neural operators. We emulate a non-equilibrium chemical network up to H$_2$ formation (9 species, 52 reactions) by adopting the DeepONet formalism, i.e. by splitting the ODE solver operator that maps the initial conditions and time evolution into a tensor product of two neural networks. We use $\texttt{KROME}$ to generate a training set spanning $-2\leq \log(n/\mathrm{cm}^{-3}) \leq 3.5$, $\log(20) \leq\log(T/\mathrm{K}) \leq 5.5$, $-6 \leq \log(n_i/n) < 0$, and by adopting an incident radiation field $\textbf{F}$ sampled in 10 energy bins with a continuity prior. We separately train the solver for $T$ and each $n_i$ for $\simeq 4.34\,\rm GPUhrs$. Compared with the reference solutions obtained by $\texttt{KROME}$ for single zone models, the typical precision obtained is of order $10^{-2}$, i.e. the $10 \times$ better with a training that is $40 \times$ less costly with respect to previous emulators which however considered only a fixed $\mathbf{F}$. The present model achieves a speed-up of a factor of $128 \times$ with respect to stiff ODE solvers. Our neural emulator represents a significant leap forward in the modeling of ISM chemistry, offering a good balance of precision, versatility, and computational efficiency.
#### G359.13142-0.20005: A steep spectrum radio pulsar candidate with an  X-ray counterpart running into the Galactic Center Snake (G359.1-0.2)
 - **Authors:** F. Yusef-Zadeh, Jun-Hui Zhao, R. Arendt, M. Wardle, C. O. Heinke, M. Royster, C. Lang, J. Michail
 - **Subjects:** High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2402.12441
 - **Pdf link:** https://arxiv.org/pdf/2402.12441
 - **Abstract**
 The Snake is a remarkable Galactic center radio filament with a morphology characterized by two kinks along its $\sim 20'$ extent. The major and minor kinks are located where the filament is most distorted from a linear magnetized structure running perpendicular to the Galactic plane. We present {\em Chandra}, VLA, and MeerKAT data and report the detection of an X-ray and radio source at the location of the major kink. High-resolution radio images of the major kink reveal a compact source with a steep spectrum with spectral index alpha ~ -2.7 surrounded by extended emission. The radio luminosity and steep spectrum of the compact source are consistent with a pulsar. We also show flattening of the spectrum and enhanced synchrotron emissivity away from the position of the major kink along the Snake, which suggests injection of relativistic particles along the Snake. We argue that the major kink is created by a fast-moving (~500-1000 km/s), object punching into the Snake, distorting its magnetic structure, and producing X-ray emission. X-ray emission pinpoints an active acceleration site where the interaction is taking place. A secondary kink is argued to be induced by the impact of the high-velocity object producing the major kink.
#### DBNets: A publicly available deep learning tool to measure the masses of  young planets in dusty protoplanetary discs
 - **Authors:** Alessandro Ruzza, Giuseppe Lodato, Giovanni Pietro Rosotti
 - **Subjects:** Earth and Planetary Astrophysics (astro-ph.EP); Instrumentation and Methods for Astrophysics (astro-ph.IM); Machine Learning (cs.LG)
 - **Arxiv link:** https://arxiv.org/abs/2402.12448
 - **Pdf link:** https://arxiv.org/pdf/2402.12448
 - **Abstract**
 Current methods to characterize embedded planets in protoplanetary disc observations are severely limited either in their ability to fully account for the observed complex physics or in their computational and time costs. To address this shortcoming, we developed DBNets: a deep learning tool, based on convolutional neural networks, that analyses substructures observed in the dust continuum emission of protoplanetary discs to quickly infer the mass of allegedly embedded planets. We focussed on developing a method to reliably quantify not only the planet mass, but also the associated uncertainty introduced by our modelling and adopted techniques. Our tests gave promising results achieving an 87% reduction of the log Mp mean squared error with respect to an analytical formula fitted on the same data (DBNets metrics: lmse 0.016, r2-score 97%). With the goal of providing the final user of DBNets with all the tools needed to interpret their measurements and decide on their significance, we extensively tested our tool on out-of-distribution data. We found that DBNets can identify inputs strongly outside its training scope returning an uncertainty above a specific threshold and we thus provided a rejection criterion that helps determine the significance of the results obtained. Additionally, we outlined some limitations of our tool: it can be reliably applied only on discs observed with inclinations below approximately 60{\deg}, in the optically thin regime, with a resolution 8 times better than the gap radial location and with a signal-to-noise ratio higher than approximately ten. Finally, we applied DBNets to 33 actual observations of protoplanetary discs measuring the mass of 48 proposed planets and comparing our results with the available literature. We confirmed that most of the observed gaps imply planets in the sub-Jupiter regime. DBNets is publicly available at dbnets.fisica.unimi.it.
#### The interaction of a large-scale nuclear wind with the high velocity HII  region G0.17+0.15
 - **Authors:** F. Yusef-Zadeh, Jun-Hui Zhao, R. Arendt, M. Wardle, M. Royster, L. Rudnick, J. Michail
 - **Subjects:** Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2402.12450
 - **Pdf link:** https://arxiv.org/pdf/2402.12450
 - **Abstract**
 We investigate the nature of a Galactic center source, G0.17+0.15, lying along the northern extension of the Radio Arc near l~0.2deg. G0.17+0.15 is an HII region located toward the eastern edge of the radio bubble, embedded within the highly polarized Galactic center eastern Lobe where a number of radio filaments appear to cross through the HII region. We report the detection of hydrogen and helium recombination lines with a radial velocity exceeding 140 km/s based on GBT and VLA observations. The morphology of G0.17+0.15, aided by kinematics, and spectral index characteristics, suggests the presence of an external pressure dragging and shredding the ionized gas. We argue that this ionized cloud is interacting with a bundle of radio filaments and is entrained by the ram pressure of the radio bubble, which itself is thought to be produced by cosmic-ray driven outflows at the Galactic center. In this interpretation, the gas streamers on the western side of G0.17+0.15 are stripped, accelerated from 0 to deltav~35 km/s, over a time scale roughly 8x10^4 years, implying that ablating ram pressure is ~700 eV cm-3, comparable to the ~10^3 eV cm-3 cosmic-ray driven wind pressure in the Galactic center region.
#### Numerical Challenges in Modeling Gravothermal Collapse in  Self-Interacting Dark Matter Halos
 - **Authors:** Igor Palubski, Oren Slone, Manoj Kaplinghat, Mariangela Lisanti, Fangzhou Jiang
 - **Subjects:** Cosmology and Nongalactic Astrophysics (astro-ph.CO); Astrophysics of Galaxies (astro-ph.GA); High Energy Physics - Phenomenology (hep-ph)
 - **Arxiv link:** https://arxiv.org/abs/2402.12452
 - **Pdf link:** https://arxiv.org/pdf/2402.12452
 - **Abstract**
 When dark matter has a large cross section for self scattering, halos can undergo a process known as gravothermal core collapse, where the inner core rapidly increases in density and temperature. To date, several methods have been used to implement Self-Interacting Dark Matter~(SIDM) in N-body codes, but there has been no systematic study of these different methods or their accuracy in the core-collapse phase. In this paper, we compare three different numerical implementations of SIDM, including the standard methods from the GIZMO and Arepo codes, by simulating idealized dwarf halos undergoing significant dark matter self interactions ($\sigma/m = 50$~cm$^2$/g). When simulating these halos, we also vary the mass resolution, time-stepping criteria, and gravitational force-softening scheme. The various SIDM methods lead to distinct differences in a halo's evolution during the core-collapse phase, as each results in slightly different scattering rates and spurious energy gains/losses. The use of adaptive force softening for gravity can lead to numerical heating that artificially accelerates core collapse, while an insufficiently small simulation time step can cause core evolution to stall or completely reverse. Additionally, particle numbers must be large enough to ensure that the simulated halos are not sensitive to noise in the initial conditions. Even for the highest-resolution simulations tested in this study ($10^6$ particles per halo), we find that variations of order $10\%$ in collapse time are still present. The results of this work underscore the sensitivity of SIDM modeling on the choice of numerical implementation and motivate a careful study of how these results generalize to halos in a cosmological context.
#### Fossil Signatures of Main-sequence Convective Core Overshoot Estimated  through Asteroseismic Analyses
 - **Authors:** Christopher J. Lindsay, J. M. Joel Ong, Sarbani Basu
 - **Subjects:** Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2402.12461
 - **Pdf link:** https://arxiv.org/pdf/2402.12461
 - **Abstract**
 Some physical processes that occur during a star's main-sequence evolution also affect its post main-sequence evolution. It is well known that stars with masses above approximately 1.1 $M_{\odot}$ have well-mixed convective cores on the main sequence, however, the structure of the star in the neighborhood of the convective core regions is currently underconstrained. We use asteroseismology to study the properties of the stellar core, in particular, convective boundary mixing through convective overshoot, in such intermediate mass stars. These core regions are poorly constrained by the acoustic (p) mode oscillations observed for cool main sequence stars. Consequently, we seek fossil signatures of main sequence core properties during the subgiant and early first-ascent red giant phases of evolution. During these stages of stellar evolution, modes of mixed character that sample the deep interior, can be observed. These modes sample the regions of the stars that are affected by the main-sequence structure of these regions. We model the global and near-core properties of 62 subgiant and early first-ascent red giant branch stars observed by the \textit{Kepler}, K2, and TESS space missions. We find that the effective overshoot parameter, $\alpha_{\text{ov, eff}}$, increases from $M = 1.0M_{\odot}$ to $M = 1.2 M_{\odot}$ before flattening out, although we note that the relationship between $\alpha_{\text{ov, eff}}$ and mass will depend on the incorporated modelling choices of internal physics and nuclear reaction network. We also situate these results within existing studies of main-sequence convective core boundaries.
#### The dynamical evolution of star-forming regions measured with INDICATE
 - **Authors:** George A. Blaylock-Squibbs, Richard J. Parker
 - **Subjects:** Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2402.12472
 - **Pdf link:** https://arxiv.org/pdf/2402.12472
 - **Abstract**
 Observations of star-forming regions provide snapshots in time of the star formation process, and can be compared with simulation data to constrain the initial conditions of star formation. In order to make robust inferences, different metrics must be used to quantify the spatial and kinematic distributions of stars. In this paper, we assess the suitability of the INDICATE (INdex to Define Inherent Clustering And TEndencies) method as a diagnostic to infer the initial conditions of star-forming regions that subsequently undergo dynamical evolution. We use INDICATE to measure the degree of clustering in N-body simulations of the evolution of star-forming regions with different initial conditions. We find that the clustering of individual stars, as measured by INDICATE, becomes significantly higher in simulations with higher initial stellar densities, and is higher in subvirial star-forming regions where significant amounts of dynamical mixing has occurred. We then combine INDICATE with other methods that measure the mass segregation, relative stellar surface density ratio and the morphology (Q-parameter) of star-forming regions, and show that the diagnostic capability of INDICATE increases when combined with these other metrics.
#### The Radcliffe Wave is Oscillating
 - **Authors:** Ralf Konietzka, Alyssa A. Goodman, Catherine Zucker, Andreas Burkert, João Alves, Michael Foley, Cameren Swiggum, Maria Koller, Núria Miret-Roig
 - **Subjects:** Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2402.12596
 - **Pdf link:** https://arxiv.org/pdf/2402.12596
 - **Abstract**
 Our Sun lies within 300 pc of the 2.7-kpc-long sinusoidal chain of dense gas clouds known as the Radcliffe Wave. The structure's wave-like shape was discovered using 3D dust mapping, but initial kinematic searches for oscillatory motion were inconclusive. Here we present evidence that the Radcliffe Wave is oscillating through the Galactic plane while also drifting radially away from the Galactic Center. We use measurements of line-of-sight velocity for 12CO and 3D velocities of young stellar clusters to show that the most massive star-forming regions spatially associated with the Radcliffe Wave (including Orion, Cepheus, North America, and Cygnus X) move as if they are part of an oscillating wave driven by the gravitational acceleration of the Galactic potential. By treating the Radcliffe Wave as a coherently oscillating structure, we can derive its motion independently of the local Galactic mass distribution, and directly measure local properties of the Galactic potential as well as the Sun's vertical oscillation period. In addition, the measured drift of the Radcliffe Wave radially outward from the Galactic Center suggests that the cluster whose supernovae ultimately created today's expanding Local Bubble may have been born in the Radcliffe Wave.
#### Radio Continuum Study of the Large Magellanic Cloud Supernova Remnant  Honeycomb Nebula
 - **Authors:** R. Z. E. Alsaberi, M. D. Filipovic, H. Sano, P. Kavanagh, P. Janas, J. L. Payne, D. Urosevic
 - **Subjects:** High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2402.12725
 - **Pdf link:** https://arxiv.org/pdf/2402.12725
 - **Abstract**
 We present the first and deepest Australia Telescope Compact Array radio continuum images of the Honeycomb Nebula at 2000 and 5500 MHz solely from archival data. The resolutions of these images are 3.6 x 2.8 arcsec2 and 1.3 x 1.2 arcsec2 at 2000 and 5500 MHz. We find an average radio spectral index for the remnant of -0.76 +- 0.07. Polarisation maps at 5500 MHz reveal an average fractional polarisation of 25 +- 5% with a maximum value of 95 x 16. We estimate the equipartition field for Honeycomb Nebula of 48 +- 5 {\mu}G, with an estimated minimum energy of Emin = 3 x 1049 erg. The estimated surface brightness, {\Sigma}1 GHz , is 30 x 10-20 W m-2 Hz-1 sr-1; applying the {\Sigma}-D relation suggests this supernova remnant is expanding into a low-density environment. Finally, using Hi data, we can support the idea that the Honeycomb Nebula exploded inside a low-density wind cavity. We suggest that this remnant is likely to be between late free expansion stage and early Sedov phase of evolution and expanding into a low-density medium.
#### A sequence of Type Ib, IIb, II-L, and II-P supernovae from binary-star  progenitors of varying initial separation
 - **Authors:** Luc Dessart, Claudia P. Gutierrez, Andrea Ercolino, Harim Jin, Norbert Langer
 - **Subjects:** Solar and Stellar Astrophysics (astro-ph.SR)
 - **Arxiv link:** https://arxiv.org/abs/2402.12977
 - **Pdf link:** https://arxiv.org/pdf/2402.12977
 - **Abstract**
 Over the last decade, evidence has accumulated that massive stars do not typically evolve in isolation but instead follow a tumultuous journey with a companion star on their way to core collapse. While Roche-lobe overflow appears instrumental for the production of a large fraction of supernovae (SNe) of Type Ib and Ic, variations in the initial orbital period Pinit of massive interacting binaries may also produce a wide diversity of case B, BC, or C systems, with preSN stars endowed from minute to massive H-rich envelopes. Focusing here on the explosion of the primary, donor star, originally of 12.6Msun, we use radiation-hydrodynamics and NLTE time-dependent radiative transfer to document the gas and radiation properties of such SNe, covering from Type Ib, IIb, II-L to II-P. Variations in Pinit are the root cause behind the wide diversity of our SN light curves, with single-peak, double-peak, fast-declining or plateau-like morphologies in the V band. The different ejecta structures, expansion rates, and relative abundances (e.g., H, He, 56Ni) are conducive to much diversity in spectral line shapes (absorption vs emission strength, width) and evolution. We emphasize that Halpha is a key tracer of these modulations, and that HeI7065 is an enduring optical diagnostic for the presence of He. Our grid of simulations fare well against representative SNe Ib, IIb, and IIP SNe, but interaction with circumstellar material, which is ignored in this work, is likely at the origin of the tension between our Type IIL SN models and observations (e.g., SN2006Y). Remaining discrepancies in our model rise time to bolometric maximum call for a proper account of both small-scale and large-scale structures in core-collapse SN ejecta. Discrepant Type IIP SN models, with a large plateau brightness but small line widths, may be cured by adopting more compact red-supergiant star progenitors.
#### Stellar flybies within 1 ly from the Sun and stars passing through the  Hills cloud
 - **Authors:** Igor Yu. Potemine
 - **Subjects:** Solar and Stellar Astrophysics (astro-ph.SR); Earth and Planetary Astrophysics (astro-ph.EP); Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2402.13015
 - **Pdf link:** https://arxiv.org/pdf/2402.13015
 - **Abstract**
 We reexamine the SIMBAD database with incorporated Gaia DR3 parallaxes and proper motions. Appropriate query searches allow us to find several nearby stars with measured radial velocities having flybies within 1 ly from the Sun (in linear approximation). The closest past flyby $\approx 215.7$ kyr ago at $\approx 0.136$ pc is attributed to the star UCAC4 323-037188, currently located at 21.74 pc from the Sun. If the radial velocity of a star is unknown, we attribute to it an ``advantageous'' value of $\pm 50$ km/s. It allows us to create an additional list of ``Nemesis candidates'' for the perforation of the inner Oort cloud. The closest potential flyby at $\approx 0.015$ pc ($\approx$ 0.050 ly $\approx$ 3147 AU) from the Sun is attributed to GALEX J013712.5-012958 (Gaia DR3 2508809660245711360). It is currently located at the distance of about 111.1 pc and belongs to the Pisces-Eridanus stream. Also, close flybies of some massive bright stars (Algol, A-giant HD 107914, A-subgiant HD 2733 and B-subgiant HD 165704) are analyzed. Finally, we notice that B1-star BD+60 596, whose proper motions and radial velocity are both small, can be considered as the Sun's pseudo-stream companion.
#### A novel image correction method for cloud-affected observations with  Imaging Atmospheric Cherenkov Telescopes
 - **Authors:** Natalia Żywucka, Julian Sitarek, Dorota Sobczyńska, Mario Pecimotika, Dario Hrupec, Dijana Dominis Prester, Lovro Pavletić, Saša Mićanović
 - **Subjects:** Instrumentation and Methods for Astrophysics (astro-ph.IM); High Energy Astrophysical Phenomena (astro-ph.HE)
 - **Arxiv link:** https://arxiv.org/abs/2402.13190
 - **Pdf link:** https://arxiv.org/pdf/2402.13190
 - **Abstract**
 Context. The presence of clouds during observations with Imaging Atmospheric Cherenkov Telescopes can strongly affect the performance of the instrument due to additional absorption of light and scattering of light beyond the field of view of the instrument. If not corrected for, the presence of clouds leads to increased systematic errors in the results. Aims. One approach to correct for the effects of clouds is to include clouds in Monte Carlo simulations to produce models for primary particle classification, energy and direction estimation. However, this method is challenging due to the dynamic nature of cloudy conditions and requires extensive computational resources. The second approach focuses on correcting the data itself for cloud effects, which allows the use of standard simulations. However, existing corrections often prioritise limiting systematic errors without optimising overall performance. By correcting the data already at the image level, it is possible to improve event reconstruction without the need for specialised simulations. Methods. We introduce a novel analysis method, based on a geometrical model that can correct the data already at the image level given a vertical transmission profile of a cloud. Using Monte Carlo simulations of an array of four Large-Sized Telescopes of the Cherenkov Telescope Array, we investigate the effect of the correction on the image parameters and the performance of the system. We compare the data correction at the camera level with the use of dedicated simulations for clouds with different transmissions and heights. Results. The proposed method efficiently corrects the extinction of light in clouds, eliminating the need for dedicated simulations. Evaluation using Monte Carlo simulations demonstrates improved gamma-ray event reconstruction and overall system performance.
#### Chemical abundances and ionizing mechanisms in the star-forming  double-ring of AM 0644-741 using MUSE data
 - **Authors:** V. M. A. Gómez-González, Y. D. Mayya, J. Zaragoza-Cardiel, G. Bruzual, S. Charlot, G. Ramos-Larios, L. M. Oskinova, A. A. C. Sander, S. Reyero Serantes
 - **Subjects:** Astrophysics of Galaxies (astro-ph.GA)
 - **Arxiv link:** https://arxiv.org/abs/2402.13230
 - **Pdf link:** https://arxiv.org/pdf/2402.13230
 - **Abstract**
 We present the analysis of archival Very Large Telescope (VLT) Multi-Unit Spectroscopic Explorer (MUSE) observations of 179 HII regions in the star-forming double-ring collisional galaxy AM 0644-741 at 98.6 Mpc. We determined ionic abundances of He, N, O and Fe using the direct method for the brightest H II region (ID 39); we report $\log\rm{(\frac{N}{O})}=-1.3\pm0.2$ and $12+\log\rm{(\frac{O}{H})}=8.9\pm0.2$. We also find the so-called `blue-bump', broad He II $\lambda4686$, in the spectrum of this knot of massive star-formation; its luminosity being consistent with the presence of $\sim430$ Wolf-Rayet (WR) stars of the Nitrogen late-type. We determined the O abundances for 137 HII regions using the strong-line method; we report a median value of $12+\log\rm{(\frac{O}{H})}=8.5\pm0.8$. The location of three objects, including the WR complex, coincide with that of an Ultra Luminous X-ray source. Nebular He II is not detected in any H II region. We investigate the physical mechanisms responsible for the observed spectral lines using appropriate diagnostic diagrams and ionization models. We find that the H II regions are being photoionized by star clusters with ages $\sim2.5-20$ Myr and ionization potential $-3.5<$$\log\langle U\rangle$$<-3.0$. In these diagrams, a binary population is needed to reproduce the observables considered in this work.


by olozhika (Xing Yuchen). 


2024-02-21
