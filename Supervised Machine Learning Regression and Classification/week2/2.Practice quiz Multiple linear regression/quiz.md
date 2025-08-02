![pic](1.png)

The answer is 30

![pic](2.png)

Shorter: np.dot(w, x)

More easily: the lib takes care of vectorized optimization such as SIMD

Run faster: Utilize the capability of GPU or modern  CPU

![pic](3.png)

Increase the learning rate is indeed an approach, but double it for twice as fast might not right because bigger learning rate may cause to divergence.

![pic](4.png)

Polynomial regression introduce square or cubed equations for model, which makes the prediction as a curve.
