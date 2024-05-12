微分

單變數函數微分

$\begin{align}
y=f(x)\\
\end{align}$

$\begin{align}
主要探討當x有些變化時,y會有多少變化
\end{align}$

$\begin{align}
\frac{d}{dx}f(x)=\lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}={f}'(x),而{f}'(x)即為導函數
\end{align}$
  
$\begin{align}
主要探討當x有些變化時,y會有多少變化
\end{align}$

$\begin{align}
\triangle x \to 0,表示x的變化趨近0但不等於0    
\end{align}$

例：

$\begin{align}
 y=f(x)=x^{2}
\end{align}$

$\begin{align}
\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{(x+\triangle x)^{2}-x^{2}}{\triangle x}
=\lim_{\triangle x \to 0}\frac{(x^{2}+2x\triangle x+\triangle x^{2})-x^{2}}{\triangle x}=
\lim_{\triangle x \to 0}\frac{x^{2}+2x\triangle x+\triangle x^{2}-x^{2}}{\triangle x}
\end{align}$

$\begin{align}
=\lim_{\triangle x \to 0}\frac{2x\triangle x+\triangle x^{2}}{\triangle x}=
\lim_{\triangle x \to 0}\frac{\triangle x(2x+\triangle x)}{\triangle x}=
\lim_{\triangle x \to 0}(2x+\triangle x)=2x
\end{align}$

$\begin{align}
\triangle x \to 0\Rightarrow 2x+\triangle x \to 2x+0\Rightarrow 2x+\triangle x \to 2x  
\end{align}$

導數

$\begin{align}
什麼是導數？顧名思義,就是把{f}'(x)視為函數（即為導函數）,然後輸入數字a,得到{f}'(a),其重要意義為f(x)在x=a上的切線斜率,
\end{align}$

$\begin{align}
則通過(a,f(a))的切線方程式為:y-f(a)={f}'(a)(x-a)
\end{align}$

例：

$\begin{align}
 y=f(x)=x^{2},找通過(2,4)的切線方程式
\end{align}$

