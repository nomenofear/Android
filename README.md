# Android Layout
	安卓布局练习(LinearLayout,ConstraintLayout,TableLayout)
> **1.LinearLayout**

Run on phone.
![LinearLayout](https://github.com/nomenofear/Android/raw/master/img/LinearLayout.png)

~~~xml
drawable中添加buttonstyle.xml文件来定义button的边框以及button的背景颜色。

<!-- 边框颜色值 -->
<item>
    <shape>
        <solid android:color="#8F8B8B" />
    </shape>
</item>
<!-- 主体背景颜色值,控件间的间距 -->
<item
    android:bottom="2dp"
    android:top="2dp"
    android:left="2dp"
    android:right="2dp">
    <shape>
        <solid android:color="@android:color/black" />
    </shape>
</item>


~~~




> **2.ConstraintLayout**

Run on tablet
![Constraint](https://github.com/nomenofear/Android/raw/master/img/Constraint.png)

> **3.TableLayout**

Run on phone
![TableLayout](https://github.com/nomenofear/Android/raw/master/img/TableLayout.png)
