# 1.1 群、子群、陪群

$$\mathbb{R}$$实数集有两个操作\(1\)加法： $$\mathbb{R}\times \mathbb{R}\rightarrow \mathbb{R}$$ （加法）\(2\)乘法： $$\mathbb{R}\times \mathbb{R}\rightarrow \mathbb{R}$$ （乘法）使 $$\mathbb{R}$$ 通过加法满足阿尔贝群的性质，并且通过乘法使$$\mathbb{R}-\left \{ 0 \right \}= \mathbb{R}^{\ast}$$  成为一个阿尔贝群。

**定义1.1  群是一个具有二元操作的集合G 二元操作：** $$G\times G\rightarrow G$$ 是对于每对 $$a,b\in G$$的元素都会关联一个 $$a\cdot b\in G$$ 的元素，并且具有如下特性： $$\cdot $$ 是 $$e\in G$$ 的一个联合元素，并且G中的每个元素都是可逆的。 更准确的说，这意味着以下方程式适用于所有 $$a,b,c\in G$$ 的元素；

$$\left ( G1 \right ) a\cdot \left ( b\cdot c \right )= \left ( a\cdot b \right )\cdot c$$（结合律）

$$\left ( G2 \right ) e\cdot a= a\cdot e= a$$（同一性）

$$\left ( G3 \right ) $$ 对于每个 $$a\in G$$ 的元素，必定存在 $$a^{-1}\in G$$ 且满足 $$a\cdot a^{-1}= a^{-1}\cdot a= e$$（可逆性）

           如果对于所有 $$a,b\in G$$ 且满足 $$a\cdot b= b\cdot a$$ 的集合G是阿贝尔的或者可交换的。

      一个集合M总共就有一个方法 $$\cdot $$ ： $$M\times M\rightarrow M$$ 并且存在一个元素e仅仅满足 $$\left ( G1 \right )$$ 和 $$\left ( G2 \right )$$ ，这种集合称为幺半群。例如，通过加法属于自然数的集合 $$\mathbb{N}= \left \{ 0,1...,n,... \right \}$$ 是一个（可交换的）幺半群。但是，这个集合并不是群。

一些群的例子如下：

**例子1.1**

1.用恒等元素0通过加法使整数集 $$\mathbb{Z}= \left \{ ...,-n,...,-1,0,...,n,... \right \}$$ 成为一个阿贝尔群。然而，通过乘法使得 $$\mathbb{Z}^{\ast }= \mathbb{Z}-\left \{ 0 \right \}$$ 不是一个群。

2.用恒等元素0通过加法使有理数 \( $$p,q\in \mathbb{Z}$$ 且 $$q\neq 0$$ 的分数 $$p/q$$ \)$$\mathbb{Q}$$ 集合成为一个阿贝尔群。用恒等元素1通过乘法使 $$\mathbb{Q}^{\ast }= \mathbb{Q}-\left \{ 0 \right \}$$ 也成为一个阿贝尔群。

3.通过恒等函数 $$id_{S}$$ 的恒等元素给任何一个非空集合S，通过组合方法\(f和g的乘积是 $$g\circ f$$ 的组合\)， $$\int :S\rightarrow S$$ 映射的集合，常常称为S的组合，是一个群。只要S有两个以上的元素，这个群就不是阿贝尔群。 $$S=\left \{ 1,...,n \right \}$$ 集合的排列群常常表示为 $$S_{n}$$ 和称为n个元素上的对称群。

4.对于任何一个 $$p\in \mathbb{N}$$ 的正整数， $$\mathbb{Z}$$ 上关系的定义表示 $$m\equiv n$$ \(mod p\),如下: 存在 $$k\in \mathbb{Z}$$，当 $$m-p= kp$$，则 $$m\equiv n$$ \(mod p\) 。

读者可以明显的看出这是一个相等关系，并且，除此之外，它与加法和乘法兼容，这意味着如果 $$m_{1}\equiv n_{1}$$ \(mod p\)和 $$m_{2}\equiv n_{2}$$ \(mod p\)，那么 $$m_{1}+m_{2}\equiv n_{1}+ n_{2}$$ \(mod p\)和 $$m_{1}m_{2}\equiv n_{1}n_{2}$$ \(mod p\)。因此，我们可以定义一个加法和乘法的等价类的集合（mod p）:

$$\left [ m \right ]+\left [ n \right ]= \left [ m+n \right ]$$ 和 $$\left [ m \right ]\cdot \left [ n \right ]= \left [ m\cdot n \right ]$$ 

读者可以明显的看出使用 $$\left [ 0 \right ]$$ 作为0通过剩余类\(mod p\)的加法生成阿贝尔群结构。这个群表示为 $$\mathbb{Z}/p\mathbb{Z}$$ 。

5. $$n\times n$$ 的集合的可逆矩阵通过 $$\mathbb{I}_{n}$$恒等矩阵的恒等元素和实\(复\)数集的矩阵乘法是一个群。 这个群称为一般线性群和常常表示为 $$GL\left ( n,\mathbb{R} \right )$$ 或者 $$GL\left ( n,\mathbb{C}\right )$$ 。





           



