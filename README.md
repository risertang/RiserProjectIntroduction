## 由虚幻GlobalShader实现的体积云(非体积云组件)

### 1. 效果图

![image-20231109155616220](assets/image-20231109155616220.png)

![image-20231101163808780](assets/image-20231101163808780.png)

![image-20231121194132118](assets/image-20231121194132118.png)

![ScreenShot00019](assets/ScreenShot00019.png)

![ScreenShot00030](assets/ScreenShot00030.png)

### 2. 重投影与空间上采样降低整体云层分辨率

![image-20231121193440222](assets/image-20231121193440222.png)

![1](assets/1.png)![2](assets/2.png)![3](assets/3.png)![4](assets/4.png)![5](assets/5.png)![6](assets/6.png)![7](assets/7.png)![8](assets/8.png)![9](assets/9.png)![10](assets/10.png)![11](assets/11.png)![12](assets/12.png)![13](assets/13.png)![14](assets/14.png)![15](assets/15.png)![16](assets/16-17005670239421.png)

![image-20231121194435245](assets/image-20231121194435245.png)

![image-20231121194514014](assets/image-20231121194514014.png)

### 3. 多重散射与Ambient Light

只有beer powder

![image-20231121194814555](assets/image-20231121194814555.png)

添加光线衰减

![image-20231121194913874](assets/image-20231121194913874.png)

添加大气透视

![image-20231121194939634](assets/image-20231121194939634.png)

添加多重散射近似

![image-20231121195014987](assets/image-20231121195014987.png)

添加Ambient Light

![image-20231121195039544](assets/image-20231121195039544.png)

添加能量守恒方程

![image-20231121195106961](assets/image-20231121195106961.png)
