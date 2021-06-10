# Hough-Transformation for moon craters detection

<p>Firstly, crater edges will be found by canny operator and then a big crater will detected by hough transformation.</p><br/>

<p align = "center"><img src="https://user-images.githubusercontent.com/67442675/121555417-496cf980-ca13-11eb-94f6-bccd4fd55a0f.png"></p>

<p>Secondly, area of detected big crater will be zoom and, after again edges detection, noisy objects of this area will remove.</p>
<p align = "center"><img src="https://user-images.githubusercontent.com/67442675/121558797-4293b600-ca16-11eb-996c-6d57682cc555.png"></p>

<p>Finally, small craters of a big crater area will found. the number of craters to be detected can be set explicitly. The more craters are specified, the longer it will take to detect them.</p>
<p align="center"><img src="https://user-images.githubusercontent.com/67442675/121560363-b8e4e800-ca17-11eb-9460-9ddac5fcf1b1.png"></p>

<p>Coords and radius of craters will print in the end.</p>
<p align="center"><img src="https://user-images.githubusercontent.com/67442675/121560777-209b3300-ca18-11eb-9cd1-4450a445cd68.png"></p>
