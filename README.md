# Sum-of-Exponentials-Approximation
This repository records both the weights and exponents of the SOE produced by the [VPMR](https://link.springer.com/article/10.1007/s10915-022-01999-1), a recently developed sum-of-exponentials method.

##  Gaussian kernel  ##
Exponents and weights of the SOE for the Gaussian kernel  $f(x)=e^{-\frac{x^2}{4}}$  with the number of terms $P=9$ and absolute error $10^{-8}$.

![Gaussian_9_terms_1e-8_error](https://github.com/LiangJiuyang/Sum-of-Exponentials-Approximation/tree/main/Screenshots/Gaussian_1e8_9term.png) 

Exponents and weights of the SOE for the Gaussian kernel  $f(x)=e^{-\frac{x^2}{4}}$  with the number of terms $P=16$ and absolute error $6\times 10^{-14}$.

![Gaussian_15_terms_6e-14_error](https://github.com/LiangJiuyang/Sum-of-Exponentials-Approximation/tree/main/Screenshots/Gaussian_6e14_15term.png) 

Exponents and weights of the SOE for the Gaussian kernel $f(x)=e^{-x^2}$ with the number of terms $P=18$ and absolute error $1\times 10^{-15}$.

Weights:
```
5.99673832958228e-06 + 1.68666706190233e-06i	5.99673832964075e-06 - 1.68666706179742e-06i	-0.00128256763349392 - 5.69515998682304e-05i	-0.00128256763349477 + 5.69515998663800e-05i	0.0467989716657016 - 0.0248428082769860i	0.0467989716657026 + 0.0248428082770166i	-0.335267028777594 + 0.757075111679156i	-0.335267028777571 - 0.757075111679353i	-1.99598682670183 - 5.99221164256010i	-1.99598682670221 + 5.99221164256101i	23.9009795446709 + 12.0862363354612i	23.9009795446732 - 12.0862363354632i	-64.0632116678656 + 22.5380203666186i	-64.0632116678705 - 22.5380203666172i	42.9479635779022 - 98.1965284307393i	42.9479635779079 + 98.1965284307392i	2.77886417555933e-16 + 1.05052462423441e-16i	2.77886412307273e-16 - 1.05052680588430e-16i
```
Exponents:
```
4.56160429581067 + 8.10664614462486i	4.56160429581067 - 8.10664614462486i	4.67614751620509 + 6.66817205403247i	4.67614751620509 - 6.66817205403247i	4.75706771210077 + 5.46277771275372i	4.75706771210077 - 5.46277771275372i	4.81739468471801 + 4.37139574323745i	4.81739468471801 - 4.37139574323745i	4.86201933938979 + 3.34750236244862i	4.86201933938979 - 3.34750236244862i	4.89345823682377 + 2.36588612738340i	4.89345823682377 - 2.36588612738340i	4.91338156910332 + 1.41021110952036i	4.91338156910332 - 1.41021110952036i	4.92300187934591 + 0.468589313154398i	4.92300187934591 - 0.468589313154398i	0.0334524767879181 + 0.0245907245253121i	0.0334524767879181 - 0.0245907245253121i
```

##  Remark  ##
If you use these SOE in your work and feel that these approximations are helpful to you, please cite the following paper：

[A kernel-independent sum-of-exponentials method, Z. Gao, J. Liang and Z. Xu, J. Sci. Comput., 93(2022), Article Number: 40.](https://link.springer.com/article/10.1007/s10915-022-01999-1)

If you require further information, for example, the SOE approximation (or the sum-of-Gaussians approximation) for some other kernels which are not include in this repository, please feel free to contact us. Either English or Chinese can be used.
```
Email address: 1270157606gzx@sjtu.edu.cn, liangjiuyang@sjtu.edu.cn, xuzl@sjtu.edu.cn.
```
