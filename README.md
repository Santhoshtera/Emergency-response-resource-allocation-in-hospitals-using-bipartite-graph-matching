# Emergency-response-resource-allocation-in-hospitals-using-bipartite-graph-matching
Allocating the resources in hospitals using bipartite graph matching, used for faster allocation

In this project, we worked on solving a very real and critical problem: how to allocate hospital resources efficiently during emergencies.
When there's a sudden rise in patients, like during a disaster or health crisis, hospitals struggle to assign doctors, beds, or equipment quickly.
We used bipartite graph matching to handle this issue — it’s like a smart way of pairing available resources with patients who need them.
Our main algorithm was Hopcroft-Karp, which uses BFS and DFS to find the best matches in less time.
This method helped in reducing delays, improving response time, and making sure critical patients were treated first.
We built a model where hospital resources and emergency cases are represented as two sets of nodes, and the algorithm finds the best pairings.
We tested it using simulations, and the results showed better utilization of resources and quicker treatment during high-demand times.
The system also adapts in real-time when new cases come in or resources become free, which is very useful in unpredictable situations.
We compared it with traditional methods and found that our approach performed better in both speed and fairness.
The model is also scalable, meaning it can be used for small clinics or large hospital networks.
We added priority handling so that patients with serious conditions are always treated first.
Our project even considered things like load balancing so no doctor or team is overburdened.
This solution has the potential to be used in real hospitals and can save lives by reducing wait times.
In future, we want to add predictive models using machine learning to prepare hospitals even before emergencies happen.
Overall, it was a meaningful project, and we’re proud that our work could make a real difference in healthcare.
