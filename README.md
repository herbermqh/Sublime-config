# Snippets LaTeX
1. pr
```tex
\newproblem{$1}{
  $0
}{
	
}
```
2. ali
```tex
\begin{align*}
  $0
\end{align*}
```
3. resp
```tex
\begin{answer}
  $0
\end{answer}
```
4. iq
```tex
\begin{itemquestion}
  $0
\end{itemquestion}
```
5. mul2
```tex
\begin{multicols}{2}
  $0
\end{multicols}
```
6. mul3
```tex
\begin{multicols}{3}
  $0
\end{multicols}
```
# Key binding LaTeX

## Pares automáticos
Keys                                                 | Mappings
--------                                             | -----------------
<kbd>(</kbd>,<kbd>(</kbd>                            | `\left(\right)`
<kbd>[</kbd>,<kbd>[</kbd>                            | `\left[\right]`
<kbd>&#92;</kbd>,<kbd>{</kbd>,<kbd>{</kbd>           | `\left\{\right\}`
<kbd>&#92;</kbd>,<kbd>&#124;</kbd>                   | `\|\|`
<kbd>&#92;</kbd>,<kbd>&#124;</kbd>,<kbd>&#124;</kbd> | `\left\|\right\|`
<kbd>&#92;</kbd>,<kbd>&lt;</kbd>                     | `\langle \rangle`
<kbd>&#92;</kbd>,<kbd>&lt;</kbd>,<kbd>&lt;</kbd>     | `\left\langle \right\rangle`

## Autocompletado de comandos matemáticos

### Símbolos matemáticos

Keys                                                                     | Mappings
--------                                                                 | -----------------
<kbd>_</kbd>,<kbd>_</kbd>                                                | `_{}`
<kbd>^</kbd>,<kbd>^</kbd>                                                | `^{}`
<kbd>\`</kbd>,<kbd>_</kbd>                                               | `\bar{}`
<kbd>_</kbd> (with text highlighted)                                     | `\bar{SELECTION}`
<kbd>_</kbd>,<kbd>_</kbd> (with text highlighted)                        | `\overline{SELECTION}`
<kbd>\`</kbd>,<kbd>^</kbd>                                               | `\hat{}`
<kbd>^</kbd> (with text highlighted)                                     | `\hat{SELECTION}`
<kbd>^</kbd>, <kbd>^</kbd> (with text highlighted)                       | `\widehat{SELECTION}`
<kbd>.</kbd>,<kbd>.</kbd>,<kbd>.</kbd>                                   | `\ldots`
<kbd>\`</kbd>,<kbd>,</kbd>                                               | `\nonumber`
<kbd>\`</kbd>,<kbd>/</kbd>                                               | `\frac{}{}`
<kbd>/</kbd> (with text highlighted)                                     | `\frac{SELECTION}{}`
<kbd>\`</kbd>,<kbd>0</kbd>                                               | `\varnothing`
<kbd>\`</kbd>,<kbd>2</kbd>                                               | `\sqrt{}`
<kbd>\`</kbd>,<kbd>6</kbd>                                               | `\partial`
<kbd>\`</kbd>,<kbd>8</kbd>                                               | `\infity`

Keys                                                                     | Mappings
--------                                                                 | -----------------
<kbd>&lt;</kbd>,<kbd>-</kbd>,<kbd>tab</kbd>                              | `\leftarrow`
<kbd>&lt;</kbd>,<kbd>-</kbd>,<kbd>-</kbd>,<kbd>tab</kbd>                 | `\longleftarrow`
<kbd>&lt;</kbd>,<kbd>=</kbd>,<kbd>tab</kbd>                              | `\Leftarrow`
<kbd>&lt;</kbd>,<kbd>=</kbd>,<kbd>=</kbd>,<kbd>tab</kbd>                 | `\Longleftarrow`
<kbd>-</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>                              | `\rightarrow`
<kbd>-</kbd>,<kbd>-</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>                 | `\longrightarrow`
<kbd>=</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>                              | `\Rightarrow`
<kbd>=</kbd>,<kbd>=</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>                 | `\Longrightarrow`
<kbd>&lt;</kbd>,<kbd>-</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>              | `\leftrightarrow`
<kbd>&lt;</kbd>,<kbd>-</kbd>,<kbd>-</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd> | `\longleftrightarrow`
<kbd>&lt;</kbd>,<kbd>=</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd>              | `\Leftrightarrow`
<kbd>&lt;</kbd>,<kbd>=</kbd>,<kbd>=</kbd>,<kbd>&gt;</kbd>,<kbd>tab</kbd> | `\Longleftrightarrow`

### Alfabeto griego

Keys                       | Mappings          | Keys                       | Mappings          | Keys                       | Mappings          |
--------                   | ----------------- | --------                   | ----------------- | --------                   | ----------------- |
<kbd>\`</kbd>,<kbd>a</kbd> | `\alpha`          | <kbd>\`</kbd>,<kbd>i</kbd> | `\iota`           | <kbd>\`</kbd>,<kbd>s</kbd> | `\sigma`          |
<kbd>\`</kbd>,<kbd>b</kbd> | `\beta`           | <kbd>\`</kbd>,<kbd>k</kbd> | `\kappa`          | <kbd>\`</kbd>,<kbd>t</kbd> | `\tau`            |
<kbd>\`</kbd>,<kbd>g</kbd> | `\gamma`          | <kbd>\`</kbd>,<kbd>l</kbd> | `\lambda`         | <kbd>\`</kbd>,<kbd>u</kbd> | `\upsilon`        |
<kbd>\`</kbd>,<kbd>d</kbd> | `\delta`          | <kbd>\`</kbd>,<kbd>m</kbd> | `\mu`             | <kbd>\`</kbd>,<kbd>f</kbd> | `\varphi`         |
<kbd>\`</kbd>,<kbd>e</kbd> | `\varepsilon`     | <kbd>\`</kbd>,<kbd>n</kbd> | `\nu`             | <kbd>\`</kbd>,<kbd>c</kbd> | `\chi`            |
<kbd>\`</kbd>,<kbd>z</kbd> | `\zeta`           | <kbd>\`</kbd>,<kbd>x</kbd> | `\xi`             | <kbd>\`</kbd>,<kbd>y</kbd> | `\psi`            |
<kbd>\`</kbd>,<kbd>h</kbd> | `\eta`            | <kbd>\`</kbd>,<kbd>p</kbd> | `\pi`             | <kbd>\`</kbd>,<kbd>w</kbd> | `\omega`          |
<kbd>\`</kbd>,<kbd>q</kbd> | `\theta`          | <kbd>\`</kbd>,<kbd>r</kbd> | `\rho`            |                            |                   |

Keys                       | Mappings
--------                   | -----------------
<kbd>\`</kbd>,<kbd>G</kbd> | `\Gamma`
<kbd>\`</kbd>,<kbd>D</kbd> | `\Delta`
<kbd>\`</kbd>,<kbd>Q</kbd> | `\Theta`
<kbd>\`</kbd>,<kbd>L</kbd> | `\Lambda`
<kbd>\`</kbd>,<kbd>X</kbd> | `\Xi`
<kbd>\`</kbd>,<kbd>P</kbd> | `\Pi`
<kbd>\`</kbd>,<kbd>S</kbd> | `\Sigma`
<kbd>\`</kbd>,<kbd>U</kbd> | `\Upsilon`
<kbd>\`</kbd>,<kbd>F</kbd> | `\Phi`
<kbd>\`</kbd>,<kbd>Y</kbd> | `\Psi`
<kbd>\`</kbd>,<kbd>W</kbd> | `\Omega`
