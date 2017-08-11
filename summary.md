# what is Tinder Engine?


今日、多くの先進国では少子高齢化が進行し人口成長の低減が起きている。我が国において人口成長の即席的な指標として用いられている合計特殊出生率(TFR)が政策の意思決定・評価に使われている。
$$
TFR = \sum _{x=15}^{49}{ \frac { f\left(x\right) }{ g\left(x\right) } }
$$

 - $f\left(x\right) $: $x$歳の女性が1年間に生んだ子供の数
 - $g\left(x\right)$: $x$歳の女性の数

政府としては経済成長の増加と賦課方式の年金財政方式の維持のために、この合計特殊出生率の変化率が増加するように政策を実施したいという意向がある。ここで合計特殊出生率変化率の要因を分解することで問題を細分化していく。
$$
\frac { f\left(x\right) }{ g\left(x\right) } = \frac { f\left(x\right) }{ h\left(x\right) } \cdot \frac { h\left(x\right) }{ g\left(x\right) }
$$

 - $h\left(x\right)$: $x$歳で結婚をしている女性の数

$x$世代女性の合計特殊出生率の変化率を以下のように展開する。
$$
TFR \equiv \frac { f\left(x\right) }{ h\left(x\right) },  MF \equiv \frac { f\left(x\right) }{ h\left(x\right) }, MP \equiv \frac { h\left(x\right) }{ g\left(x\right) }
$$

 - $MF$: 有配偶出生率
 - $MP$: 有配偶率

$$
\log { TFR } + \log {MF} + \log {MP}\\
\frac {dTFP/dx}{TFR} = \frac {dMF/dx}{MF} + \frac {dMP/dx}{MP}\\
r_{TFR} = r_{MF} + r_{MP}
$$

上式から人口成長率が逓増し続けるためには、有配偶出生率の成長率と有配偶率の成長率を上昇しなければならない。そのためには、
