### NOTE: For better viewing experience, please install [MathJax Plugin for Github](https://chrome.google.com/webstore/detail/github-with-mathjax/ioemnmodlmafdkllaclgeombjnmnbima) for Chrome or some other plugin/extension that will enable MathJax for your browser.

## articles: https://plus.maths.org/content/fourier-transforms-images

the sounds we hear are waves, results of vibrations.
we can get a visual representation of the sound by plotting vibrations (their intensity, or pressurem of the wave over time).

any sound wave (repeating function), can be broken up into a number of sine waves of various frequencies and amplitudes (intensities).
that means a sound wave, or any signal varying over time, can be expressed as the sum of its constituent sine waves.
this expression is called ***Fourier transform*** of that signal.

> ![Fourier transform example](https://plus.maths.org/content/sites/plus.maths.org/files/articles/2017/carola/Fourier_transform.gif)
> > The function f varies in time – representing a sound wave. The Fourier transform process takes f and decomposes it into its constituent sine waves, with particular frequencies and amplitudes. The Fourier transform is represented as spikes in the frequency domain, the height of the spike showing the amplitude of the wave of that frequency.

we can think of image as a varying function across the 2-dimensional space of it.
gray scale image contains pixels each of which has a value $\in \left[0, 255\right]$.
the value represents how dark that pixel is (or also how bright that pixel is).
we can modeling an image as a function: $I\left(x, y\right)$, where x and y are respectively the coordinate on the x (horizontal) and y (vertical) axis.



[//]: # (<img src="https://render.githubusercontent.com/render/math?math=e^{i \pi} = -1">)
[//]: # ($x_{1,2} = \frac{-b \pm \sqrt{b^2-4ac}}{2b}.$)
