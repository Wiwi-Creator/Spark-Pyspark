# Spark/Pyspark 大量資料分析

***
#### Why Spark? :
```markdown

當處理的資料已經大到無法以單一電腦處理時，有以下解法:

1.購買超級電腦( > 1TB 記憶體):RD可以程式碼照code，便可執行。但硬體隨時會不夠，屆時需在往上購買更好的硬體。

2.利用多台電腦打造運算群集，SPARK可以針對運算資源做動態調整且快，而且這個運算叢集可以分配給全公司，成本可以大幅降低。

```
***

#### SPARK Introduction :
```markdown
Spark 採用In-memory運算技術，將運算資料除儲存於記憶體中，相對於使用硬碟儲存等媒介的運算框架(Hadoop)更具速度優勢。

1.運算速度:
  主要把資料暫存在記憶體並將處理資料的部分作優化(EX:減少shuffle)
2.易使用:
  Spark提供了Scala(主流),Python(主流),R,Java的API介面，可以選擇擅長語言做開發。
3.範圍廣:
  可以在Spark做到SQL(Spark SQL)、Spark Streaming(及時串流)、Mlip(Spark的機器學習套件)、GraohX(For 社群網路)
  
**** 註 : 雖可支援多種語言，但實際轉寫程式時，都需使用Sprak的邏輯運作(大量的functional programming的Map Reduce概念)
          需花時間去習慣。

```

#### PYSPARK Introduction :
```markdown
●Apache Spark : 是一個對開發者提供完備的庫和API的集群計算系統，是現今處理巨量資料(Larget-scale Data)及機器學習(ML)主流運算框架
                主打簡單、快速，介面統一，支援多種語言。SparkSQL相當於其中的模塊，在DataFrame API的幫助下可用來處理非結構化數據。
如何透過Anaconda創建pyaprk框架及後續處理應用，可參考[Pyspark創建](https://kknews.cc/zh-tw/code/3qk4o4a.html) 

●Pyspark : 則是以Python開發的Apache Spark介面，我們則可透過Python開發相關應用

**** 註 : Pandas和Pyspark整合度高且API相似。
```
***   
#### Model :

```markdown

   
```
***
#### Process :

```markdown

```
***
#### Basic Web Crawer : 
   
 
 


