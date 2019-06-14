
<img align="right" width="650" height="500" src="https://github.com/bheemnitd/Community-Detection-Based-On-Seed-Node/blob/master/community_detection.jpg">

#### Abstract
<p align = 'justify'>From Earlier days Community detection is one of the most popular topic and is an important structure in social network. Community detection is required to define that who is belong to which community. Further numerous approaches are already proposed for finding community over a social network. In <a href = 'https://github.com/bheemnitd/Community-Detection-Based-On-Seed-Node/blob/master/%5BThesis%20PAPER%5D%20A%20new%20Approach%20of%20Community%20Detection%20Based%20on%20seed%20node.pdf'>this</a> paper we will propose a new approach of community detection based on seed centric approach in which we will discuss that how we are finding the seed node. We will also discuss about how seed set is expanding from remaining nodes which do not belongs to any community directly. The basic idea underlying in this approach is to identifying special nodes in the target network, called seed so that we can detect good community. Different algorithms adopt different approaches of seed selection definitions and seed set expansion definitions for communities construction. We will apply our algorithm in three classical data sets and will compare to other algorithms.<p>


#### Dataset

<table>

  <tr align = 'center'><td align = 'left'><h5> Network name</h5></td><td><h5>#node</h5></td><td><h5>#edge</h5></td><td><h5>Refrences</h5></td></tr>
  <tr align = 'center'><td align = 'left'>Karated Club</td><td>34</td><td>78</td><td>[1]</td></tr>
  <tr align = 'center'><td align = 'left'>Dolphins Network</td><td>62</td><td>159</td><td>[2]</td></tr>
  <tr align = 'center'><td align = 'left'>Political Books</td><td>105</td><td>441</td><td><center>[3]</center></td></tr>

</table>

#### Experimental Result.

<table>
  <tr align = 'center'><td align = 'left'><h5> Network name</h5></td><td><h5>#node</h5></td><td><h5>#edge</h5></td><td><h5>#Community</h5></td><td><h5>Modularity</h5></td><td><h5>Refrences</h5></td></tr>
  <tr align = 'center'><td align = 'left'>Karated Club</td><td>34</td><td>78</td><td>2</td><td>0.371</td><td>[1]</td></tr>
  <tr align = 'center'><td align = 'left'>Dolphins Network</td><td>62</td><td>159</td><td>5</td><td>0.505</td><td>[2]</td></tr>
  <tr align = 'center'><td align = 'left'>Political Books</td><td>105</td><td>441</td><td>4</td><td>0.524</td><td>[3]</td></tr>
</table>  

![alt text](https://github.com/bheemnitd/Community-Detection-Based-On-Seed-Node/blob/master/Selection_007.jpg) 

![alt text](https://github.com/bheemnitd/Community-Detection-Based-On-Seed-Node/blob/master/Selection_008.jpg) 

![alt text](https://github.com/bheemnitd/Community-Detection-Based-On-Seed-Node/blob/master/Selection_009.jpg) 


### Comparision between some popular existed community detection algorithm and our algorithm
<table>
  <tr align = 'center'><td><h5>Name of Network</h5></td><td><h5>Algorithms</h5></td><td><h5>Communities</h5></td><td><h5>Modularity</h5></td></tr>
  <tr align = 'center'><td>Karate Club</td><td>Newman[1]</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Lovain[5]</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Walktrap[6]</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Licod[7]</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Yasca[8]</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td><b>Our Algorithm</b></td><td><b>5</b></td><td><b>0.40</b></td></tr>
  
  <tr align = 'center'><td>Dolphins</td><td>Newman</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Lovain</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Walktrap</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Licod</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Yasca</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td><b>Our Algorithm</b></td><td><b>5</b></td><td><b>0.40</b></td></tr>
  
  <tr align = 'center'><td>Political Books</td><td>Newman</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Lovain</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Walktrap</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Licod</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td>Yasca</td><td>5</td><td>0.40</td></tr>
  <tr align = 'center'><td> </td><td><b>Our Algorithm</b></td><td><b>5</b></td><td><b>0.40</b></td></tr>

</table>

![alt text](https://github.com/bheemnitd/Community-Detection-based-on-seed-node/blob/master/download%202.png)
