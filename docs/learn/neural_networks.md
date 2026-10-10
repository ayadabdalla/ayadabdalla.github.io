Have you ever thought about a simple equation you studied in high school physics, maybe $F = ma$? The net force acting on an object is equal to its mass times its acceleration. Now consider adding a new variable. $F = ma + bv$. Now the applied force must also overcome friction, which opposes the object's motion. Different masses and frictional properties will affect the force required to achieve the same acceleration.

Why did we couple $a$ and $v$ with an operation that is addition? This comes from our understanding of the physical world, through experimentation and intuition. What if we add more variables? How should we couple them?

With this introduction, I would like to hint to the reader that neural networks are groups of variables connected through weights, which determine how these variables are combined to solve a problem. A designer can introduce their own bias into how these variables should be connected. This design is called an architecture.

An architecture pushes the model towards learning certain concepts more efficiently and generalizing better, through the bias introduced by the designer.

---

!!! example "Example: a temporal architecture"

    Novel Neural Network Temporal Architecture that is a combination between TCNs (Temporal Convolution Networks) and TAs (Temporal Attention) by Abdullah Ayad

    <figure markdown>
      ![Mouldit multimodal architecture](../assets/mouldit_architecture_multimodal_.png)
      <figcaption>Mouldit multimodal architecture</figcaption>
    </figure>
