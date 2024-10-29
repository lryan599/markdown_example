# markdown语法和常用符号

### 代码

    int main{
        int x = 1;
        int y = x;
        return x + y;
    }
  
  ```
    int main{
      int x = 1;
      int y = x;
      return x + y;
  }
  ```

### 文本

# 这是一个一级标题

## 这是一个二级标题

### 这是一个三级标题

#### 这是一个四级标题

##### 这是一个五级标题

这是一个`main`函数  

这是一个&nbsp;空格  
这是两个&ensp;空格  
这是四个&emsp;空格  

这是<u>下划线</u>  

<font color = 'red'>这是一段红色文字 </font>  

这是<del>删除线</del>

1. 这是一个列表
   1. 这是一个嵌套列表
2. 这是一个列表

- 这是一个无序列表  
- 这是另一个无序列表
  - 嵌套的无序列表  

这是一个分割线  
___

这是一个链接[百度](https:\\www.baidu.com)  
<https:\\www.baidu.com>  

这是一张图片  
![秋山澪](http://pic.baike.soso.com/p/20120927/20120927222852-1439391804.jpg)

使用img标签居中插入图片  
<div style="text-align: center;">
<img src="http://pic.baike.soso.com/p/20120927/20120927222852-1439391804.jpg" alt="秋山澪" width=50% height=50%/>
</div>

**粗体** <b>粗体</b>  
*斜体* <i>斜体</i>  
***斜粗体***  <b><i>斜粗体</i></b>

简易表格：
| 表头   | 表头   |
| ------ | ------ |
| 单元格 | 单元格 |
| 单元格 | 单元格 |

HTML渲染的带边框的表格：
<table border="1">
    <tr>
        <td>row 1, cell 1</td>
        <td>row 1, cell 2</td>
    </tr>
    <tr>
        <td>row 2, cell 1</td>
        <td>row 2, cell 2</td>
    </tr>
</table>

HTML渲染的跨列表格：
<table border="1">
<tr>
  <th>Name</th>
  <th colspan="2">Telephone</th>
</tr>
<tr>
  <td>Bill Gates</td>
  <td>555 77 854</td>
  <td>555 77 855</td>
</tr>
</table>

HTML渲染的跨行表格：
<table border="1">
<tr>
  <th>First Name:</th>
  <td>Bill Gates</td>
</tr>
<tr>
  <th rowspan="2">Telephone:</th>
  <td>555 77 854</td>
</tr>
<tr>
  <td>555 77 855</td>
</tr>
</table>

> 注释块  
> 这里是一个注释块

### 公式测试：
#### 1.希腊符号表：
| latex    | 符号       | latex    | 符号       |
| -------- | ---------- | -------- | ---------- |
| \alpha   | $\alpha$   | \Alpha   | $\Alpha$   |
| \beta    | $\beta$    | \Beta    | $\Beta$    |
| \gamma   | $\gamma$   | \Gamma   | $\Gamma$   |
| \theta   | $\theta$   | \Theta   | $\Theta$   |
| \delta   | $\delta$   | \Delta   | $\Delta$   |
| \mu      | $\mu$      | \Mu      | $\Mu$      |
| \nu      | $\nu$      | \Nu      | $\Nu$      |
| \epsilon | $\epsilon$ | \Epsilon | $\Epsilon$ |
| \omega   | $\omega$   | \Omega   | $\Omega$   |
| \eta     | $\eta$     | \Eta     | $\Eta$     |
| \lambda  | $\lambda$  | \Lambda  | $\Lambda$  |
| \pi      | $\pi$      | \Pi      | $\Pi$      |
| \rho     | $\rho$     | \Rho     | $\Rho$     |
| \sigma   | $\sigma$   | \Sigma   | $\Sigma$   |
| \phi     | $\phi$     | \Phi     | $\Phi$     |
| \xi      | $\xi$      | \Xi      | $\Xi$      |
| \alef    | $\alef$    | -        | -          |

下面是花写的变量字母：
| latex       | 符号          |
| ----------- | ------------- |
| \varepsilon | $\varepsilon$ |
| \varGamma   | $\varGamma$   |
| \varpi      | $\varpi$      |
| \vartheta   | $\vartheta$   |
| \mathbb{Aa,Rr,Kk} | $\mathbb{Aa,Rr,Kk}$ |
| \Bbb{Aa,Rr,Kk} | $\Bbb{Aa,Rr,Kk}$ |

#### 2.数学符号表：
| latex                          | 符号                             |
| ------------------------------ | -------------------------------- |
| \pm                            | $\pm$                            |
| \times                         | $\times$                         |
| \circ                          | $\circ$                          |
| \cdot                          | $\cdot$                          |
| \cap                           | $\cap$                           |
| \cup                           | $\cup$                           |
| \cdots                         | $\cdots$                         |
| \subset                        | $\subset$                        |
| \subseteq                      | $\subseteq$                      |
| \neq                           | $\neq$                           |
| \div                           | $\div$                           |
| \geq                           | $\geq$                           |
| \leq                           | $\leq$                           |
| \mp                            | $\mp$                            |
| \in                            | $\in$                            |
| \emptyset                      | $\emptyset$                      |
| \land                          | $\land$                          |
| \lor                           | $\lor$                           |
| \lnot                          | $\lnot$                          |
| \forall                        | $\forall$                        |
| \exists                        | $\exists$                        |
| \equiv                         | $\equiv$                         |
| \infty                         | $\infty$                         |
| \partial                       | $\partial$                       |
| \approx                        | $\approx$                        |
| \Rightarrow                    | $\Rightarrow$                    |
| \rightarrow                    | $\rightarrow$                    |
| \preceq                        | $\preceq$                        |
| \succeq                        | $\succeq$                        |
| \prec                          | $\prec$                          |
| \succ                          | $\succ$                          |
| \to                            | $\to$                            |
| \vec a                         | $\vec a$                         |
| \hat a                         | $\hat a$                         |
| \bar a                         | $\bar a$                         |
| \tilde a                       | $\tilde a$                       |
| \sqrt[2]{3}                    | $\sqrt[2]{3}$                    |
| \dfrac{\partial f}{\partial x} | $\dfrac{\partial f}{\partial x}$ |
| \sin 30^\circ                  | $\sin 30^\circ$                  |
| \ln 2                          | $\ln 2$                          |
| \log_2 8                       | $\log_2 8$                       |
| x^{\prime}                     | $x^{\prime}$                     |
| \bowtie                        | $\bowtie$                        |
| -                              | ⟕                                |
| -                              | ⟖                                |
| -                              | ⟗                               |
| \nabla                         | $\nabla$                         |
| \mathcal{LU}                   | $\mathcal{LU},花写$              |
#### 3.数学结构
| latex                                                         | 符号                                                          |
| ------------------------------------------------------------- | ------------------------------------------------------------- |
| \sum_1^n                                                      | $\sum_1^n$                                                    |
| \prod_1^n                                                     | $\prod_1^n$                                                   |
| \int_1^n                                                      | $\int_1^n$                                                    |
| \iint_1^n                                                     | $\iint_1^n$                                                   |
| \iiint_1^n                                                    | $\iiint_1^n$                                                  |
| \lceil x \rceil                                               | $\lceil x \rceil$                                             |
| \lfloor x \rfloor                                             | $\lfloor x \rfloor$                                           |
| \underset{x \to \infty}{\lim}{x}                              | $\underset{x \to \infty}{\lim}{x}$                            |
| \dfrac{a}{b}                                                  | $\dfrac{a}{b}$                                                |
| \begin{pmatrix}1 & 2 & 3\\\4 & 5 & 6\\\7 & 8 & 9\end{pmatrix} | $\begin{pmatrix}1 & 2 & 3\\4 & 5 & 6\\7 & 8 & 9\end{pmatrix}$ |
| \begin{bmatrix}1 & 2 & 3\\\4 & 5 & 6\\\7 & 8 & 9\end{bmatrix} | $\begin{bmatrix}1 & 2 & 3\\4 & 5 & 6\\7 & 8 & 9\end{bmatrix}$ |
| \begin{Bmatrix}1 & 2 & 3\\\4 & 5 & 6\\\7 & 8 & 9\end{Bmatrix} | $\begin{Bmatrix}1 & 2 & 3\\4 & 5 & 6\\7 & 8 & 9\end{Bmatrix}$ |
| \begin{vmatrix}1 & 2 & 3\\\4 & 5 & 6\\\7 & 8 & 9\end{vmatrix} | $\begin{vmatrix}1 & 2 & 3\\4 & 5 & 6\\7 & 8 & 9\end{vmatrix}$ |
| \begin{Vmatrix}1 & 2 & 3\\\4 & 5 & 6\\\7 & 8 & 9\end{Vmatrix} | $\begin{Vmatrix}1 & 2 & 3\\4 & 5 & 6\\7 & 8 & 9\end{Vmatrix}$ |

$$\begin{Vmatrix}
1 & 2 & 3\\
4 & 5 & 6\\
7 & 8 & 9
\end{Vmatrix}$$

$$\begin{aligned}
\text{原式} 
& = 1+2+3 \\
& = 3 + 3 \\
& = 6
\end{aligned}$$

$$f(n) =
\begin{cases}
n/2,  & \text{if $n$ is even} \\
3n+1, & \text{if $n$ is odd} \\
\end{cases}
\tag{2}$$
