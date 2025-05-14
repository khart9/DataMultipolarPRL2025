# phononDrivenMultipolarDynamics--data
Data for the manuscript "Phonon-driven multipolar dynamics in a spin-orbit coupled Mott insulator"
by Kathleen Hart, Ruairidh Sutcliffe, Gil Refael and Arun Paramekanti

## File details:
All files are saved in the JLD2 format.

### Files for Figure 1:
Fig1a.jld2:<br />
    -T: with temperature data in units of $T/J_0$ <br />
    -J: with exchange parameter $J_1$ in units of $J_1/J_0$ <br />
    -My: with octupolar order parameter $\langle \tau_y \rangle$ <br />
    -Mafm: with antiferro-quadrupolar order parameter at wavevector $(\pi,\pi,0)$ and symmetrically equivalent, note Fig.1a is produced by taking absolute value of My and subtracting Mafm <br />

Fig1b.jld2:<br />
    -T: with time data in units of $\hbar/J_0$<br />
    -Qx: with time-series data for phonon coordinate $Q_x$ at $T=0.1$ <br />
    -Qz: with time-series data for phonon coordinate $Q_z$ at $T=0.1$ <br />

Fig1c.jld2:<br />
    -T: with time data in units of $\hbar/J_0$<br />
    -Qx: with time-series data for phonon coordinate $Q_x$ at $T=5.2$ <br />
    -Qz: with time-series data for phonon coordinate $Q_z$ at $T=5.2$ <br />

Fig1d.jld2:<br />
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
    - Sy1: $\tau_y$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $\pi/2$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy2: $\tau_y$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $\pi/4$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy3: $\tau_y$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = 0, J1/J0 = 1.3 and T = 3.0<br />
    - Sy4: $\tau_y$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $-\pi/4$, J1/J0 = 1.3 and T = 3.0<br />
    - Sy5: $\tau_y$ with parameters A = 0.5, $\eta$ = 1.0, $\phi$ = $-\pi/2$, J1/J0 = 1.3 and T = 3.0<br />

### Files for Figure 3:
Fig3.jld2:<br />
    -time: with time data in units of $\hbar/J_0$ for $\langle \tau_y\rangle$<br />
    -My: with data for the octupolar order parameter $\langle \tau_y\rangle$<br />
    -slice1: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=0 \hbar/J_0$<br />
    -slice2: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=1.5 \hbar/J_0$<br />
    -slice3: with a two-dimensional array representing the spins as either +1 for $\langle \tau_y\rangle>0$ or -1 for $\langle \tau_y\rangle<0$ at time $t=4.0 \hbar/J_0$<br />

