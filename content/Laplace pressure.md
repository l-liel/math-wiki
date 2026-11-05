---
draft: true
---
The Young-Laplace equation for an arbitrary smooth curved surface (general shape), $\Delta P = \gamma \left( \frac{1}{R_1} + \frac{1}{R_2} \right)$, can also be elegantly derived using the principle of virtual work (the balance of energy under infinitesimal changes), just like the spherical case we looked at earlier.

For a general curved surface, we consider a minute "rectangular patch" (infinitesimal surface element) and expand it.

### 1. Setting up the Infinitesimal Surface Element

At any arbitrary point on the curved surface, let the radii of curvature along two mutually orthogonal principal curvature directions be $R_1$ and $R_2$.

Consider a small rectangular surface element containing this point, with infinitesimal side lengths $x$ and $y$ along the respective directions.

- The area $A$ of this infinitesimal surface can be expressed as:  
    
    $$A = x \cdot y$$

### 2. Virtual Expansion

Assume that this curved surface undergoes a translational movement (expansion) outward in the normal direction by an infinitesimal distance $dz$ due to the internal Laplace pressure $\Delta P$. At this time, the radii of curvature change to $R_1 \to R_1 + dz$ and $R_2 \to R_2 + dz$, respectively.

From the similarity relationship, the expanded side lengths $x'$ and $y'$ change as follows:  

$$x' = x \cdot \frac{R_1 + dz}{R_1} = x \left( 1 + \frac{dz}{R_1} \right)$$$$y' = y \cdot \frac{R_2 + dz}{R_2} = y \left( 1 + \frac{dz}{R_2} \right)$$

### 3. Calculation of Energy Changes

#### ① Energy due to surface area change ($dW_{\text{surface}}$)

Calculate the new area $A'$ after expansion (terms of $dz^2$ are extremely small and thus neglected):  

$$A' = x' \cdot y' = x \cdot y \left( 1 + \frac{dz}{R_1} \right) \left( 1 + \frac{dz}{R_2} \right) \approx xy \left( 1 + \frac{dz}{R_1} + \frac{dz}{R_2} \right)$$$$A' \approx xy + xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

Therefore, the infinitesimal change in area $dA = A' - A$ is:  

$$dA = xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

From the definition of surface tension, the energy required for this area increase is:  

$$dW_{\text{surface}} = \gamma \cdot dA = \gamma \cdot xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz \quad \text{—— (1)}$$

#### ② Work done by pressure ($dW_{\text{pressure}}$)

When the Laplace pressure $\Delta P$ pushes out a surface of area $A = xy$ by a distance $dz$, the volume change is $dV = xy \cdot dz$.

Therefore, the work done by the pressure-generating force is:  

$$dW_{\text{pressure}} = \Delta P \cdot dV = \Delta P \cdot xy \cdot dz \quad \text{—— (2)}$$

### 4. Derivation of the General Formula from the Balance Equation

By the law of conservation of energy (the principle of virtual work), $dW_{\text{pressure}} = W_{\text{surface}}$.  

$$\Delta P \cdot xy \cdot dz = \gamma \cdot xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

Dividing both sides by the common term $xy \cdot dz$, we derive the Young-Laplace equation for a general shape:  

$$\Delta P = \gamma \left( \frac{1}{R_1} + \frac{1}{R_2} \right)$$

As shown above, no matter how complex the shape may be, by isolating a local infinitesimal surface and considering geometric similarity (the elongation of sides due to $dz$), you can directly derive this beautiful formula from the definition of surface tension.

Were there any parts of the geometric relationships in the general derivation (such as the calculation of similarity ratios) or the intermediate equations that caught you up?

- I'd like a more detailed, diagram-based supplementary explanation of the concept of similarity ratios for infinitesimal surface elements.
    
- I want to know how this general formula is expressed from the perspective of differential geometry (using mean curvature $H$).
    
- I want to know how it behaves when the radius of curvature becomes negative (saddle-shaped or undulating surfaces).
    

I am happy to explain it more clearly according to your preferences!

Young-Laplace Equation Derivation

The Young-Laplace equation for an arbitrary smooth curved surface (general shape), $\Delta P = \gamma \left( \frac{1}{R_1} + \frac{1}{R_2} \right)$, can also be elegantly derived using the principle of virtual work (the balance of energy under infinitesimal changes), just like the spherical case we looked at earlier.

  

