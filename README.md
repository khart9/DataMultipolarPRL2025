# phononDrivenMultipolarDynamics--data
Data for the manuscript "Phonon-driven multipolar dynamics in a spin-orbit coupled Mott insulator"
by Kathleen Hart, Ruairidh Sutcliffe, Gil Refael and Arun Paramekanti

## File details:
All files are saved in the JLD2 format.

### Files for Figure 1:
Fig1a.jld2:<br />
    -Data for the equilibrium phase diagram of the model, including both the ferro-octupolar order parameter and antiferro-quadrupolar order parameter<br />
    -T: with temperature data in units of $T/J_0$ <br />
    -J: with exchange parameter $J_1$ in units of $J_1/J_0$ <br />
    -My: with octupolar order parameter $\langle \tau_y \rangle$ <br />
    -Mafm: with antiferro-quadrupolar order parameter at wavevector $(\pi,\pi,0)$ and symmetrically equivalent, note Fig.1a is produced by taking absolute value of My and subtracting Mafm <br />

Fig1b.jld2:<br />
    -Data for a simulated pump-probe experiment, including a time series of both the kicked ($Q_x$) and unkicked ($Q_z$) phonons, in the ferro-octupolar phase<br />
    -T: with time data in units of $\hbar/J_0$<br />
    -Qx: with time-series data for phonon coordinate $Q_x$ at $T=0.1$ <br />
    -Qz: with time-series data for phonon coordinate $Q_z$ at $T=0.1$ <br />

Fig1c.jld2:<br />
    -Data for a simulated pump-probe experiment, including a time series of both the kicked ($Q_x$) and unkicked ($Q_z$) phonons, in the paramagnetic phase<br />
    -T: with time data in units of $\hbar/J_0$<br />
    -Qx: with time-series data for phonon coordinate $Q_x$ at $T=5.2$ <br />
    -Qz: with time-series data for phonon coordinate $Q_z$ at $T=5.2$ <br />

Fig1d.jld2:<br />
    -Data for comparing the maximum phonon cross-amplitude ($Q_z$ amplitude due to a $Q_x$ kick) as compared to the octupolar order parameter<br />
    -T_Qz: with an array of temperature points for the $Q_z$ cross-amplitudes <br />
    -T_my: with an array of temperature points for the order parameter data <br />
    -My: with the data for the order parameter $\langle \tau_y\rangle$ <br />
    -crossAmp: with the data for the maximum $Q_z$ cross-amplitudes <br />

### Files for Figure 2:
Fig2a.jld2:<br />
    - Data for the spin and phonon dynamics for a pulsed drive in the FO phase, averaged only over configurations with overall positive order parameter:<br />
    - t: time data in units of $\hbar/J_0$<br />
    - Sy1: $\tau_y$ with parameters A = 1.5, $\eta$ = 1.0, $\phi$ = $\pi/2$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy2: $\tau_y$ with parameters A = 1.75, $\eta$ = 1.0, $\phi$ = $\pi/2$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy3: $\tau_y$ with parameters A = 2.0, $\eta$ = 1.0, $\phi$ = $\pi/2$, J1/J0 = 1.3 and T = 3.0<br />

Fig2b.jld2:<br />
    - Data for the spin and phonon dynamics for a pulsed drive with A=0.5 in the PM phase:<br />
    - t: time data in units of $\hbar/J_0$<br />
    - Sy1: $\langle\tau_y\rangle$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $\pi/2$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy2: $\langle\tau_y\rangle$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $\pi/4$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy3: $\langle\tau_y\rangle$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = 0, J1/J0 = 1.3 and T = 3.0<br />
    - Sy4: $\langle\tau_y\rangle$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $-\pi/4$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy5: $\langle\tau_y\rangle$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $-\pi/2$, J1/J0 = 1.3 and T = 3.0<br />

### Files for Figure 3:
Fig3.jld2:<br />
    - Data showing slices through an illustrative configuration during octupolar order switching due to a two-phonon drive and a time series of the expectation value of $\langle \tau_y \rangle$ for the lattice <br />
    -time: with time data in units of $\hbar/J_0$ for $\langle \tau_y\rangle$<br />
    -My: with data for the octupolar order parameter $\langle \tau_y\rangle$<br />
    -slice1: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=0 \hbar/J_0$<br />
    -slice2: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=1.5 \hbar/J_0$<br />
    -slice3: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=4.0 \hbar/J_0$<br />

### Files for Figure S2:
FigS2.jld2:<br />
    - Data showing the time series of the spin components $\tau_x$ and $\tau_z$ corresponding to the phonon data shown in Fig. 1.(b) of the main text.<br />
    -time: time data in units of $\hbar/J_0$ for $t=0 \hbar/J_0$ through $t=100 \hbar/J_0$ of which only the first $t=5 \hbar/J_0$ is shown in the manuscript<br />
    -Sx: time series of $\langle \tau_x \rangle$ for $t=0 \hbar/J_0$ through $t=100 \hbar/J_0$<br />
    -Sz: time series of $\langle \tau_z \rangle$ for $t=0 \hbar/J_0$ through $t=100 \hbar/J_0$<br />

### Files for Figure S5:
FigS5.jld2:<br />
    - Data showing the time series of $Q_x$ and $Q_z$ during a simulated pump-probe experiment for three different damping strengths<br />
    - t: time data in units of $\hbar/J_0$<br />
    -QxLow: time series of the $Q_x$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.007$<br />
    -QzLow: time series of the $Q_z$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.007$<br />
    -QxMid: time series of the $Q_x$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.013$<br />
    -QzMid: time series of the $Q_z$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.013$<br />
    -QxHigh: time series of the $Q_x$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.035$<br />
    -QzHigh: time series of the $Q_z$ phonon during a pump-probe simulation for a damping strength $2\pi \eta/\omega=0.035$<br />
     
### Files for Figure S6:
FigS6a.jld2:<br />
    - Data for spin dynamics for a continuous wave drive in the FO phase with weak damping ($\eta = 0.1$), averaged only over configurations with overall positive order parameter:<br />
    - Parameters: $A=0.2$, $\phi = \pi/2$, $J_1/J_0 = 1.3$, $T = 3.0$<br />
    - t: time data in units of $\hbar/J_0$<br />
    - Sx: pseudospin component $\langle \tau_x\rangle$<br />
    - Sy: pseudospin component $\langle\tau_y\rangle$<br />
    - Sz: pseudospin component $\langle\tau_z\rangle$<br />

FigS6b.jld2:<br />
    - Data for $\tau_y$ configuration dynamics for a continuous wave drive in the FO phase with weak damping ($\eta = 0.1$), corresponding to a single slice of a configuration used to produce Fig.S6a (all spins are represented as either up (+1) or down (-1). A value of zero indicates a site where no spin is present):<br />
    - Parameters: $A=0.2$, $\phi = \pi/2$, $J_1/J_0 = 1.3$, $T = 3.0$<br />
    - slice1: configuration of $\tau_y$ at $t = 22.5\hbar/J_0$<br />
    - slice2: configuration of $\tau_y$ at $t = 23.25\hbar/J_0$<br />
    - slice3: configuration of $\tau_y$ at $t = 24.0\hbar/J_0$<br />
    - slice4: configuration of $\tau_y$ at $t = 24.75\hbar/J_0$<br />


