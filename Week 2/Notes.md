### Implementing Collaborative Filtering with Tensor Flow

<figure>
    <center>
    <img src="TF Supports Automatic Differentiation.png" alt="TF Supports Automatic Differentiation" style="width:100%">
    <figcaption>TF Supports Automatic Differentiation</figcaption>
</figure>

<figure>
    <center>
    <img src="TF Code Implementation.png" alt="TF Code Implementation" style="width:100%">
    <figcaption>TF Code Implementation</figcaption>
</figure>

### Limitations of Collaborative Filtering
<figure>
    <center>
    <img src="Limitations of Collaborative Filtering.png" alt="Limitations of Collaborative Filtering" style="width:100%">
    <figcaption>Limitations of Collaborative Filtering</figcaption>
</figure>

- Because of the large scale of data nowadays, there is large possibility that they are too many catalog to be recommended, and hence break the recommender system into two different steps

<figure>
    <center>
    <img src="Retrieval.png" alt="Retrieval" style="width:100%">
    <figcaption>Retrieval</figcaption>
</figure>

<figure>
    <center>
    <img src="Ranking.png" alt="Ranking" style="width:100%">
    <figcaption>Ranking</figcaption>
</figure>

- Key Questions: How many to retrieve?
<figure>
    <center>
    <img src="Retrieval Steps.png" alt="Retrieval Steps" style="width:100%">
    <figcaption>Retrieval Steps</figcaption>
</figure>

<figure>
    <center>
    <img src="Code in TF.png" alt="Code in Tensor Flow" style="width:100%">
    <figcaption>Code in Tensor Flow</figcaption>
</figure>
- axis = 1 means normalize the vector to length one