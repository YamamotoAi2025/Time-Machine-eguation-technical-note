# Time-Machine-eguation-technical-note
technical note 1
# タイムマシン方程式 技術ノート（試作稿）

## 1. 拡張座標と変数分離

- 実空間座標:  
  $\mathbf{x} = (x,y,z)$

- 時間空間座標:  
  $\boldsymbol{\tau} = (\tau_1, \tau_2, \tau_3), \quad \rho = |\boldsymbol{\tau}|$

- 状態関数の分離:  
  $
  \Psi(\mathbf{x}, \boldsymbol{\tau}) = X(\mathbf{x}) \, T(\boldsymbol{\tau})
  $

- 時間空間の球対称展開:  
  $
  T(\boldsymbol{\tau}) = R(\rho) \, Y_\ell(\Omega_\tau)
  $

---

## 2. 時間空間の放射状方程式

- 時間素粒子の質量: $m = i\mu$  
- 放射状方程式:  

$
\frac{d^2R}{d\rho^2} + \frac{2}{\rho}\frac{dR}{d\rho} 
- \frac{\ell(\ell+1)}{\rho^2}R 
+ \left[ U(\rho) - \mu^2 \right]R = 0


---

## 3. 重力波エネルギーの三分割

$$
E_{\text{GW}} = E_{\text{space}} + E_{\text{time}} + E_{\text{interaction}}
$$

- $E_{\text{space}}$: 実空間の曲率エネルギー  
- $E_{\text{time}}$: 時間空間（時間素粒子）由来のエネルギー  
- $E_{\text{interaction}}$: 相互作用項


この分割により、重力波観測を通して **時間素粒子（マイナスエネルギー）の痕跡を分離・解析**できる可能性がある。

---
