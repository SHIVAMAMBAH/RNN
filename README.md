### Different Types of Data
- **Time Series** : In a time series data set, the values on successive time-stamps are closely related to one another. If one uses the value of these time-stamps as independent features, then key information about the relationships among the values of these time-stamps is lost. For example, the value of  time series at time t is closely related to its value in the previous window. However, this information is lost when the values at individual time-stamps are treated independently of one another.
- **Text** :  Although text is often processed as bag of words, one can obtain better semantics insights when the ordering of the words is used. In such cases, it is important to construct models that take the sequencing information into account. Text data is most common use of recurrent neural networks.
- **Biological Data** : Bilogical data often contains sequences, in which the symbols might correspond to amino acids or one of the nucleobases that form the building blocks of DNA.

The individual values in a sequene can be either real-valued or symbolic. Real-valued sequences are also referred to as time-series. RNNs can be used for either type of data.<br><br>
Many sequence centric applications like text are often processed as bag of words.

