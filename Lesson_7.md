# Lesson 7 - Oscillation - 7/31/2022
## oscilation and rotation
* ![image](https://user-images.githubusercontent.com/71202720/182032534-3f5f94e4-2884-4d5b-a37b-2f24a265e0a5.png)


## Spring 
* $F = -kx$, where $x = f(t)$
* F = ma = -kx
* m d (df(t)/dt)/dt = -k f(t)
* $m f(t)'' = -k f(t)$  -- differential equation

* Try and error -- guess 
* An intelligent guess -- Sinusoidal curve 
    * $\sin'(x) = \cos(x)$
    * $\cos'(x) = -\sin(x)$
    * $\sin''(x) = -\sin(x)$
* more
    * $\sin'(\omega x) = \omega \cos(\omega x)$
    * $\sin''(\omega x) = -\omega^2 \sin(\omega x)$
* $f''(t) = - \frac{k}{m} f(t)$
* ->
* $f(t) = \sin(\omega t)$, where $\omega = \sqrt{\frac{k}{m}}$

## Terminology
* T - period (sec)
* f - frequence (/sec -- Hz)
* f = 1/T,   T = 1/f
* $\sin(\omega t)$ 
    * $\omega$ - Angular velocity, (radian/sec)
    * if $\omega t == 2\pi$, $t = 2\pi / \omega$, or $\omega = 2\pi / T$
    * $T = 2\pi / \omega$
    * $f = 1/T = \omega / 2\pi$

## The Spring
* $F = -kx = ma
* $\omega = \sqrt{\frac{k}{m}}$
* $T = 2\pi * \sqrt{\frac{m}{k}}$   <--- [memorize]


## Pendulum
* ![image](https://user-images.githubusercontent.com/71202720/182031738-18e9da21-a95c-45f3-b47d-ee081afac7f4.png)
* Restoration force 
* $F = m g sin(\theta)$
* When $\theta$ is small, $sin(\theta) = \theta$
* $F = mg \theta = m a$ , where $a = f''(x)$
* $x = L \theta$
* $g \theta(t) = -L \theta''(t)$
* $\theta''(t) = -\frac{g}{L} \theta(t)$
* Conclusion, the pendulum position is a sinusoidal function

* $\omega = \sqrt{\frac{g}{L}}$
* $T = 2\pi * \sqrt{\frac{l}{g}}$ <-- [memorize]


## Exercises
1. T = 1/2 kx^2 = 1/2 mv^2 --> v = \sqrt(k/m) x
14: find its equilibrium position where kx = mg,  
    * x = mg / k = 0.1 * 10 / 40 = 1/40
    * T = 2\pi \sqrt{m/k}
16. s = 1/2 g t^2, 10 = 1/2 10 t^2, t = sqrt (2)
