# MiniTorch Module 1  

<img src="https://minitorch.github.io/_images/match.png" width="100px">

* Docs: https://minitorch.github.io/

* Overview: https://minitorch.github.io/module1.html

This module requires `operators.py` and `module.py` from Module 0

```
cp ../Module-0/operators.py ../Module-0/module.py minitorch/
```


* Tests:

```
python run_tests.py
```
![Simple.png](images//Simple.png)

```
Setting up a new session... SIMPLE 500 EPOCHS

Epoch  0  loss  33.827013303316406 correct 30
Epoch  10  loss  32.84253095185056 correct 30
Epoch  20  loss  31.071647776975524 correct 33
Epoch  30  loss  27.299019461166836 correct 44
Epoch  40  loss  21.120097787343344 correct 47
Epoch  50  loss  15.291804728677462 correct 48
Epoch  60  loss  11.079394347459196 correct 50
Epoch  70  loss  8.603220383432111 correct 50
Epoch  80  loss  8.143850084911985 correct 48
Epoch  90  loss  12.261238431928932 correct 43
Epoch  100  loss  8.41147943452198 correct 46
Epoch  110  loss  5.710749260019077 correct 49
Epoch  120  loss  4.84737394087706 correct 49
Epoch  130  loss  3.7916331146681355 correct 50
Epoch  140  loss  2.992457838235576 correct 50
Epoch  150  loss  2.6552429498185117 correct 50
Epoch  160  loss  2.3800274925409517 correct 50
Epoch  170  loss  2.1800548473746955 correct 50
Epoch  180  loss  2.0300372209096507 correct 50
Epoch  190  loss  1.8569688798287685 correct 50
Epoch  200  loss  1.7093400827433618 correct 50
Epoch  210  loss  1.5813454653744392 correct 50
Epoch  220  loss  1.4810687145210406 correct 50
Epoch  230  loss  1.394595383629208 correct 50
Epoch  240  loss  1.317410074461596 correct 50
Epoch  250  loss  1.2473360218625993 correct 50
Epoch  260  loss  1.1834605194320258 correct 50
Epoch  270  loss  1.125023141177695 correct 50
Epoch  280  loss  1.0713841079492537 correct 50
Epoch  290  loss  1.0220005699391839 correct 50
Epoch  300  loss  0.9764084678894003 correct 50
Epoch  310  loss  0.9342084470265384 correct 50
Epoch  320  loss  0.8950547745084043 correct 50
Epoch  330  loss  0.8586465185308051 correct 50
Epoch  340  loss  0.8247204542085901 correct 50
Epoch  350  loss  0.7930453043268916 correct 50
Epoch  360  loss  0.7634170237223004 correct 50
Epoch  370  loss  0.7356549080584027 correct 50
Epoch  380  loss  0.7095983600021045 correct 50
Epoch  390  loss  0.6853879725296456 correct 50
Epoch  400  loss  0.662685497002138 correct 50
Epoch  410  loss  0.641368597281683 correct 50
Epoch  420  loss  0.6209825189866022 correct 50
Epoch  430  loss  0.6020496210200272 correct 50
Epoch  440  loss  0.5841983861574779 correct 50
Epoch  450  loss  0.5673002979484504 correct 50
Epoch  460  loss  0.5512565302955936 correct 50
Epoch  470  loss  0.5359944894079984 correct 50
Epoch  480  loss  0.5214556118246244 correct 50
Epoch  490  loss  0.507589835401413 correct 50

Process finished with exit code 0
```

![Xor.png](images//Xor.png)

```
Setting up a new session... XOR 500 EPOCHS

Epoch  0  loss  79.68839328658335 correct 23
Epoch  10  loss  32.029231998330495 correct 29
Epoch  20  loss  29.995507376961285 correct 38
Epoch  30  loss  28.082957150985052 correct 39
Epoch  40  loss  26.28898945723006 correct 44
Epoch  50  loss  24.72211278252818 correct 42
Epoch  60  loss  22.642244711493703 correct 41
Epoch  70  loss  20.124404382206293 correct 43
Epoch  80  loss  19.576863219782467 correct 43
Epoch  90  loss  18.320859657323684 correct 43
Epoch  100  loss  16.14247528937387 correct 45
Epoch  110  loss  15.089980550373866 correct 45
Epoch  120  loss  14.503441182182426 correct 44
Epoch  130  loss  12.036770067411268 correct 45
Epoch  140  loss  15.130196158316812 correct 44
Epoch  150  loss  9.420424942561086 correct 47
Epoch  160  loss  13.76717541475813 correct 43
Epoch  170  loss  9.2618544850719 correct 47
Epoch  180  loss  10.108844867387225 correct 47
Epoch  190  loss  8.892713161656122 correct 47
Epoch  200  loss  9.370246167980655 correct 47
Epoch  210  loss  6.2531072792537605 correct 49
Epoch  220  loss  7.8150481239440905 correct 48
Epoch  230  loss  6.2990972278817035 correct 48
Epoch  240  loss  5.006823580238938 correct 50
Epoch  250  loss  24.504382153143695 correct 41
Epoch  260  loss  4.682943894195033 correct 50
Epoch  270  loss  3.906930323628362 correct 50
Epoch  280  loss  3.373768721729277 correct 50
Epoch  290  loss  3.6543449961639194 correct 50
Epoch  300  loss  30.249581526798984 correct 41
Epoch  310  loss  16.046273609510383 correct 42
Epoch  320  loss  3.0562552989174057 correct 50
Epoch  330  loss  2.6567547808390577 correct 50
Epoch  340  loss  2.395018706568034 correct 50
Epoch  350  loss  2.221184681038281 correct 50
Epoch  360  loss  2.0811273631183376 correct 50
Epoch  370  loss  1.9592573732263319 correct 50
Epoch  380  loss  1.8522906335489164 correct 50
Epoch  390  loss  1.7524637233402411 correct 50
Epoch  400  loss  1.6902082494938742 correct 50
Epoch  410  loss  1.648876137747731 correct 50
Epoch  420  loss  2.0799353395849844 correct 50
Epoch  430  loss  35.39391341039688 correct 41
Epoch  440  loss  1.5693834382579466 correct 50
Epoch  450  loss  1.444351614576377 correct 50
Epoch  460  loss  1.358308169936939 correct 50
Epoch  470  loss  1.2903267941535501 correct 50
Epoch  480  loss  1.2289239164427919 correct 50
Epoch  490  loss  1.1710908289320583 correct 50

Process finished with exit code 0
```