For a general curved surface, we consider a minute "rectangular patch" (infinitesimal surface element) and expand it.

  

### 1. Setting up the Infinitesimal Surface Element

At any arbitrary point on the curved surface, let the radii of curvature along two mutually orthogonal principal curvature directions be $R_1$ and $R_2$.

  

Consider a small rectangular surface element containing this point, with infinitesimal side lengths $x$ and $y$ along the respective directions.

  

- The area $A$ of this infinitesimal surface can be expressed as:
    
      
    $$A = x \cdot y$$

### 2. Virtual Expansion

Assume that this curved surface undergoes a translational movement (expansion) outward in the normal direction by an infinitesimal distance $dz$ due to the internal Laplace pressure $\Delta P$.

At this time, the radii of curvature change to $R_1 \to R_1 + dz$ and $R_2 \to R_2 + dz$, respectively.

  

From the similarity relationship, the expanded side lengths $x'$ and $y'$ change as follows:

  
$$x' = x \cdot \frac{R_1 + dz}{R_1} = x \left( 1 + \frac{dz}{R_1} \right)$$$$y' = y \cdot \frac{R_2 + dz}{R_2} = y \left( 1 + \frac{dz}{R_2} \right)$$

### 3. Calculation of Energy Changes

#### ① Energy due to surface area change ($dW_{\text{surface}}$)

Calculate the new area $A'$ after expansion (terms of $dz^2$ are extremely small and thus neglected):

  
$$A' = x' \cdot y' = x \cdot y \left( 1 + \frac{dz}{R_1} \right) \left( 1 + \frac{dz}{R_2} \right) \approx xy \left( 1 + \frac{dz}{R_1} + \frac{dz}{R_2} \right)$$$$A' \approx xy + xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

Therefore, the infinitesimal change in area $dA = A' - A$ is:

  
$$dA = xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

From the definition of surface tension, the energy required for this area increase is:

  
$$dW_{\text{surface}} = \gamma \cdot dA = \gamma \cdot xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz \quad \text{—— (1)}$$

#### ② Work done by pressure ($dW_{\text{pressure}}$)

When the Laplace pressure $\Delta P$ pushes out a surface of area $A = xy$ by a distance $dz$, the volume change is $dV = xy \cdot dz$.

  

Therefore, the work done by the pressure-generating force is:

  
$$dW_{\text{pressure}} = \Delta P \cdot dV = \Delta P \cdot xy \cdot dz \quad \text{—— (2)}$$

### 4. Derivation of the General Formula from the Balance Equation

By the law of conservation of energy (the principle of virtual work), $dW_{\text{pressure}} = W_{\text{surface}}$.

  
$$\Delta P \cdot xy \cdot dz = \gamma \cdot xy \left( \frac{1}{R_1} + \frac{1}{R_2} \right) dz$$

Dividing both sides by the common term $xy \cdot dz$, we derive the Young-Laplace equation for a general shape:

  
$$\Delta P = \gamma \left( \frac{1}{R_1} + \frac{1}{R_2} \right)$$

As shown above, no matter how complex the shape may be, by isolating a local infinitesimal surface and considering geometric similarity (the elongation of sides due to $dz$), you can directly derive this beautiful formula from the definition of surface tension.

  

Were there any parts of the geometric relationships in the general derivation (such as the calculation of similarity ratios) or the intermediate equations that caught you up?

  

- I'd like a more detailed, diagram-based supplementary explanation of the concept of similarity ratios for infinitesimal surface elements.
    
      
    
- I want to know how this general formula is expressed from the perspective of differential geometry (using mean curvature $H$).
    
      
    
- I want to know how it behaves when the radius of curvature becomes negative (saddle-shaped or undulating surfaces).
    
      
    


任意の場所をクリックして直接入力や編集を行うか、テキストを選択して Gemini に変更を指示します。任意の滑らかな曲面（一般の形状）における**ヤング・ラプラスの式 $\Delta P = \gamma \left( \frac{1}{R_1} + \frac{1}{R_2} \right)$** も、先ほどの球体と同じく==**仮想仕事の原理（微小に変化させたときのエネルギーのつり合い）**を用いて美しく導出できます==。

