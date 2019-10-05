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

6.$$n\times n$$ 的集合的可逆矩阵A通过 $$\mathbb{I}_{n}$$恒等矩阵的恒等元素和实\(复\)数集的矩阵乘法是一个群。这个群称为特殊线性群和常常表示为 $$SL\left ( n,\mathbb{R} \right )$$ 或者 $$SL\left ( n,\mathbb{C}\right )$$ 。

7.$$n\times n$$ 的矩阵Q通过$$\mathbb{I}_{n}$$恒等矩阵的恒等元素和实数集的矩阵乘法，比如 $$\mathbb{Q}\mathbb{Q}^{T}= \mathbb{Q}^{T}\mathbb{Q}=\mathbb{I}_{n}$$是一个群 ；这样就有了 $$\mathbb{Q}^{-1}= \mathbb{Q}^{T}$$ 。这个群被称为特殊正交群或旋转群，常常以 $$SO_{(n)}$$ 进行表示。

除了 $$SO_{\left ( 2 \right )}$$ 是阿贝尔群\( $$O_{\left ( 2 \right )}$$是非阿贝尔群\)，当 $$n\geq 2$$时 $$\left ( 5-8 \right )$$ 对应的群是非阿贝尔群。

通常用+表示阿贝尔群G的运算，在这种情况下， $$a\in G$$ 的逆 $$a^{-1}$$ 用 $$-a$$ 表示。

群的恒等元素是唯一的。实际上，我们可以证明一个更普遍的事实：

