---
layout: post
title: "9/11/2023"
date: 2023-09-11 19:41:00 -0700
categories: coulomb z_eff quantum-numbers
---

- Wednesday prelab
- Coulomb's law, _Z.eff_
- Coulomb's law: _F_ = _ke_ \* _q1_ \* _q2_ / _d_^2
    - _ke_ is a constant
    - Opposite charges attract
    - Same charges repel
    - This equation only deals with interactions between 
    - Similar to newton's laws of graviation, which is _F_ = _G_ \* _m1_ \* _m2_ / _r_^2
    - 1.1: electric force varies directly with charge
    - 1.2: electric force varies indirectly with the square of the distance
    - 2.1: double distance -> 1/4 the force
    - 2.2: triple distnace -> 1/9 the force
- _Z.eff_ = _Z_ - _S_
    - The valence electrons of an atom are shielded from the positive charge of the nucleus' protons by the core electrons.
    - _Z_ = # of protons
    - _S_ = Shielding Constant ~= sum of electrons in inner orbitals. Can be calculated more exactly by using slater's rule.
- Slater's rule
    - Write out electron configuration. !! We write it with respect to energy levels, but we need to group it by increasing _n_ quantum number (ex. 2 in 2s1)
    - x     | _n_   | _n-1_ | _n-2_ | _n-m_
    - s, p  | 0.35  | 0.85  | 1     | 1     
    - d, f  | 0.35  | 1     | 1     | 1
    - Electrons cannot 'affect' themselves. Electrons in the same energy level can, though.
    - Calc _Z.eff_ for Nitrogen electron in 2p subshell
        - (1s2) (2s2 2p3); 5 - 1 (self) = 4 in _n_, 2 in _n.1_
        - _S_: 4 \* 0.35 + 2 \* 0.85 = 3.1
        - _Z.eff_ 
            = _Z_ - _S_ 
            = 7 (charge from protons) - 3.1 (shielding) 
            = 7 - 3.1 
            = 3.9
    - Calc _Z.eff_ for Carbon electron in outer subshell
        - (1s2) (2s2 2p2); 4 - 1 = 3 in outer; 2 in inner
        - _S_ = 3 \* 0.35 + 2 \* 0.85 = 2.75
        - _Z.eff_
            = 6 - 2.75
            = 3.25
    - Calc _Z.eff_ for Magnesium in outer subshell
        - (1s2) (2s2 2p6) (3s2); 2 - 1 = 1 in _n_; 8 in _n-1_; 2 in _n-2_
        - _S_ = 1 \* 0.35 + 8 \* 0.85 + 2 \* 1
        - _Z.eff_
            = 12 - 9.15
            = 2.85
    - Calc _Z.eff_ for Zinc in outer subshell
         - (1s2) (2s2 2p6) (3s2 3p6 3d10) (4s2); 2 - 1 = 1 in _n_; 18 in _n-1_; 8 in _n-2_; 2 in _n-3_
         - _S_ = 1 \* 0.35 + 18 \* 0.85 + 8 \* 1 + 2 \* 1 = 25.65
         - _Z.eff_
            = 30 - 25.65 = 4.35
    - Calc _Z.eff_ for Tellurium in outer subshell
        - (1s2) (2s2 2p6) (3s2 3p6 3d10) (4s2 4p6 4d10) (5s2 5p4); 6 - 1 = 5 in _n_; 18 in _n-1_; 18 in _n-2_; 8 in _n-3_; 2 in _n-4_
        - _S_ = 5 \* 0.35 + 18 \* 0.85 + 18 \* 1 + 8 \* 1 + 2 \* 1 = 45.05
        - _Z.eff_
            = 52 - 45.05
            = 6.95
    - Calc _Z.eff_ for Tellurium in 5s subshell
        - 2 - 1 = 1 in _n_; 18 in _n-1_; 18 in _n-2_; 8 in _n-3_; 2 in _n-4_
        - _S_ = 1 \* 0.35 + 18 \* 0.85 + 18 \* 1 + 8 \* 1 + 2 \* 1 = 43.65
        _ _Z.eff_
            = 52 - 43.65
            = 8.35