$\begin{align}
step1:找x^{2}在x=2的切線斜率(算{f}'(2))
\end{align}$

$\begin{align}
\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{(x+\triangle x)^{2}-x^{2}}{\triangle x}=2x={f}'(x)
\end{align}$

$\begin{align}
{f}'(2)=4
\end{align}$

$\begin{align}
step2:可直接求出通過(2,4)的切線方程式為：y-4=4(x-2)
\end{align}$

$\begin{align}
常見重要微分公式及推導：
\end{align}$

$\begin{align}
1.
\end{align}$
$\begin{align}
y=f(x)=x^{n}\Rightarrow {f}'(x)=nx^{n-1} 
\end{align}$

証明:
$\begin{align}
{f}'(x)=\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{(x+\triangle x)^{n}-x^{n}}{\triangle x}=\lim_{\triangle x \to 0}\frac{x^{n}+\frac{n!}{(n-1)!1!}x^{n-1}\triangle x+\frac{n!}{(n-2)!2!}x^{n-2}\triangle x^{2}+\frac{n!}{(n-3)!3!}x^{n-3}\triangle x^{3}+...+\triangle x^{n}-x^{n} }{\triangle x}
\end{align}$

$\begin{align}
=\lim_{\triangle x \to 0}\frac{\triangle x (\frac{n!}{(n-1)!1!}x^{n-1}+\frac{n!}{(n-2)!2!}x^{n-2}\triangle x^{}+\frac{n!}{(n-3)!3!}x^{n-3}\triangle x^{2}+...+\triangle x^{n-1} )}{\triangle x}=\lim_{\triangle x \to 0}{(\frac{n!}{(n-1)!1!}x^{n-1}+\frac{n!}{(n-2)!2!}x^{n-2}\triangle x^{}+\frac{n!}{(n-3)!3!}x^{n-3}\triangle x^{2}+...+\triangle x^{n-1} )}=nx^{n-1}
\end{align}$

$\begin{align}
2.常數函數微分為0
\end{align}$

$\begin{align}
y=f(x)=k\Rightarrow {f}'(x)=0 
\end{align}$

証明:
$\begin{align}
{f}'(x)=\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{k-k}{\triangle x}=\lim_{\triangle x \to 0}\frac{0}{\triangle x}=0
\end{align}$

$\begin{align}
3.三角函數的微分
\end{align}$

$\begin{align}
(1)\quad y=f(x)=sin(x)\Rightarrow {f}'(x)=cos(x) 
\end{align}$

証明:
$\begin{align}
{f}'(x)=\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{sin(x+\triangle x)-sin(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{sin(x)cos(\triangle x)+cos(x)sin(\triangle x)-sin(x)}{\triangle x}
\end{align}$

$\begin{align}
=\lim_{\triangle x \to 0}(\frac{sin(x)cos(\triangle x)-sin(x)}{\triangle x}+\frac{cos(x)sin(\triangle x)}{\triangle x})=\lim_{\triangle x \to 0}(\frac{sin(x)(cos(\triangle x)-1)}{\triangle x}+\frac{cos(x)sin(\triangle x)}{\triangle x})=sin(x)\lim_{\triangle x \to 0}\frac{(cos(\triangle x)-1)}{\triangle x}+cos(x)\lim_{\triangle x \to 0}\frac{sin(\triangle x)}{\triangle x}
\end{align}$

$\begin{align}
=cos(x)
\end{align}$

$\begin{align}
備註:
\lim_{\triangle x \to 0}\frac{(cos(\triangle x)-1)}{\triangle x}=0,\lim_{\triangle x \to 0}\frac{sin(\triangle x)}{\triangle x}=1
\end{align}$

$\begin{align}
\lim_{\triangle x \to 0}\frac{(cos(\triangle x)-1)}{\triangle x}=\lim_{\triangle x \to 0}\frac{(cos(\triangle x)-1)(cos(\triangle x)+1)}{\triangle x(cos(\triangle x)+1)}=\lim_{\triangle x \to 0}\frac{((cos(\triangle x))^{2}-1)}{\triangle x(cos(\triangle x)+1)}=\lim_{\triangle x \to 0}\frac{-sin(x)}{\triangle x}\lim_{\triangle x \to 0}\frac{sin(x)}{cos(\triangle x)+1}=-1\times \frac{0}{1+1}=0
\end{align}$

$\begin{align}
(2)\quad y=f(x)=cos(x)\Rightarrow {f}'(x)=-sin(x) 
\end{align}$

証明:
$\begin{align}
{f}'(x)=\frac{dy}{dx}=\frac{d}{dx}f(x)= \lim_{\triangle x \to 0}\frac{\triangle y}{\triangle x}=
\lim_{\triangle x \to 0}\frac{f(x+\triangle x)-f(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{cos(x+\triangle x)-cos(x)}{\triangle x}=\lim_{\triangle x \to 0}\frac{cos(x)cos(\triangle x)-sin(x)sin(\triangle x)-cos(x)}{\triangle x}
\end{align}$

$\begin{align}
=\lim_{\triangle x \to 0}(\frac{cos(x)cos(\triangle x)-cos(x)}{\triangle x}-\frac{sin(x)sin(\triangle x)}{\triangle x})=\lim_{\triangle x \to 0}(\frac{cos(x)(cos(\triangle x)-1)}{\triangle x}-\frac{sin(x)sin(\triangle x)}{\triangle x})=cos(x)\lim_{\triangle x \to 0}\frac{(cos(\triangle x)-1)}{\triangle x}-sin(x)\lim_{\triangle x \to 0}\frac{sin(\triangle x)}{\triangle x}=-sin(x)
\end{align}$

$\begin{align}
(3)\quad y=f(x)=e^x\Rightarrow {f}'(x)=e^x
\end{align}$

$\begin{align}
(4)\quad y=f(x)=lnx\Rightarrow {f}'(x)=\frac{1}{x}
\end{align}$

$\begin{align}
(5)\quad y=f(x)=a^x\Rightarrow {f}'(x)=a^xlna
\end{align}$

$\begin{align}
(6)\quad y=f(x)=a_{n} x^n+a_{n-1} x^{n-1}+a_{n-2} x^{n-2}+a_{n-3} x^{n-3}+a_{n-4} x^{n-4}...+a_{1}x+a_{0} 
\end{align}$

$\begin{align}
\Rightarrow {f}'(x)=a_{n}n x^{n-1}+a_{n-1}({n-1}) x^{n-2}+a_{n-2}({n-2}) x^{n-3}+a_{n-3}({n-3}) x^{n-4}+a_{n-4}({n-4})x^{n-5}...+a_{1} 
\end{align}$

微分的性質

$\begin{align}
1.\quad\frac{d}{dx}(f(x)+g(x))=\frac{d}{dx}f(x)+\frac{d}{dx}g(x)
\end{align}$

$\begin{align}
2.\quad\frac{d}{dx}(kf(x))=k\frac{d}{dx}f(x)
\end{align}$

$\begin{align}
3.\quad\frac{d}{dx}(f(x)\times g(x))=(\frac{d}{dx}f(x))g(x)+f(x)(\frac{d}{dx}g(x))
\end{align}$

$\begin{align}
4.\quad\frac{d}{dx}(\frac{g(x)}{f(x)} )=\frac{(\frac{d}{dx}g(x))f(x)-g(x)(\frac{d}{dx}f(x)) }{(f(x))^{2}}  
\end{align}$

$\begin{align}
5.\quad\frac{d}{dx}(af(x)+bg(x))=a(\frac{d}{dx}f(x))+b(\frac{d}{dx}g(x))
\end{align}$

例：

$\begin{align}
f(x)=3x^{2}+7x
\end{align}$

$\begin{align}
g(x)=5x
\end{align}$

$\begin{align}
1.\quad\frac{d}{dx}(3x^{2}+7x+5x)=\frac{d}{dx}(3x^{2}+7x)+\frac{d}{dx}(5x)=6x+7+5
\end{align}$

$\begin{align}
\quad\quad\frac{d}{dx}(3x^{2}+7x+5x)=6x+7+5
\end{align}$

$\begin{align}
2.\quad\frac{d}{dx}(10(3x^{2}+7x))=10(\frac{d}{dx}(3x^{2}+7x))=10(6x+7)=60x+70
\end{align}$

$\begin{align}
\quad\quad\frac{d}{dx}(30x^{2}+70x)=60x+70
\end{align}$

$\begin{align}
3.\quad\frac{d}{dx}((3x^{2}+7x)\times (5x))=(\frac{d}{dx}(3x^{2}+7x))(5x)+(3x^{2}+7x)(\frac{d}{dx}(5x))=(6x+7)5x+(3x^{2}+7x)5=45x^{2}+70x
\end{align}$

$\begin{align}
\quad\quad\frac{d}{dx}((3x^{2}+7x)\times (5x))=(\frac{d}{dx}(15x^3+35x^2))=45x^{2}+70x
\end{align}$

$\begin{align}
4.\quad\frac{d}{dx}(\frac{5x}{3x^{2}+7x} )=\frac{(\frac{d}{dx}(5x))(3x^{2}+7x)-(5x)(\frac{d}{dx}(3x^{2}+7x)) }{(3x^{2}+7x)^{2}}=\frac{(5)(3x^{2}+7x)-(5x)(6x+7) }{(3x^{2}+7x)^{2}}  
\end{align}$

$\begin{align}
5.\quad\frac{d}{dx}(2(3x^{2}+7x)+3(5x))=2(\frac{d}{dx}(3x^{2}+7x))+3(\frac{d}{dx}(5x))=2(6x+7)+3(5)=12x+29
\end{align}$

$\begin{align}
\quad\quad\frac{d}{dx}(2(3x^{2}+7x)+3(5x))=\frac{d}{dx}(6x^{2}+14x+15x)=12x+14+15=12x+29
\end{align}$

$\begin{align}
連鎖率
\end{align}$

$\begin{align}
y=f(x),z=g(y),z=g(f(x))=(g。f)(x)\\
(g。f)(x)^{'}=\frac{dg}{dx}=\frac{dg}{df}\frac{df}{dx}
\end{align}$

$\begin{align}
例1:y=f(x)=x^{2},z=g(y)=e^{y},z=g(f(x))=e^{x^{2}}=(g。f)(x)
\end{align}$
$\begin{align}
(g。f)(x)^{'}=\frac{dg}{dx}=\frac{dg}{df}\frac{df}{dx}=e^{x^{2}}\times 2x
\end{align}$

$\begin{align}
例2:y=f(x)=x^{2},z=g(y)=sin(y),z=g(f(x))=sin(x^{2})=(g。f)(x)
\end{align}$
$\begin{align}
(g。f)(x)^{'}=\frac{dg}{dx}=\frac{dg}{df}\frac{df}{dx}=cos(x^{2})\times 2x
\end{align}$


$\begin{align}
函數的的增遞減
\end{align}$

$\begin{align}
什麼是遞增？
\end{align}$

$\begin{align}
函數f(x)在一區間上遞增\Leftrightarrow 在區間中x_{1}< x_{2},則f(x_{1})<f(x_{2})\\
函數f(x)在一區間上遞減\Leftrightarrow 在區間中x_{1}< x_{2},則f(x_{1})>f(x_{2})
\end{align}$

$\begin{align}
如何判斷遞增＼遞減？
\end{align}$

$\begin{align}
可利用一次微分
\end{align}$

$\begin{align}
設函數f (x)在區間[a，b]上連續，且在區間(a，b)上可微分 
\end{align}$

$\begin{align}
(1)若{f}'(x)＞0在區間(a，b)上都成立，則f (x)在區間[a，b]上為嚴格遞增函數 
\\(2)若{f}'(x)＜0在區間(a，b)上都成立，則f (x)在區間[a，b]上為嚴格遞減函數
\end{align}$

$\begin{align}
函數圖形的凹向 
\end{align}$
$\begin{align}
\\1.凹口向上：若圖形上任相異兩點所連成的線段恆在圖形的上方 
\\凹口向下：若圖形上任相異兩點所連成的線段恆在圖形的下方 
\end{align}$

$\begin{align}
2.判斷方式：(導函數判斷)
\end{align}$
$\begin{align}
\\(1)切線的斜率由左往右逐漸增大，也就是說，圖形上愈往右邊的點其導函數{f}'(x)的值愈大， 即{f}'(x)為嚴格遞增函數 
\\(2)切線的斜率由左往右逐漸減小，也就是說，圖形上愈往右邊的點其導函數{f}'(x)的值愈小， 即{f}'(x)為嚴格遞減函數 
\end{align}$
$\begin{align}
註：函數f (x)圖形的凹向相當於討論導函數{f}'(x)的遞增與遞減，由二階導函數{f}''(x)函數值的正負來決定 
\end{align}$

$\begin{align}
3.函數圖形凹向的判定：(由二階導函數{f}''(x)函數值判斷) 設函數f (x)在開區間I內每一數x的第二階導數{f}''(x)都存在 
\end{align}$

$\begin{align}
(1)若{f}''(x)＞0在區間I上都成立，則f (x)在區間I的圖形是凹口向上\\
(2)若{f}''(x)＜0在區間I上都成立，則f (x)在區間I的圖形是凹口向下 
\end{align}$

$\begin{align}
函數圖形的臨界點(critical\quad point)
\end{align}$

$\begin{align}
設 c 在f 的定義域內. 則 c 為 f 的臨界點(critical\quad point) \Leftrightarrow {f}'(c) = 0 或 {f}'(c) 不存在 (未定義).
\end{align}$

$\begin{align}
函數圖形的反曲點
\end{align}$

$\begin{align}
1.反曲點的定義： 
在a的附近(某個包含a的開區間)，當{f}(x)的圖形在x＜a與x＞a的凹向相反時，稱點(a，f (a))為函數{f}(x)圖形 的反曲點。
\end{align}$

$\begin{align}
2.反曲點的性質(求法): 若(a，f (a))為多項式函數f (x )圖形的一個反曲點點，則{f}''(a)＝0 
\end{align}$

$\begin{align}
(1){f}(x)的二階導函數仍是多項式函數(連續函數)，反曲點{f}''(x)附近的函數值由正轉負或由負轉正 
\end{align}$

$\begin{align}
(2)若(a，f (a))為反曲點，且{f}''(x)為連續函數，則在反曲點附近的{f}''(x)函數值會由正轉負或由負轉正， 因而{f}''(a) = 0  
\end{align}$

$\begin{align}
例：y=f(x)=x^{2}\\
\Rightarrow{f}'(x)=2x\\
\Rightarrow{f}''(x)=2
\end{align}$

$\begin{align}
找臨界點(critical\quad point):
令{f}'(x)=0\Rightarrow{f}'(x)=2x=0\Rightarrow x=0\\
\end{align}$
$\begin{align}
critical\quad point為(0,0)
\end{align}$
$\begin{align}
找反曲點:
令{f}''(x)=0\Rightarrow 但2\ne 0\Rightarrow沒有反曲點\Rightarrow且凹口一定向上
\end{align}$
$\begin{align}
x>0\Rightarrow {f}'(x)>0\Rightarrow 遞增\\
x<0\Rightarrow {f}'(x)<0\Rightarrow 遞減
\end{align}$

多變數函數偏微分

先談論兩變數情況:
$\begin{align}
z=f(x,y)\\
\end{align}$

$\begin{align}
主要探討當y不變,x有些微變化時,z會有多少變化\\
當x不變,y有些微變化時,z會有多少變化
\end{align}$

$\begin{align}
\frac{\partial z}{\partial x}f(x,y)=\lim_{\triangle x \to 0}\frac{\triangle z}{\triangle x}=\lim_{\triangle x \to 0}\frac{f(x+\triangle x,y)-f(x,y)}{\triangle x}=f_{x}'(x,y),而f_{x}'(x,y)即為x偏導函數
\end{align}$

$\begin{align}
\frac{\partial z}{\partial y}f(x,y)=\lim_{\triangle y \to 0}\frac{\triangle z}{\triangle y}=\lim_{\triangle y \to 0}\frac{f(x,y+\triangle y)-f(x,y)}{\triangle y}=f_{y}'(x,y),而f_{y}'(x,y)即為y偏導函數
\end{align}$

$\begin{align}
事實上,\frac{\partial z}{\partial x}f(x,y)可把當y常數,直接對x偏微分\\\frac{\partial z}{\partial y}f(x,y)可把當x常數,直接對y偏微分
\end{align}$

$\begin{align}
例:
{f}(x,y)=4x^7y+5x+7y\quad
,\frac{\partial }{\partial x}f(x,y)=28x^{6}y+5\quad(把y當常數)\\
,\frac{\partial }{\partial y}f(x,y)=4x^{7}+7\quad(把x當常數)
\end{align}$

$\begin{align}
什麼是偏導數？顧名思義,就是把f_{x}'(x,y)(即為x偏導函數)視為函數,然後把x=a,y=b帶入,得到f_{x}'(a,b)即為x偏導數,\\同理,就是把f_{y}'(x,y)(即為y偏導函數)視為函數,然後把x=a,y=b帶入,得到f_{y}'(a,b)即為y偏導數
\end{align}$

$\begin{align}
例:由上個例子延伸:
{f}(x,y)=4x^7y+5x+7y\quad
\\\frac{\partial }{\partial x}f(x,y)=28x^{6}y+5\quad(把y當常數)\\\frac{\partial }{\partial y}f(x,y)=4x^{7}+7\quad(把x當常數),\\\frac{\partial }{\partial x}f(1,2)=28\times1^{6}\times2+5=61為x偏導數\\
\frac{\partial }{\partial y}f(1,2)=4\times1^{7}+7=11為y偏導數
\end{align}$

$\begin{align}
備註:
1.可藉由單變數一次微分求切線方程式\quad\quad 2.可藉由兩變數一次偏微分求切平面方程式
\end{align}$

$\begin{align}
切平面方程式
z=f(x,y)\quad z_{0}=f(x_{0},y_{0})\quad 過(x_{0},y_{0})的切平面方程式為:\\ 
\end{align}$

$\begin{align}
z-z_{0}=\frac{\partial f(x_{0},y_{0}) }{\partial x}(x-x_{0})+\frac{\partial f(x_{0},y_{0})}{\partial y}(y-y_{0})
\end{align}$

$\begin{align}
例:{f}(x,y)=4x^7y+5x+7y\quad 求過(1,2)的切平面方程式
\end{align}$

$\begin{align}
z-f(1,2)=\frac{\partial f(1,2) }{\partial x}(x-1)+\frac{\partial f(1,2)}{\partial y}(y-2)\Rightarrow z-8=61(x-1)+11(y-2)
\end{align}$

$\begin{align}
連鎖率
\end{align}$

$\begin{align}
z=f(x,y),x=g(t),y=h(t)\\
\frac{df}{dt} =\frac{\partial f}{\partial g}\frac{dg}{dt}+\frac{\partial f}{\partial h}\frac{dh}{dt}
\end{align}$

$\begin{align}
例1:z=f(x,y)=x^{3}+y^{5},x=g(t)=10t,y=h(t)=cos(t)
\end{align}$

$\begin{align}
\frac{df}{dt} =\frac{\partial f}{\partial g}\frac{dg}{dt}+\frac{\partial f}{\partial h}\frac{dh}{dt}=3(10t)^{2}\times10+5(cos(t))^{4}\times(-sin(t))\\
\end{align}$

$\begin{align}
z=(10t)^{3}+(cos(t))^{5}
\end{align}$

$\begin{align}
\frac{df}{dt}=3(10t)^{2}\times10+5(cos(t))^{4}\times(-sin(t))\\
\end{align}$
