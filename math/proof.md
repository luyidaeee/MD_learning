# 高等数学

## 罗尔中值定理

>函数 $f(x)$ 在 $[a,b]$ 上连续，在$（a,b）$上可导，若$f(a)=f(b)$ 则 $\exists\xi\in(a,b),s.t.f'(\xi)=0$ 

$proof:$   
$$\exists x_0 \in \big(a,b) s.t.\forall x \in (a,b),f(x)\leq f(x_0)$$
由极限保号性知
$$ \lim\limits_{{x \rightarrow x_0}} f(x)\leq  \lim\limits_{{x \rightarrow x_0}} f(x_0) $$
$$\Rightarrow  \lim\limits_{{x \rightarrow x_0}} f(x)-f(x_0) \leq 0 $$

$$ \Rightarrow  \lim\limits_{{x \rightarrow x_0^+}} \frac{f(x)-f(x_0) }{x-x_0}\leq 0 ,   \lim\limits_{{x \rightarrow x_0^-}} \frac{f(x)-f(x_0) }{x-x_0}\geq 0 $$  

$$ \Rightarrow \lim\limits_{{x \rightarrow x_0}} \frac{f(x)-f(x_0) }{x-x_0} 
= 0 = f\rq(x_0)$$  


## 拉格朗日中值定理
>函数 $f(x)$ 在 $[a,b]$ 上连续，在$（a,b）$上可导，则
 $$\exists\xi\in(a,b)\,,s.t.\,, \frac{f(a)-f(b)}{a-b}=f\rq(\xi)$$
 
$proof:$   
