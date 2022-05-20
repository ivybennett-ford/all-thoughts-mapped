Low Noise Amplifiers

## Basics of Noisy Network Theory
- Thevenin: Any two-port network containint sources can be represented by the network with sources added to the terminals
	- Series voltage or shunt current
- Thevenin is independent of waveforms or quantity of internal sources
- Noises of any source (thermal, shot, avalanche, and so on) in a network can be represented by two terminal noise sources
	- Complex correlation coefficient $\rho$ must be specified between two sources, for 4 real numbers (parameters) to describe all interactions
	- There are many sets of such 4 numbers; the choice depends on what is known about the internal sources, and on the application
- Most common Microwave Noise Representation
	- Noise of a microwave amplifier is usually specified by the noise temperature, $T_{n}$, added to the noise source generator
	- Noise figure of a microwave amplifier:
		$NF = 10log(1 + T_{n}/290)$
	- The noise temperature $T_{n}$ is a function of the source impedance $Z_{s}$
	- Key noise parameter, $Z_{opt}$, minimizes {T_n}$ to give third parameter, $T_{min}$
	- Fourth parameter is usually $R_{n}$ or $N$, to specify the increase in noise if $Z_{s} \neq Z_{opt}$

#microwave-engineering #electronics #radio-astronomy #noise