# Skin Type Analyzer

<!-- wp:paragraph -->
<p>Around age 17, like most teenage girls, I was dealing with pimples. It puzzled me because my skin had always been on the dry side before the breakouts began.With a little more research, I discovered that I had combination skin. This means some areas of my skin were oily, while other parts were dry. So, each area needed to be treated differently. Now the challenge is to identify which areas are oily and which areas are dry. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Fast forward to 2016, we have the power of AI. Here's how I use AI to solve the problem.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Principle</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>1. The human body releases heat. This heat has an infrared signature, which can be detected by infrared cameras. </p>
<!-- /wp:paragraph -->

<p align="center">
  <img width="" height="" src="https://i1.wp.com/live.staticflickr.com/65535/48599275822_9a84ea8f4a.jpg?resize=500%2C281&ssl=1">
</p>


<!-- wp:paragraph -->
<p>2.  The regions in the thermal image which have red, yellow and green are the warmer regions, with red being the hottest.  While, the regions which have light blue, dark blue, purple and black are the cooler regions, with black being the coldest.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>3. Combination skin is characterized by an oily forehead, nose, and chin and relatively dry cheeks. </p>
<!-- /wp:paragraph -->

<!-- wp:quote {"className":"is-style-default"} -->
<blockquote class="wp-block-quote is-style-default"><p>4. "Excessive production of subdermal fat, modifies the dynamics of the bloodstream, and consequently temperature. A high percentage of this heat interchange is manifested as electromagnetic radiation with far-infrared wavelengths, which can be captured through a thermal imaging camera. "</p><cite>https://www.ncbi.nlm.nih.gov/pubmed/24777529</cite></blockquote>
<!-- /wp:quote -->

<!-- wp:heading {"level":3} -->
<h3>Theory</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Based on the research paper, I deduced that the thermal signature of oily skin will be higher than that of the surrounding skin. This will help me detect oily patches of skin. </p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Methodology</h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li>Identify features of the face to detect the location of  oily skin.</li><li>Check for high temperatures which will be either red or orange according to the thermal image scale. </li><li>Return names of the regions of the face that are 'oily'.</li></ul>
<!-- /wp:list -->

<!-- wp:heading -->
<h2>Test</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>I do not have access to a thermal camera, so I had to simulate a thermal image using a thermal image effect. Then, I used the app to analyze it.</p>
<!-- /wp:paragraph -->


<!-- wp:heading {"level":4} -->
<h4>Output:</h4>
<!-- /wp:heading -->

<!-- wp:code -->
<pre class="wp-block-code"><code>Nose</code></pre>
<!-- /wp:code -->

The app has detected that the oiliest region on my face is the nose.

<!-- wp:heading {"level":3} -->
<h3>Dataset:</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>To learn more about the dataset, visit the link below:</p>
<!-- /wp:paragraph -->

https://www.kaggle.com/kpvisionlab/tufts-face-database-thermal-cropped

<!-- wp:heading {"level":3} -->
<h3>References:</h3>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>To view the research paper by Padilla-Medina JA, León-Ordoñez F, Prado-Olivarez J, Vela-Aguirre N, Ramírez-Agundis A and Díaz-Carmona J, click the button below:</p>
<!-- /wp:paragraph -->

https://www.ncbi.nlm.nih.gov/pubmed/24777529
