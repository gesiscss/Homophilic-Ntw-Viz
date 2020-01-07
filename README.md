# Visualizing networks with homophily and two groups of different sizes

The visualisation of a social network which is based on [Karimi et al. 2017](https://arxiv.org/pdf/1702.00150.pdf) model. In the model, it is assumed that there is an underlying **homophily** parameter due to node attributes which leads to the formation of links between members of each group in the network. The model considers the **preferential attachment** property proposed by Barabási and Albert. For the implementation of the model in **python**, you can visit [this repository](https://github.com/frbkrm/HomophilicNtwMinorities).

For users who are not familiar by how to render **html files**, here is the solution:

* Download a copy of an existing Git repository on your machine using `git clone https://github.com/neuronphysics/Homophilic-Ntw-Viz.git` command.


* Download and install [brackets](http://brackets.io/) which is an editor for web developers.


* Go to the *network project* and open the *network.html* using **File> Open Folders** in your brackets editor.


* select **File > Live Preview** or click the **lightning bolt** icon on the rightside toolbar. Brackets will launch Chrome and open your file in a new tab. 

The output should be similar to the following image:

![network](https://github.com/neuronphysics/Homophilic-Ntw-Viz/blob/master/network.jpg "homophily network")

In this model, nodes have only two attributes, so they are assigned to two groups with different sizes. The homophily parameter alters between ```0``` to ```1```.  Here it was posited that group *a* is the **minority group** in the network and group *b* has the majority. The nodes in the minority group are shown in **red**. 

The parameters that can be changed are:

* **Number of nodes** - The number of nodes which create the network

* **Number of edges of a new node** - The **minimum** number of edges which a node can have in this network

* **Minority fraction** - The fraction of nodes that belong to the group *a* 

* $`h_{ab}`$ - The probability of connection between group *a* and *b*

* $`h_{ba}`$ - The probability of connection between the majority group members with the minorities

* **Press button generate** - Make a new realization of the network with the modified input parameters

**The colour bars** (the top left side) illustrate the *fraction* of minority nodes (red) in the **top 10%** with the highest degree inside the generated network.

## Related Works
* Lee, E., Karimi, F., Wagner, C., Jo, H. H., Strohmaier, M., & Galesic, M. (2019). Homophily and minority-group size explain perception biases in social networks. Nature human behaviour, 3(10), 1078-1087.

* Karimi, F., Génois, M., Wagner, C., Singer, P., & Strohmaier, M. (2018). Homophily influences ranking of minorities in social networks. Scientific reports, 8(1), 11077.

* Kohne, J., Gallagher, N., Kirgil, Z. M., Paolillo, R., Padmos, L., & Karimi, F. (2020). The Role of Network Structure and Initial Group Norm Distributions in Norm Conflict. In Computational Conflict Research (pp. 113-140). Springer, Cham.

## Authors of the code
* **Fariba Karimi**
* **Zahra Sheikhbahaee** - PhD in Astrophysics 

