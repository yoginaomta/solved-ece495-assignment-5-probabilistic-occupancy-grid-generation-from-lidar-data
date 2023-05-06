Download Link: https://assignmentchef.com/product/solved-ece495-assignment-5-probabilistic-occupancy-grid-generation-from-lidar-data
<br>
<ul>

 <li>To understand how to use lidar data to generate occupancy probabilities</li>

 <li>Apply logodds updates based on given Bresenham raytracing outputs</li>

 <li>Convert a logodds grid to a probabilistic occupancy grid</li>

</ul>




You are provided with lidar measurement data (Measurements.txt), as well as a Python 3 Jupyter Notebook which contains the required supplementary code (thanks to Paul Balzer). Your task is to complete each TODO section of the notebook in order to generate a probabilistic occupancy grid, as well as answer the given written questions.




<h1>Resources and Instructions</h1>




There are 3 TODO sections to complete in the given Jupyter notebook:




<ol>

 <li>Write code to convert lidar data in spherical coordinates to Cartesian coordinates in the function ibeo2XYZ().</li>

</ol>




<ol start="2">

 <li>Perform the logodds update for the `grid` global variable in insertPointcloudBRESENHAM(). Make sure to complete both TODOs in this section.</li>

</ol>




<ol start="3">

 <li>Convert the logodds grid to a probabilistic occupancy grid.</li>

</ol>




In addition, there are two written questions you must answer:




<ol>

 <li>What are the computational advantages of using logodds when generating our occupancy grid?</li>

</ol>




<ol start="2">

 <li>Is the angle phi in our Spherical to Cartesian calculation the same as the polar angle in standard Spherical coordinates? Why?</li>

</ol>




<h1>Deliverables</h1>




HTML output: In the Jupyter Notebook, go to File &gt; Download as &gt; HTML (.html).

In addition, include a PDF file of your answers to the two written questions. Submit a ZIP file containing the HTML output and the PDF file.




<strong>Run all code blocks before downloading the HTML. </strong>

<strong> </strong>

Please follow the naming convention for your zip file: a5_&lt;user_id&gt;.zip ​