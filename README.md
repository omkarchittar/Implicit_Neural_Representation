Implicit neural representations is about parameterizing a continuous differentiable signal with a neural network. The signal is encoded within the neural network, providing a possibly more compact representation or allowing smooth parameter-based manipulation of that signal. This is a type of regression problem.

Applications of these learned representations range from simple compression, to 3D scene reconstruction from 2D images, super-resolution, semantic information inference, etc.

CPPN is an early example of a implicit neural representation implementation mainly used for pattern generation . It uses a neural network to generate patterns parameterized by two (or more) coordinates.

Usually a coordinate system is used as input for the network which will attempt to produce the signal’s value at each coordinate.

# Implicit neural representations for high frequency data
To encode potentially high frequency data such as sound or images, it is much more efficient to start from periodic feature transformations. This can be achieved with periodic activation functions such as sinusoidal representation networks or SIRENs (Sitzmann et al. 2020) or by using a Fourier feature mapping (Tancik et al. 2020) .
