---
description: Introduce nPr
---

# Permutation

{% tabs %}
{% tab title="Q1" %}
5個字母A, B, C, D, E排列成一行，有幾多種可能性？

$$\_ \ \_ \ \_ \ \_ \ \_$$ 
{% endtab %}

{% tab title="A1" %}
$$\underline{5} \times \underline{4} \times \underline{3} \times \underline{2} \times \underline{1} $$ 
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Q2" %}
5個字母A, B, C, D, E抽3個出來排成一行，有幾多種可能性？

$$\_ \ \_ \ \_$$
{% endtab %}

{% tab title="A2" %}
$$\underline{5} \times \underline{4} \times \underline{3}$$ 
{% endtab %}
{% endtabs %}

{% tabs %}
{% tab title="Q3" %}
100個相異符號抽60個出來排列成一行，有幾多種可能性？
{% endtab %}

{% tab title="A3" %}
$$\underline{100} \times \underline{99} \times \cdots \times \underline{62} \times \underline{61} $$ 
{% endtab %}
{% endtabs %}

每次都要寫呢串嘢比較麻煩，不如引入一個符號幫手：

$$
n! = n \times (n-1) \times \cdots \times 2 \times 1
$$

用呢個感歎號\(階乘\)，以上就可以寫成：

{% tabs %}
{% tab title="A1" %}
$$5!$$ 
{% endtab %}

{% tab title="A2" %}
$$
5 \times 4 \times 3 = \frac{5 \times 4 \times 3 \times 2 \times 1}{2 \times 1} = \frac{5!}{2!}
$$
{% endtab %}

{% tab title="A3" %}
$$
100 \times 99 \times \cdots \times 62 \times 61 = \frac{100 \times 99 \times \cdots \times 2 \times 1}{60 \times 59 \times \cdots \times 2 \times 1} = \frac{100!}{60!}
$$
{% endtab %}
{% endtabs %}

從以上例子可以觀察到，n個物件抽r個出來排成一行，可能性有 $$\frac{n!}{(n-r)!}$$ 咁多。呢樣嘢有個符號俾佢：

$$
_nP_r = \frac{n!}{(n-r)!}
$$

