# CrowdSourced_Seul


\appendix
\section{Detailed Mathematical Formalism}

We start with a Hamiltonian of the form:

\begin{equation}
H = H_{\text{el}} + H_{\text{ph}} + H_{\text{int}},
\end{equation}

where

\begin{equation}
H_{\text{el}} = \sum_{ij\sigma} t_{ij}(d) c^{\dagger}_{i\sigma} c_{j\sigma},
\end{equation}

\begin{equation}
H_{\text{ph}} = \sum_{q} \hbar\omega_{q} (b^{\dagger}_{q} b_{q} + \frac{1}{2}),
\end{equation}

and 

\begin{equation}
H_{\text{int}} = \sum_{ij} g_{ij} (c_{i\uparrow}^{\dagger} c_{j\downarrow}^{\dagger} + h.c.).
\end{equation}

The electron-phonon spectral function \(\alpha^2F(\omega)\) is computed from first principles using density functional perturbation theory (DFPT), which gives us the electron-phonon matrix elements and phonon frequencies.

The Eliashberg equations can be solved self-consistently on the imaginary axis to obtain the gap function \(\Delta(i\omega_n)\) and the renormalization function \(Z(i\omega_n)\).

The superconducting critical temperature \(T_c\) is determined from the condition \(\Delta(i\omega_n = 0) = 0\) at the lowest Matsubara frequency.

The Ginzburg-Landau free energy functional is given by:

\begin{equation}
F[\psi] = \alpha(T-T_c) |\psi|^2 + \beta |\psi|^4 + \sum_{i} |\nabla\psi_i|^2,
\end{equation}

where \(\alpha\) and \(\beta\) are phenomenological parameters.

The fluctuation-dissipation theorem is applied to calculate the superconducting conductivity \(\sigma_s\), from the current-current correlation function.

The Gorkov equations are used to calculate the Green's function of the superconducting state and to incorporate the effects of impurity scattering on the superconducting properties.

\end{document}
