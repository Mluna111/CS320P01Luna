<h1>Timing Loops for Asymptotic Analysiis</h1>


<h2>Description</h2>
This code tests one loop at a time. The user chooses the loop to test. Then, chooses the
set of Ns , number of times to loop, used to show the asymptotic growth. Each N in the set of Ns are timed a MaxNumTrails,
a number of trials. These times will be averaged giving a timing value for each N and writen to a file and standard output.
<br />


<h2>Languages and Utilities Used</h2>
<ul>
  <li><b>C++</b></li>
  <li><b><code>&lt;iostream&gt;</code></b> - For input and output operations</li>
  <li><b><code>&lt;fstream&gt;</code></b> - For file operations</li>
  <li><b><code>&lt;iomanip&gt;</code></b> - For setting the precision of floating-point output</li>
  <li><b><code>&lt;chrono&gt;</code></b> - For measuring execution time</li>
  <li><b><code>&lt;cstdlib&gt;</code></b> - For using the <code>exit</code> function</li>
</ul>


<h2>Environments Used</h2>
<ul>
  <li><b>Windows 10 (21H2)</b></li>
</ul>

<h2>How to Run</h2>
<ol>
  <li><b>Compile the Program:</b>
    <pre><code>g++ -o CS320Luna Source.cpp</code></pre>
  </li>
  <li><b>Execute the Program:</b>
    <pre><code>./CS320Luna</code></pre>
  </li>
  <li><b>Follow the prompts</b> to select the loop fragment and the set of input sizes to use for timing.</li>
</ol>


<h2>Output</h2>
<p>
The program outputs the timing results to a file named <code>runTimesX.txt</code>, where <code>X</code> is the loop fragment index.
</p>

<h2>Program walk-through:</h2>
<p align="center">
<b>Prompted to enter number of loop fragment & set of Ns: </b>
<br/>
<br/>
<img src="https://imgur.com/HnNGQiG.png" height="80%" width="80%" />
<br />
<br />
<b>Trials: </b>
<br/>
<br/>
<img src="https://imgur.com/5PC58qw.png" height="80%" width="80%" />
<br />
<br />
<b>Average time for each N: </b>
<br/>
<br/>
<img src="https://imgur.com/2rXdFDm.png" height="80%" width="80%" />
</p>
