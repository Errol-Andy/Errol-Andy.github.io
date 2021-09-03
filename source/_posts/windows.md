---
title: windows
mathjax: true
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

## Equations

1、

```latex
\begin{equation}
   E = mc^2
\end{equation}
```


$$
\begin{equation}
   E = mc^2
\end{equation}
$$
2、

```latex
% equation* 不会编号
\begin{equation*}
   e^{\pi i} + 1 = 0
\end{equation*}
```


$$
\begin{equation*}
   e^{\pi i} + 1 = 0
\end{equation*}
$$
3、

```latex
% 单句一个编号
\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:2}
\end{equation}
```


$$
\begin{equation}
  \int_0^\infty \frac{x^3}{e^x-1}\,dx = \frac{\pi^4}{15}
  \label{eq:2}
\end{equation}
$$
4、

```latex
% 多句一个编号
\begin{equation} \label{eq:3}
\begin{aligned}
a &= b + c \\
  &= d + e + f + g \\
  &= h + i
\end{aligned}
\end{equation}
```



$$
\begin{equation} \label{eq:3}
\begin{aligned}
a &= b + c \\
  &= d + e + f + g \\
  &= h + i
\end{aligned}
\end{equation}
$$
5、

```latex
% 多句多个编号，\nonumber不加编号
% align 本身就是一个完整的方程环境，不需要用 equation 环境包装它
\begin{align}
a &= b + c \label{eq4} \\
x &= yz  \nonumber \\
l &= m - n \label{eq5} 
\end{align}
```


$$
\begin{align}
a &= b + c \label{eq:4} \\
x &= yz  \nonumber \\
l &= m - n \label{eq:5} 
\end{align}
$$
6、

```latex
% tag 自定义编号
x+1\over\sqrt{1-x^2} \tag{i}\label{eq:i}
```


$$
x+1\over\sqrt{1-x^2} \tag{i}\label{eq:i}
$$

7、引用公式编号

引用自动编号: $\eqref{eq:2}$, $\ref{eq:2}$

引用tag: $\eqref{eq:a}$, $\ref{eq:a}$

引用 $\sum{x}$, 带空格 $ \sum{x} $ 不显示

## Other