**命题 2.1** 如果一个二进制操作 $$\therefore $$$$M\times M\rightarrow M$$ 是结合的,如果 $$e^{'}\in M$$ 是左恒等的和 $$e^{"}\in M$$ 是右恒等的，那就可以得出:

对于所有在 $$a\in M$$条件下，且  $$e^{'}\cdot a= a$$ （G21）

和

对于所有在 $$a\in M$$条件下，且 $$a\cdot e^{"}= a$$ （G2r）

则可得出 $$ e^{"}= e^{'}$$ 

证明：

如果我们在等式（G21）中假设 $$a= e^{"}$$ ，我们可以得出 $$e^{'}\cdot e^{"}= e^{"}$$ 

如果我们在等式（G2r）中假设 $$a= e^{'}$$，我们可以得出 $$e^{'}\cdot e^{"}= e^{'}$$ 

因此可得出先前命题的结论， $$e^{'}= e^{'}\cdot e^{"}= e^{"}$$ 。

        命题2.1隐含的表达了一个幺半群的恒等元素是唯一的，而且每个群都是一个幺半群，一个幺半群中的恒等元素是唯一的。除此之外，在群中的每个元素都含有一个唯一的逆。这样就得出一个普遍的结论： 命题2.2 在包含有恒等元素e的幺半群M中，如果存在a\in M 的元素中存在a^{'}\in M 的左逆和a^{"}\in M 的右逆，那就意味着 a^{'}\cdot a= e \(G31\) 和 a^{"}\cdot a= e \(G3r\) 由此可得出a^{'}= a^{"} 证明，由\(G31\)和e是一个恒等元素，可以得出 \left \( a^{'}\cdot a \right \)\cdot a^{"}= e\cdot a^{"}= a^{"} 同理，由\(G3r\)和e是一个恒等元素，可以得出 a^{'}\cdot \left \( a \cdot a^{"} \right \)= a^{'}\cdot e= a^{'} 然而，如果M是幺半群，\cdot 操作是组合操作，所以 a^{'}= a^{'}\cdot \left \( a\cdot a^{"} \right \)= \left \( a^{'}\cdot a \right \)\cdot a^{"}= a_{n} 说明：公理（G2）和（G3）可以通过仅要求（G2r）（存在权同一性）和（G3r）（每个元素都存在右逆）（或（G21）和（ G3L））。证明组公理（G2）和（G3）遵循（G2r）和（G3r）是一个很好的练习。 定义 2.2 假设群G的元素中有一个有限数n,我们可以说G是阶n的一个群。如果集合G是无限的，我们可以说集合G有无限阶。一个群的阶常常表示为\left \| G \right \|。 存在一个群G，对于任何R,S\in G的子群，我们使 RS= \left { r\cdot s\|r\in R,s\in S \right }。 尤其是，对于任何g\in G的子群，如果R= \left { g \right },我们可以写成Rg= \left { r\cdot g\|r\in R \right }， 并且同理，如果S= \left { g \right }，我们可以写成Rg= \left { r\cdot g\|r\in R \right }。 从现在开始，我们将会删除掉乘法符号并且用g_{1}g_{2}替换g_{1}\cdot g_{2}。 定义 2.3 使G是一个群。对于任意的g\in G，定义为L_{g}，对于所有a\in G的元素和R_{g}，通过L_{g}\(a\)= ga表示g的左转化；对于所有a\in G的元素通过R_{g}\(a\)= ag表示g的右转化。 接下来的是经常使用到的例子。 命题 2.3 给定的一个群G,L_{g}和R_{g}的转化是双射的。 证明 我们只表述L_{g}的证明过程，R_{g}的证明过程类似。 如果L_{g}\(a\)= L_{g}\(b\)，那么ga= gb，并且在左边乘以g^{-1}，我们可以得到a= b，所以L_{g}是内射的。对于任意的b\in G，且L_{g}\(g^{-1}b\)= gg^{-1}b=b，所以L_{g}是满射的。因此，L_{g}是双射的。 定义 2.4 给定一个群G,一个G子群的子集合H \(1\)群G的恒等元素e常常属于H\(e\in H\)； \(2\)对于所有h_{1},h_{2}\in H，我们可以得出h_{1}h_{2}\in H； \(3\)对于所有h\in H，我们可以得出h^{-1}\in H。 以下命题的证明留作练习。 命题 2.4 给定一个群G,一个群G的一个子群的子集合H\subseteq G的H,如果H是非空的，并且当h_{1},h_{2}\in H时，可得出h_{1}h_{2}^{-1}\in H。 如果组G是有限的，则可以使用以下准则。 命题 2.5 给定一个有限的集合G,G子群的一个H\subseteq G的子集合 \(1\)e\in H \(2\)H在乘法下是闭合的。 证明 我们只需要证明定义2.4的条件（3）成立即可。对于任何属于a\in H,在左转换L_{a}后是双射的，它对H的限制是内射的，因为H是限制的，所以它也是双射的。因为e\in H，因此存在唯一的b\in H使得L_{a}\(b\)=ab=e。然而，如果a^{-1}是群G中的a元素的逆，我们仍然可以得到L_{a}\(a^{-1}\)=aa^{-1}=e，并且通过L_{a}的注入性，我们可以得出a^{-1}=b\in H。 例 2.2 1.对于任何n\in \mathbb{Z}，集合n\mathbb{Z}=\left { nk\|k\in \mathbb{Z} \right }是群\mathbb{Z}的子群。 2.矩阵集合GL^{+}\(n,\mathbb{R}\)=\left { A\in GL\(n,\mathbb{R}\)\|det\(A\)&gt;0 \right }是群GL\(n,\mathbb{R}\)的子群。 3.群SL\(n,\mathbb{R}\)是GL\(n,\mathbb{R}\)的子群。 4.群O\(n\)是群GL\(n,\mathbb{R}\)的子群。 5.群SO\(n\)是群O\(n\)的子群，并且是SL\(n,\mathbb{R}\)的子群。 6. 不难看出每个2\times 2的旋转矩阵R\in SO\left \( 2 \right \)可以表述为R=\begin{pmatrix} cos\theta & -sin\theta \ sin\theta & cos\theta \end{pmatrix}，满足 0\leq \theta &lt; 2\pi。 通过将矩阵R=\begin{pmatrix} cos\theta & -sin\theta \ sin\theta & cos\theta \end{pmatrix}看作\begin{pmatrix} cos\theta & -sin\theta &0 \ sin\theta &cos\theta &0 \ 0& 0 & 1 \end{pmatrix}，可以将SO\(2\)被认为是SO\(3\)的一个子群。 7.2\times 2的上三角矩阵形式\begin{pmatrix} a &b \ 0& c \end{pmatrix} a,b,c\in \mathbb{R},a,c\neq 0 是群GL\(2,\mathbb{R}\)的子群。 8.由四个\begin{pmatrix} \pm 1 &0 \ 0& \pm 1 \end{pmatrix} 组成的集合V是群GL\(2,\mathbb{R}\)的一个子群，并称为克莱因四元组。 定义 2.5 如果H是G的一个子群，并且g\in G是一个元素，gH格式的集合被称为在群G中H的左陪集和Hg格式的集合被称为在群G中H的右陪集。H的左陪集\(resp.右陪集\)产生的等价关系\sim 定义如下： 对于所有满足g_{1},g_{2}\in G，当g_{1}H= g_{2}H,则g_{1}\sim g_{2} \(resp.当Hg_{1}= Hg_{2}，则g_{1}\sim g_{2}\)。显然，\sim是等价关系。 现在，我们可以得出一下结论： 命题 2.6 给出一个群G和群G的任意一个子群H,对于所有满足g_{1},g_{2}\in G，如果g_{2}^{-1}\in H，且g_{2}^{-1}g_{1}H= H，可以得出g_{1}H= g_{2}H。 证明 如果我们在g_{1}H和g_{2}H都应用双射L_{g_{2}^{-1}}，我们可以得出L_{g_{2}^{-1}}\(g_{1}H\)= g_{2}^{-1}g_{1}H和L_{g_{2}^{-1}}\(g_{2}H\)= H，因此如果g_{2}^{-1}g_{1}H= H，那么可得出g_{1}H= g_{2}H。如果g_{2}^{-1}g_{1}H= H且1\in H我们可以得出g_{2}^{-1}g_{1}\in H。相反，如果g_{2}^{-1}g_{1}\in H且H是一个群，L_{g_{2}^{-1}g_{1}}的左转换是H的一个双射，所以g_{2}^{-1}g_{1}H= H.因此如果g_{2}^{-1}g_{1}\in H，那么g_{2}^{-1}g_{1}H= H。 因此，g\in G的一个元素的等价类为陪集gH\(表示为Hg\)。因此L_{g}是H和gH之间双射，陪集gH都含有共同的基数。图L_{g^{-1}}\circ R_{g}是gH左陪集和Hg右陪集的一个双射，所以他们常常含有相同的基数。来源于群G的一个切分子群会表示不同的陪群gH,概括如下： 命题 2.7 \(拉格朗日\) 对于任意的一个有限群G和任意一个群G的子群H,群H的阶h除以群G的阶n. 定义 2.6 给定一个有限群G和群G的一个子群H,如果n= \left \| G \right \|和h= \left \| H \right \|，那么n/h的比可以通过\(G:H\)表示，并且称为群G中群H的索引。 索引\(G:H\)是群G中群H的左\(右\)陪集数。命题 2.7可以声明为\left \| G \right \|= \(G:H\)\left \| H \right \|。 群G\(一般而言，不是一个群\)中群H的左陪集集合可以记作G/H。G/H的“点”是由陪集中所有的元素合并为一个元素的“崩溃”获得的。 例 2.3 1.假设任意一个正整数n,并且\(通过加法\)n\mathbb{Z}为\mathbb{Z}的子群。 0的陪集是集合\left { 0 \right }，并且m\in \mathbb{Z}的任意一个非零的陪集是m+n\mathbb{Z}= \left { m+nk\|k\in \mathbb{Z} \right }。 用m除以n,对于例如0\leq r\leqslant n-1的特殊的r,可以得出m= nq+1。但是接下来我们会发现r是m+n\mathbb{Z}陪集的最小正元素。这 就表示这里有一个群\mathbb{Z}的子群n\mathbb{Z}的陪集和剩余模\left { 0,1,...,n-1 \right }的陪集或等同于\mathbb{Z}/n\mathbb{Z}的一个映射。 2.GL\(n,\mathbb{R}\)中SL\(n,\mathbb{R}\)的陪集是ASL\(n,\mathbb{R}\)= \left { AB\|B\in SL\(n,\mathbb{R}\) \right },A\in GL\(n,\mathbb{R}\)的矩阵集合。 因此A是可逆的，det\(A\)\neq 0，并且如果det\(A\)&gt;0和A= \(-det\(A\)\)^{1/n}\(\(-det\(A\)\)^{-1/n}A，且det\(A\)&lt;0，我们可以表示为A= \left \( det\(A\) \right \)^{1/n} \(\(det\(A\)\)^{1/n}A\)。如果det\(A\)&gt;0，-\(-det\(A\)\)^{-1/n}A\in SL\(n,\mathbb{R}\)和det\(A\)0,那么\(det\(A\)\)^{1/n}I_{n}，如果det\(A\)&lt;0,那么-\(-det\(A\)\)^{1/n}I_{n} 的矩阵。 从而可以得出GL\(n,\mathbb{R}\)中的SL\(n,\mathbb{R}\)的陪集和\mathbb{R}的双射。 3.GL^{+}\(n,\mathbb{R}\)中的SO\(n\)的陪集是ASO\(n\)= \left { AQ\|Q\in SO\(n\) \right },A\in GL^{+}\(n,\mathbb{R}\)的矩阵集合。 她可以表示为\(对矩阵使用极性形式\)GL^{+}\(n,\mathbb{R}\)中SO\(n\)的陪集合和n\times n维的对称集合，正矩阵，定矩阵的一个双射；这些是特征值严格为正的对称矩阵。 4.SO\(3\)中的SO\(2\)的陪集是QSO\(2\)= \left { QR\|R\in SO\(2\) \right },Q\in SO\(3\)矩阵的集合。



\*\*\*\*



           



