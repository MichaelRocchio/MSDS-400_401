```R
#### QUESTION  3.11  
library(pastecs)
library(DescTools)
df<-c(6,2,4,9,1,3,5)
stat.desc(df)
MeanAD(df, weights = NULL, center = Mean, na.rm = FALSE)
IQR(df)
z_scores <- (df-mean(df))/sd(df)
z_scores_df <- data.frame(df, z_scores)
z_scores_df
```


<dl class=dl-horizontal>
	<dt>nbr.val</dt>
		<dd>7</dd>
	<dt>nbr.null</dt>
		<dd>0</dd>
	<dt>nbr.na</dt>
		<dd>0</dd>
	<dt>min</dt>
		<dd>1</dd>
	<dt>max</dt>
		<dd>9</dd>
	<dt>range</dt>
		<dd>8</dd>
	<dt>sum</dt>
		<dd>30</dd>
	<dt>median</dt>
		<dd>4</dd>
	<dt>mean</dt>
		<dd>4.28571428571429</dd>
	<dt>SE.mean</dt>
		<dd>1.01686459543155</dd>
	<dt>CI.mean.0.95</dt>
		<dd>2.4881780295712</dd>
	<dt>var</dt>
		<dd>7.23809523809524</dd>
	<dt>std.dev</dt>
		<dd>2.6903708365382</dd>
	<dt>coef.var</dt>
		<dd>0.627753195192246</dd>
</dl>




2.04081632653061



3



<table>
<thead><tr><th scope=col>df</th><th scope=col>z_scores</th></tr></thead>
<tbody>
	<tr><td>6         </td><td> 0.6371931</td></tr>
	<tr><td>2         </td><td>-0.8495908</td></tr>
	<tr><td>4         </td><td>-0.1061988</td></tr>
	<tr><td>9         </td><td> 1.7522810</td></tr>
	<tr><td>1         </td><td>-1.2212868</td></tr>
	<tr><td>3         </td><td>-0.4778948</td></tr>
	<tr><td>5         </td><td> 0.2654971</td></tr>
</tbody>
</table>


