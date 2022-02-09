  # real-time shadow

## shadow mapping

- 两趟算法
  - the light pass generates the SM - depth texture
  - the camera pass uses the SM

###  不等式

- schwarz 不等式 
- minkowski 不等式

在实时渲染中将不等式当做约等使用

RTR中一个重要的约等式：
$$
\int_\Omega f(x)g(x)dx \approx \frac{\int_{\Omega}f(x)dx}{\int_\Omega dx} \cdot \int_\Omega g(x)dx 
$$


###   PCSS percentage closer soft shadows  58 mins 处



