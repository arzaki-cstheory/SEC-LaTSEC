Use the updated LaTSEC-Parameter-Selection-v2.2-fixedtailbound.ipynb for parameter search. The tail bound has been fixed.
The LaTSEC-Parameter-Selection-v2.2-fixedtailbound.ipynb supersedes LaTSEC-Parameter-Selection-v2.1-updatedbound.ipynb.
Refer to SEC-Parameter-Selection-v1.ipynb or SEC-Parameter-Selection-v1-q32.ipynb for the parameter search restricted to the privacy of SEC.
SEC-Parameter-Selection-v1.ipynb uses the moduli from the threshold signature, whereas SEC-Parameter-Selection-v1-q32.ipynb uses the fix 32 bit modulus.
The lattice-estimator used is: 27a581b.
q is the largest NTT prime below 2^b_q (ceil(lg q) = b_q).