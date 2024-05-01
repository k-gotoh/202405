##GitHubでのLaTexの実験

\\\\は使用できずspace２つで代用
  
$$
\frac{\partial}{\partial v}( \frac{1}{2} \sum_{i=1}^n (y_{(i)} - v)^2
$$

$$
= \frac{\partial}{\partial v}( \frac{1}{2} \sum_{i=1}^n (y_{(i)}^2 -2y_{(i)}v + v^2)
$$

$$
=  \frac{1}{2} \sum_{i=1}^n ( -2y_{(i)} + 2v)
$$

$$
= \sum_{i=1}^n (-y_{(i)} +v)
$$

$$
= \sum_{i=1}^n ( v-y_{(i)})
$$

### 2024年4月26日 ロジスティクス回帰 ###
$$
尤度関数
$$

$$
log L(\theta) = log \prod_{i=1}^nP(y^{(i)} = 1 |x^{(i)})^{v^{(i)}}P(y^{(i)} = 0 | x^{(i)})^{1-y^{(i)}}
$$

$$
目的関数
$$

$$
log L(\theta) =  \sum_{i=1}^n y^{(i)} log  \frac{1}{1+\exp(-\theta^Tx)}+(1-y^{(i)})log(1 - \frac{1}{1+\exp(-\theta^Tx)})
$$