一般の曲面では、微小な「長方形のパッチ（微小面要素）」を考えて膨張させます。

---

1. 微小面要素の設定

曲面上の任意の点において、互いに直交する2つの主曲率方向の半径を **$R_{1}$** および **$R_{2}$** とします。  
この点を含み、それぞれの方向に沿った微小な辺の長さが **$x$** および **$y$** であるような、小さな長方形の面要素を考えます。

- この微小面の面積 $A$ は次のように表せます。  
    $A=x\cdot y$

2. 仮想的に膨張させる

この曲面が、内部からのラプラス圧 $\Delta P$ によって、法線方向に**ごくわずかな距離 $dz$** だけ外側に並進移動（膨張）したと仮定します。

このとき、曲率半径はそれぞれ $R_1 \rightarrow R_1 + dz$、$R_2 \rightarrow R_2 + dz$ に変化します。  
相似の関係から、膨張後の辺の長さ $x^{\prime }$ と $y^{\prime }$ は以下のように変化します。  
$x^{\prime }=x\cdot \frac{R_{1}+dz}{R_{1}}=x\left(1+\frac{dz}{R_{1}}\right)$  
$y^{\prime }=y\cdot \frac{R_{2}+dz}{R_{2}}=y\left(1+\frac{dz}{R_{2}}\right)$

3. エネルギー変化の計算

① 表面積変化によるエネルギー（$dW_{\text{surface}}$）

膨張後の新しい面積 $A^{\prime }$ を計算します（\(dz^{2}$ の項は極めて小さいので無視します）。  
$A^{\prime }=x^{\prime }\cdot y^{\prime }=x\cdot y\left(1+\frac{dz}{R_{1}}\right)\left(1+\frac{dz}{R_{2}}\right)\approx xy\left(1+\frac{dz}{R_{1}}\frac{dz}{R_{2}}\right)$  
$A^{\prime }\approx xy+xy\left(\frac{1}{R_{1}}+\frac{1}{R_{2}}\right)dz$

したがって、面積の微小変化 $dA = A' - A$ は：  
$dA=xy\left(\frac{1}{R_{1}}+\frac{1}{R_{2}}\right)dz$

表面張力の定義より、この面積増加に必要なエネルギーは：  
$dW_{\text{surface}}=\gamma \cdot dA=\gamma \cdot xy\left(\frac{1}{R_{1}}+\frac{1}{R_{2}}\right)dz\quad \text{—— (1)}$

② 圧力による仕事（$dW_{\text{pressure}}$）

ラプラス圧 $\Delta P$ が、面積 $A = x y$ の面を距離 $dz$ だけ押し広げたときの体積変化は $dV = x y \cdot dz$ です。  
したがって、圧力を生み出す力がした仕事は：  
$dW_{\text{pressure}}=\Delta P\cdot dV=\Delta P\cdot xy\cdot dz\quad \text{—— (2)}$

4. つり合いの式から一般式の導出

エネルギー保存則（仮想仕事の原理）により、$dW_{\text{pressure}} = dW_{\text{surface}}$ となります。  
$\Delta P\cdot xy\cdot dz=\gamma \cdot xy\left(\frac{1}{R_{1}}+\frac{1}{R_{2}}\right)dz$

両辺にある共通の項 **$x y \cdot dz$** で割ると、一般形状におけるヤング・ラプラスの式が導出されます。

$\Delta P=\gamma \left(\frac{1}{R_{1}}+\frac{1}{R_{2}}\right)$

---

このように、どんなに複雑な形状であっても、局所的な微小面を切り取って幾何学的な相似（$dz$ による辺の伸び）を考えることで、表面張力の定義から直接この美しい公式を導くことができます。

一般形状の導出における**幾何学的な関係（相似比の計算など）**や、途中の数式で引っかかる部分はありましたか？

- 微小面要素の**相似比の考え方**をもう少し詳しく図解的に補足してほしい
- この一般式を**微分幾何学（平均曲率** \(H$）の視点からどう表現するのか知りたい
- 曲率半径が負になる場合（**サドル型・凹凸がある面**）の挙動を知りたい

ご希望に合わせてさらに分かりやすく説明します。