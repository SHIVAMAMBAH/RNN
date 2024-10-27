### Different Types of Data
- **Time Series** : In a time series data set, the values on successive time-stamps are closely related to one another. If one uses the value of these time-stamps as independent features, then key information about the relationships among the values of these time-stamps is lost. For example, the value of  time series at time t is closely related to its value in the previous window. However, this information is lost when the values at individual time-stamps are treated independently of one another.
- **Text** :  Although text is often processed as bag of words, one can obtain better semantics insights when the ordering of the words is used. In such cases, it is important to construct models that take the sequencing information into account. Text data is most common use of recurrent neural networks.
- **Biological Data** : Bilogical data often contains sequences, in which the symbols might correspond to amino acids or one of the nucleobases that form the building blocks of DNA.

The individual values in a sequene can be either real-valued or symbolic. Real-valued sequences are also referred to as time-series. RNNs can be used for either type of data.<br><br>
Many sequence centric applications like text are often processed as bag of words. Such an approach ignores the ordering of words in the documents, and work well for docuemnts of reasonable size. However, the applications where the semantic interpretation of the sentence is important, or in which the size of the text segment is relatively small (e.g. a single sentence), such an approach is simply inadequate.
>A bag-of-words is a representation of text that describes the occurrence of words within a document. It involves two things: a vocabulary of known words and a measure of the presence of known words. The order or structure of words in the document is discarded.

Let's take an example : <br>
- The cat chased the mouse.
- The mouse chased the cat.

The sentence are clearly very different. However, the bag of words representation would deem them identical. Hence, this type of representation works well for simpler application (such as claffication), but a greater degree of linguistic intelligence is required for more sophistcated applications in difficult settings such as sentimental analysis, machine translation, or information exactraction.
