### Graphical User Interface:
>
![image](./README/README1.png)

##### 補充: 計算點是否在bbox內部
</br>step1 利用bbox的四個點找出法向量，計算出方程式a、b的比例
</br>step2 利用bbox的四個點找出可能出現在bbox內部的點之x、y方向上的臨界值
</br>step3 藉由下圖的方法判斷點是否在bbox內
>
![image](./README/README2.png)