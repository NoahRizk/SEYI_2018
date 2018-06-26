#Section 1

1. The "replace" argument replaces the numbers drawn in the sampling.
2. MyMatrix*1
3. apply(MyMatric, 1, sum) == ncol(MyMatrix)

#Section 2

1. 16
2. colSums(MyMatrix)
3. apply(MyMatrix, 2, prod)
4. MyMatrix[MyMatrix==10]<-12
5. 33
6. MyDataFrame <- as.data.frame(MyMatrix), MyDataFrame[,12]<- as.character(MyDataFrame[,12])
7. RowSums <- rowSums(MyMatrix)
MyDataFrame$V13 <- RowSums > 70
