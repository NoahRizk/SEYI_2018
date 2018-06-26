1. data.frame, class()

2. vector, is(precip,"vector")

3. data.matrix(trees) or as(trees,"matrix")

4. Atlanta, precip[14]

5. list(precip,trees,mtcars)

6. is(precip,"numeric")

7. mtcars[2,7], mtcars["Mazda RX4 Wag",7], mtcars["Mazda RX4 Wag","qsec"], mtcars[,"qsec"][2]

8. precip[c("Juneau","Phoenix","Sacarmento")]<-c[23,46,12]

9. any(trees[,"Girth"]>trees[,"Volume"])

10. A<-sum(trees["Height"]), B<-sum(mtcars["Valiant",]), C<-sum(precip[1:8]), (C/B)+A = 2356.628