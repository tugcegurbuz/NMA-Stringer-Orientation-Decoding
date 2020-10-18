# NMA-Stringer-Orientation-Decoding

Neuromatch Academy Summer School Project: How Behavior Affects Visual Processing In Mouse V1 Area?
Busra Tugce Gurbuz, Zhewen He, Andrey Bukharev

T.A.: Arash Ashrafnejad

Mentors: Joshua Glaser, Kohitij Kar

Project Description:

Scientific question: Can we decode the perceived orientation information from the V1 area using calcium imaging data during mouse running behavior?

Brief scientific background: As described in Stringer et al., (2019), mainly two types of signals are encoded in V1, namely the sensory and behavioral signals. Here, we propose a decoding approach to understand how behavioral signals impact orientation decoding in the V1 area.

Analysis: We separated our data into moving and not moving trials by using standard error of the mean of running data as a threshold. To reduce the dimension of our data to 200, we performed PCA. Then, applied linear regression (with and without PCA), SVM approach (without PCA), and tried feedforward neuronal network (with PCA) for both moving and not moving data.

Conclusions: We observed that moving models predict perceived orientation better, which means that moving behavior somehow facilitates orientation perception. The next step might be explaining how moving facilitates orientation perception by using a mechanistic model.
