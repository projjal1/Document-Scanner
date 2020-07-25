# Document-Scanner
Python Script written with OpenCV to implement document scanner.

In this scenario we make use of Perspective transform to get the top-down view of the image in a plane.

Four-Point Transform is applied to approximate Region of Interest and filter selected area from the image provided.
Here we assume that the document will be one with a rectangular contour, and thus apply transformations accordingly.

More on Region on Interest at <a href='https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjQvdH3zufqAhUjIbcAHYUuCAgQFjAHegQIHBAG&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FRegion_of_interest&usg=AOvVaw3UJpIgOmdL5uKfAtBzPuN_'>Wiki Link</a>

<a href='https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwitlaWsz-fqAhVS8HMBHX9nAPsQFjAVegQIFhAS&url=https%3A%2F%2Fwww.idesign.wiki%2Ftag%2Ffour-point-perspective%2F&usg=AOvVaw1C42-XY1-rip0dkZqcUKHO'>What is Four Point Transform and its Application?</a>

<h2>Command to Start Execution</h2>
<pre>python script.py</pre>
  
 <h2>Set the input image path</h2>
<pre>img,ratio,edged,orig=read_img("image.jpg")</pre>

 Change file to your file_path

<h2>Dependencies:</h2>
<ul>
  <li>Python 3.5+</li>
  <li>Numpy</li>
  <li>OpenCV 2.4+</li>
  <li>imutils</li>
</ul>

<h2>Output</h2>
<table>
  <tr>
    <th>Input</th>
    <th>Output</th>
  </tr>
  <tr>
    <td><img src='https://github.com/projjal1/Document-Scanner/blob/master/image.jpg' height='650'/></td>
    <td><img src='https://github.com/projjal1/Document-Scanner/blob/master/Scanned.jpg' height='650'/></td> 
</table>  

<h2>Note: Take image of document against a dark background.</h2>

<h2>Attributions: PyImageSearch</h2>
