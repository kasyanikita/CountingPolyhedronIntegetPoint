# CountingPolyhedronIntegerPoints

GMP Docs - https://gmplib.org/manual/


$$ td_3(\xi_1, \ldots, \xi_n) = \frac{1}{24}\sum_{i \neq j}\xi_i^2 \xi_j + \frac{1}{8}\sum_{i = 3}^{n}(\xi_i \cdot \sum_{j < k < i}\xi_j\xi_k) $$

$$ td_4(\xi_1, \ldots, \xi_n) = -\frac{1}{720}\sum_{i=1}^{n}\xi_i^4 + \frac{1}{144}\sum_{i < j}\xi_i^2 \xi_j^2 + \frac{1}{48}\sum_{j < k, i \neq j, k}\xi_i^2\xi_j\xi_k + \frac{1}{16}\sum_{m=3, m < k}(\xi_m\xi_k\sum_{i < j < m}\xi_i\xi_j)$$

