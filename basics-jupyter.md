# Matplotlib Demo
Norah Smith
2021-05-22

<details class="code-fold">
<summary>Code</summary>

``` python
import numpy as np
import matplotlib.pyplot as plt

r = np.arange(0, 2, 0.01)
theta = 2 * np.pi * r
fig, ax = plt.subplots(subplot_kw={'projection': 'polar'})
ax.plot(theta, r)
ax.set_rticks([0.5, 1, 1.5, 2])
ax.grid(True)
plt.show()
```

</details>
<div id="fig-polar">

![](basics-jupyter_files/figure-commonmark/fig-polar-output-1.png)


Figure 1: A line plot on a polar axis

</div>
<details class="code-fold">
<summary>Code</summary>

``` python
print('hello, world')
```

</details>

    hello, world

<details class="code-fold">
<summary>Code</summary>

``` python
testvar='aaa'
```

</details>
<details class="code-fold">
<summary>Code</summary>

``` python
print(f'{testvar=}')
```

</details>

    testvar='aaa'
