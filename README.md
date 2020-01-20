# On Automated and Practical Trust Computation in IoT using Multi-attribute Decision Making and Subjective Logic

In this directory, we present the supplemental material for our paper entitled "On Automated and Practical Trust Computation in IoT using Multi-attribute Decision Making and Subjective Logic". The following files are included in this directory: 

* <b>weight_approximation.ipynb:</b> In this file, we present surrogate weights that we obtain by applying different weight approximation methods, namely Rank Order Centroid (ROC), Rank Sum (RS), and Rank Reciprocal (RR).



## Weight Approximation Methods

---
The table below shows the surrogate weights that we obtain by applying three widely used weight approximation methods in Multi Attribute Decision Making (MADM) approaches. These methods are: Rank Order Centroid (ROC), Rank Sum (RS), and Rank Reciprocal (RR). For computing the weights in the table, we use the formulae below the table and we assume the rank of the attributes given in the table.




\begin{array}{lllll}
\hline 
  Rank & Attribute & ROC^a & RS^b & RR^c \\\hline
  1    & Key freshness  & 0.6111              & 0.5000            & 0.5455 \\
  2    & Data freshness & 0.2778              & 0.3333            & 0.2727 \\
  3    & Temperature    & 0.1111              & 0.1667            & 0.1818 \\\hline 
\end{array}



### Formulae

In the formulae below, $R_j$ denotes the rank of an attribute $j$.

* ROC method: 

\begin{equation*}
^a w_j= 1/n\sum_{k=R_j}^{n} 1/k
\end{equation*}

* RS method: 

\begin{equation*}
^b w_j= 2(n+1-R_j)/n(n+1)
\end{equation*}


* RR method: 

\begin{equation*}
^c w_i=(1/R_j)/(\sum_{k=R_j}^{n} 1/k)
\end{equation*}











<!-- 
    * Nested bullet
        * Sub-nested bullet etc
-->
