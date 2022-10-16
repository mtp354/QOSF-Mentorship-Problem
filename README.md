# QOSF-Mentorship-Problem
Task 1 for Cohort 6 of the QOSF mentorship program.

The challenge for this task was to construct a quantum integer multiplier circuit. I used the Qiskit framework for this project.
The design I opted for was based on the suggested Ruiz-Perez, Garcia-Escartin paper. Essentially converting the output to the Fourier
basis, performing a series of repeated additions via conditional phase gates and transforming back into the computational basis.
I used the Qiskit provided QFT object, however it would only require simple modification to recreate this from scratch.

I have created a basic runtime analysis to accompany the function to investigate the impact of circuit depth. The results are included.

Thank you for the opportunity to be a part of this program, I have enjoyed the screening task challenge.

- Matthew Prest.
