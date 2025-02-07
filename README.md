# 参考
- [线性代数的本质-3Blue1Brown中文配音](https://www.bilibili.com/video/BV1ib411t7YR?p=1)[ | 中文字幕](https://www.bilibili.com/video/BV1ys411472E)[ | 英文版](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)[ | 文字版](https://o1zys.github.io/2018/01/03/EssenceOfLinearAlgebra/)
- [麻省理工公开课：线性代数视频中文字幕](https://open.163.com/newview/movie/courseintro?newurl=%2Fspecial%2Fopencourse%2Fdaishu.html)[ | 英文原版视频](https://ocw.mit.edu/courses/mathematics/18-06-linear-algebra-spring-2010/)[ | A 2020 Vision of Linear Algebra](https://ocw.mit.edu/resources/res-18-010-a-2020-vision-of-linear-algebra-spring-2020/index.htm)[ | 18.06 Linear Algebra, Spring 2020](https://mitmath.github.io/1806/)
- [【线性代数 上】清华大学 马辉 徐帆](https://www.bilibili.com/video/BV11z4y1f7ym/) [| 【线性代数 下】清华大学 马辉 徐帆](https://www.bilibili.com/video/BV14k4y1y7uR/)
- [可汗线性代数](https://www.khanacademy.org/math/linear-algebra)
- [线性代数2022 李宏毅](https://www.bilibili.com/video/BV16q4y1e7Cm?p=2)
- [mit-18.06-linalg-notes,python](https://github.com/apachecn/mit-18.06-linalg-notes)
- [Introduction to Linear Algebra for Applied Machine Learning with Python](https://pabloinsente.github.io/intro-linear-algebra)
- [Linear_Algebra_With_Python](https://github.com/MacroAnalyst/Linear_Algebra_With_Python)
- [MIT-18.06-线性代数-完整笔记 markdown版](https://github.com/guokaide/linear-algebra)[ | 在线版](https://linalg.apachecn.org/#/)
- [线性代数 python](https://github.com/meichaofan/linear-algebra)
- [《线性代数及其应用》笔记](https://github.com/huangtinglin/Linear-Algebra-and-Its-Applications-notes)
- [线性代数 中英文对照表](http://www.gaoshufudao.com/LinearAlgebra_Word.aspx)
# notes
- system：a system has input and output(function, transformation,operator)
- linear system: persevering multiplication + persevering addition
- 微积分运算都属于线性系统，电路学、微分方程、信号与系统也是线性系统
- 向量和向量集合（符合某些约束条件），R<sup>n</sup>表示有n个元素的向量的集合
- 线性相关、线性无关、基、维数属于向量组的概念，描述空间的
- 秩是矩阵的概念
- 符合8特征的东西叫做向量
  + u+v=v+u
  + (u+v)+w=u+(v+w)
  + 0+u=u
  + u'+u=0
  + 1u=u
  + (ab)u=a(bu)
  + a(u+v)=au+av
  + (a+b)u=au+bu
- 线性系统=线性方程组，m个方程组，n个变量，m*n，线性方程组=矩阵*向量（行）=线性组合（列）
  + A(u+v)=Au+Av
  + A(cu)=c(Au)=(cA)u
  + (A+B)u=Au+Bu
  + A0=0
  + Ov=0
  + Iv=v
  + Au=Bu=>A=B
- 矩阵，向量也是矩阵[矩阵的运算及其运算规则](http://www2.edu-edu.com.cn/lesson_crs78/self/j_0022/soft/ch0605.html)
  + A+B=B+A
  + (A+B)+C=A+(B+C)
  + (st)A=s(tA)
  + s(A+B)=sA+sB
  + (s+t)A=sA+tA
  + (AB)C=A(BC)
  + A(B+C)=AB+AC
  + (B+C)A=BA+CA
  + (sA)B=s(AB)=A(sB)
  + (A<sup>T</sup>)<sup>T</sup>=A
  + (sA)<sup>T</sup>=sA<sup>T</sup>
  + (A+B)<sup>T</sup>=A<sup>T</sup>+B<sup>T</sup>
  + (AB)<sup>T</sup>=B<sup>T</sup>A<sup>T</sup>
  + (A<sup>-1</sup>)<sup>-1</sup>=A
  + (sA)<sup>-1</sup>=(1/s)A<sup>-1</sup>
  + (AB)<sup>-1</sup>=B<sup>-1</sup>A<sup>-1</sup>
  + (A<sup>T</sup>)<sup>-1</sup>=(A<sup>-1</sup>)<sup>T</sup>
  + |A<sup>-1</sup>|=1/|A|
  + AA<sup>\*</sup>=A<sup>\*</sup>A=|A|E
  + (A<sup>\*</sup>)<sup>-1</sup>=(A<sup>-1</sup>)<sup>\*</sup>
  + (kA)<sup>\*</sup>=k<sup>n-1</sup>A<sup>\*</sup>
  + (A<sup>\*</sup>)<sup>T</sup>=(A<sup>T</sup>)<sup>\*</sup>
  + |A<sup>*</sup>|=|A|<sup>n-1</sup>
  + (A<sup>\*</sup>)<sup>\*</sup>=|A|<sup>n-2</sup>A (n>=2)
  + A<sup>-1</sup>=(1/|A|)(A<sup>*</sup>)<sup>T</sup>
  + |AB|=|A||B|
  + |A<sup>T</sup>|=|A|
  + Rank A=Rank A<sup>T</sup>

- 方阵、单位阵 I、零阵 O、逆阵 A<sup>-1</sup>、转置阵A<sup>T</sup>、[三角阵 T](https://zh.wikipedia.org/wiki/%E4%B8%89%E8%A7%92%E7%9F%A9%E9%98%B5)、[对角阵 D](https://zh.wikipedia.org/wiki/%E5%B0%8D%E8%A7%92%E7%9F%A9%E9%99%A3)、[对称阵 S](https://math.fandom.com/zh/wiki/%E5%AF%B9%E7%A7%B0%E7%9F%A9%E9%98%B5?variant=zh)、[正交阵](https://zh.wikipedia.org/wiki/%E6%AD%A3%E4%BA%A4%E7%9F%A9%E9%98%B5)、[初等矩阵 E](https://baike.baidu.com/item/%E5%88%9D%E7%AD%89%E7%9F%A9%E9%98%B5/5538659)、- [伴随矩阵 A<sup>*</sup>](https://baike.baidu.com/item/%E4%BC%B4%E9%9A%8F%E7%9F%A9%E9%98%B5/10034983)、[简化的行阶梯形矩阵 R(reduced row echelon form=RREF)](https://ww2.mathworks.cn/help/matlab/ref/rref.html)
- 向量的数乘、向量的内积、向量的外积、矩阵的数乘、矩阵的乘法、矩阵的哈达玛积、矩阵的克罗内克积
  - 矩阵的乘法(matrix product、matmul product,一般矩阵乘积,表示为m x p矩阵A与p x n矩阵B乘积结果 m x n )
  - 哈达玛积（Hadamard product，对形状相同的矩阵进行运算，表示为 A ⊙ B ）
  - 克罗内克积（Kronecker product，是两个任意大小矩阵间的运算，表示为 A ⊗ B ）
  - 内积（inner product）、点乘（dot product）、数量积（scalar product）、外积（outer product）、叉乘（cross product）、矢量积（vector product）
  - exterior product=cross product，属于解析几何中领域，两个向量法向量，右手法则
  - outer product，属于线代或张量
- AX=0 有非零解说明A的列向量集合是线性相关关(dependence)
- 矮胖型矩阵肯定是dependence
- rank=矩阵线性无关最多列数；nullity=总列数-rank
![](rank.png)

![](solution.png)
- Column Correspondence Theorem,矩阵和RREF结构一致性
- The three elementary row operations are: 
  - (Row Swap) Exchange any two rows. 
  - (Scalar Multiplication) Multiply any row by a constant. 
  - (Row Sum) Add a multiple of one row to another row.
- Gauss-Jordan 消去法(interchange、scaling(non zero)、row addition)
- 左边是Row Echelon Form的定义，首先，非0行要在全0行上面，再者，leading entires(每行第一个非0值)是echelon form，从左到右阶梯排列
- 右边是reduced Row Echelon Form，加上一个条件，所有包含leading entires的列都是standard vectors
- 通过RREF求rank，求independence、求span
- basic or pivot variables、free variables、full rank、rank deficient、pivot(主元) column、pivot row、nullity
- 通过逆矩阵解方程组x=A<sup>-1</sup>b
- 求逆矩阵[A I] => [R B], B=A<sup>-1</sup>
- 如果A有可逆，R则是I，det(R)=1，det(A)!=0；如果A不可逆，R则有零行，det(R)=0，det(A)=0
![](invertible.png)
- subspace是一个向量集合
  + 零向量属于这个向量集合
  + u、v、u+v向量都属于这个向量集合(加法封闭性)
  + u，kv向量都属于这个向量集合(数乘封闭性)
- span一定是个subspace,subspace也是span
- column space是矩阵的列span，表示为Col A
- row space是矩阵的行span，表示为Row A = Col A<sup>T</sup>
- RREF Col A != Col R,但 Row A = Row R
- Ax=b 有解
  + b是A的列向量的线性组合
  + b在A的列向量的张成的空间里
  + b在列空间里
 - null space 是Ax=0的解向量集合
 - basis可以有很多对，pivot columns是 basis
 ![](pivot.png)
 - basis theorem
   + basis 是最小的[生成集](https://math.stackexchange.com/questions/3089880/minimal-generating-set)
   + basis 是子空间里最大的线性无关向量集
   + 任意两个basis在这个子空间里所包含的向量数是一样的，basis的向量个数=dim V(nonzero subspace), dim V(zero subspace)=0
- rank A = rank A<sup>T</sup>
- Dim(Null A) = number of free variables = Nullity A = n - Rank A
- det(A)!=0 <=> A可逆
![](det.png)
![](detp3.png)
- 坐标系变换：v笛卡尔下向量、[v]<sub>B</sub>其他坐标系下的向量、B其他坐标系矩阵
  - 笛卡尔到其他：[v]<sub>B</sub>=B<sup>-1</sup>v
  - 其他到笛卡尔：v=B[v]<sub>B</sub>
- Av=λv,λ是特征值，v是特征向量，零向量除外
  - A来确定一个好的坐标变换来简化function
  - 特征值可以对应无穷多个特征向量，这些特征向量不是subspace，因为无零向量
  - 特征向量对应一个特征值
  - eigenspace=eigenvecors+zerospace=Null(A-λI)
  - 判断特征值是不是矩阵的
  - 求矩阵的所有特征值：det(A-tI)=0(特征多项式)
  - 特征值小于n(R<sup>n</sup>)
# 三个流行的开源数值线性代数库是：
- 线性代数包，或 LAPACK。
- 基本线性代数子程序，或 BLAS（线性代数库的标准）。
- 自动调谐线性代数软件，或 ATLAS。



