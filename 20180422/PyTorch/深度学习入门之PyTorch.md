深度學習入門之PyTorch 
```
深度学习入门之PyTorch
廖星宇  電子工業出版社 出版日期: 2017-09-01

https://github.com/L1aoXingyu/code-of-learn-deep-learning-with-pytorch
```
```
第1章深度學習介紹1 


1.1人工智能. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 1 

1.2數據挖掘、機器學習與深度學習. . . . . . . . . . . . . . . . . . . . . . . 2 

1.2.1數據挖掘. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3 

1.2.2機器學習. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 3 

1.2.3深度學習. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 4 

1.3學習資源與建議. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 8 

 

第2章深度學習框架11 

 

2.1深度學習框架介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 11 

2.2 PyTorch介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13 

2.2.1什麼是PyTorch . . . . . . . . . . . . . . . . . . . . . . . . . . . . 13

2.2.2為何要使用PyTorch . . . . . . . . . . . . . . . . . . . . . . . . . . 14 

2.3配置PyTorch深度學習環境. . . . . . . . . . . . . . . . . . . . . . . . . . 15 

2.3.1操作系統的選擇. . . . . . . . . . . . . . . . . . . . . . . . . . . . 15 

2.3.2 Python開發環境的安裝. . . . . . . . . . . . . . . . . . . . . . . . 16 

2.3.3 PyTorch的安裝. . . . . . . . . . . . . . . . . . . . . . . . . . . . 18 

 

第3章多層全連接神經網絡24 

 

3.1熱身：PyTorch基礎. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 24 

3.1.1 Tensor（張量） . . . . . . . . . . . . . . . . . . . . . . . . . . . . 24 

3.1.2 Variable（變量） . . . . . . . . . . . . . . . . . . . . . . . . . . . 26 

3.1.3 Dataset（數據集） . . . . . . . . . . . . . . . . . . . . . . . . . . . 28

3.1.4 nn.Module（模組） . . . . . . . . . . . . . . . . . . . . . . . . . . 29 

3.1.5 torch.optim（優化） . . . . . . . . . . . . . . . . . . . . . . . . . . 30 

3.1.6模型的保存和加載. . . . . . . . . . . . . . . . . . . . . . . . . . 31 

3.2線性模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32 

3.2. 1問題介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 32 

3.2.2一維線性回歸. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 33 

3.2.3多維線性回歸. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 34 

3.2.4一維線性回歸的代碼實現. . . . . . . . . . . . . . . . . . . . . . 35 

3.2.5多項式回歸. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 38

3.3分類問題. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42 

3.3.1問題介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42 

3.3.2 Logistic起源. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42 

3.3.3 Logistic分佈. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 42 

3.3.4二分類的Logistic回歸. . . . . . . . . . . . . . . . . . . . . . . . 43 

3.3.5模型的參數估計. . . . . . . . . . . . . . . . . . . . . . . . . . . . 44 

3.3.6 Logistic回歸的代碼實現. . . . . . . . . . . . . . . . . . . . . . . 45 

3.4簡單的多層全連接前向網絡. . . . . . . . . . . . . . . . . . . . . . . . . 49 

3.4.1模擬神經元. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 49

3.4.2單層神經網絡的分類器. . . . . . . . . . . . . . . . . . . . . . . . 50 

3.4.3激活函數. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 51 

3.4.4神經網絡的結構. . . . . . . . . . . . . . . . . . . . . . . . . . . . 54 

3.4.5模型的表示能力與容量. . . . . . . . . . . . . . . . . . . . . . . . 55 

3.5深度學習的基石：反向傳播算法. . . . . . . . . . . . . . . . . . . . . . . 57 

3.5.1鍊式法則. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 57 

3.5.2反向傳播算法. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 58 

3.5.3 Sigmoid函數舉例. . . . . . . . . . . . . . . . . . . . . . . . . . . 58 

3.6各種優化算法的變式. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59 

3.6.1梯度下降法. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 59

3.6.2梯度下降法的變式. . . . . . . . . . . . . . . . . . . . . . . . . . 62 

3.7處理數據和訓練模型的技巧. . . . . . . . . . . . . . . . . . . . . . . . . 64 

3.7.1數據預處理. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 64 

3.7.2權重初始化. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 66 

3.7.3防止過擬合. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 67 

3.8多層全連接神經網絡實現MNIST手寫數字分類. . . . . . . . . . . . . . 69 

3.8.1簡單的三層全連接神經網絡. . . . . . . . . . . . . . . . . . . . . 70 

3.8.2添加激活函數. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 70 

3.8.3添加批標準化. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 71 

3.8.4訓練網絡. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 71 

 

第4章卷積神經網絡76

 

4.1主要任務及起源. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 76 

4.2卷積神經網絡的原理和結構. . . . . . . . . . . . . . . . . . . . . . . . . 77 

4.2.1卷積層. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 80 

4.2.2池化層. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 84 

4.2.3全連接層. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 85 

4.2.4卷積神經網絡的基本形式. . . . . . . . . . . . . . . . . . . . . . 85 

4.3 PyTorch卷積模塊. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 87 

4.3.1卷積層. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 87 

4.3.2池化層. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 88

4.3.3提取層結構. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 90 

4.3.4如何提取參數及自定義初始化. . . . . . . . . . . . . . . . . . . . 91 

4.4卷積神經網絡案例分析. . . . . . . . . . . . . . . . . . . . . . . . . . . . 92 

4.4.1 LeNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 93 

4.4.2 AlexNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 94 

4.4.3 VGGNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 95 

4.4.4 GoogLeNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 98 

4.4.5 ResNet . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 100 

4.5再實現MNIST手寫數字分類. . . . . . . . . . . . . . . . . . . . . . . . . 103

4.6圖像增強的方法. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 105 

4.7實現cifar10分類. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 107 

 

第5章循環神經網絡111 

 

5.1循環神經網絡. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 111 

5.1.1問題介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 112 

5.1.2循環神經網絡的基本結構. . . . . . . . . . . . . . . . . . . . . . 112 

5.1.3存在的問題. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 115 

5.2循環神經網絡的變式：LSTM與GRU . . . . . . . . . . . . . . . . . . . . 116 

5.2.1 LSTM . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 116 

5.2. 2 GRU . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 119

5.2.3收斂性問題. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 120 

5.3循環神經網絡的PyTorch實現. . . . . . . . . . . . . . . . . . . . . . . . 122 

5.3.1 PyTorch的循環網絡模塊. . . . . . . . . . . . . . . . . . . . . . . 122 

5.3.2實例介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 127 

5.4自然語言處理的應用. . . . . . . . . . . . . . . . . . . . . . . . . . . . . 131 

5.4.1詞嵌入. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 131 

5.4.2詞嵌入的PyTorch實現. . . . . . . . . . . . . . . . . . . . . . . . 133 

5.4.3 N Gram模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 133 

5.4.4單詞預測的PyTorch實現. . . . . . . . . . . . . . . . . . . . . . . 134

5.4.5詞性判斷. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 136 

5.4.6詞性判斷的PyTorch實現. . . . . . . . . . . . . . . . . . . . . . . 137 

5.5循環神經網絡的更多應用. . . . . . . . . . . . . . . . . . . . . . . . . . . 140 

5.5.1 Many to one . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 140 

5.5.2 Many to Many（ shorter） . . . . . . . . . . . . . . . . . . . . . . . 141 

5.5.3 Seq2seq . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 141 

5.5.4 CNN+RNN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 142 

 

第6章生成對抗網絡144 

 

6.1生成模型. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 144 

6.1 .1自動編碼器. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 145

6.1.2變分自動編碼器. . . . . . . . . . . . . . . . . . . . . . . . . . . . 150 

6.2生成對抗網絡. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 153 

6.2.1何為生成對抗網絡. . . . . . . . . . . . . . . . . . . . . . . . . . 153 

6.2.2生成對抗網絡的數學原理. . . . . . . . . . . . . . . . . . . . . . 160 

6.3 Improving GAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164 

6.3.1 Wasserstein GAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . 164 

6.3.2 Improving WGAN . . . . . . . . . . . . . . . . . . . . . . . . . . . 167 

6.4應用介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 168 

6.4.1 Conditional GAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . 168

6.4.2 Cycle GAN . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 170 

 

第7章深度學習實戰173 

 

7.1實例一——貓狗大戰：運用預訓練卷積神經網絡進行特徵提取與預測. 173 

7.1.1背景介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 174 

7.1.2原理分析. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 174 

7.1.3代碼實現. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 177 

7.1.4總結. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 183 

7.2實例二——Deep Dream：探索卷積神經網絡眼中的世界. . . . . . . . . 183 

7.2.1原理介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 184 

7.2.2預備知識：backward . . . . . . . . . . . . . . . . . . . . . . . . . 185

7.2.3代碼實現. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 190 

7.2.4總結. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 195 

7.3實例三——Neural-Style：使用PyTorch進行風格遷移. . . . . . . . . . . 196 

7.3.1背景介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 196 

7.3.2原理分析. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 197 

7.3.3代碼實現. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 199 

7.3.4總結. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 205 

7.4實例四——Seq2seq：通過RNN實現簡單的Neural Machine Translation . 205 

7.4.1背景介紹. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 206

7.4.2原理分析. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 206 

7.4.3代碼實現. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 209 

7.4.4總結. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 221

```
