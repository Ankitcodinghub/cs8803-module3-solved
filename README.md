# cs8803-module3-solved
**TO GET THIS SOLUTION VISIT:** [CS8803 Module3 Solved](https://www.ankitcodinghub.com/product/cs8803-module3-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;62193&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS8803 Module3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
In this assignment, you’ll continue the process of exploring relationships in data. You’ll accomplish this task by computing some basic inferential statistical measures on a natural language-based dataset.

Natural language processing is concerned with the ability to process and analyze large amounts of natural language data, whether for automated sentence completion in emails, conversational agents and chatbots, or AI tools to help journalists. In this assignment, we will work with data from a classifier built to identify toxicity in comments from Wikipedia Talk Pages. The model is built from a dataset of 127,820 Talk Page comments, each labeled by human raters as toxic or non-toxic. A toxic comment is defined as a “rude, disrespectful, or unreasonable comment that is likely to make you leave a discussion.”

<strong>Step 1</strong> – <em>Download the modified dataset – toxity_per_attribute.csv</em>:

<ul>
<li>&lt;Wiki_ID&gt; is unique identifier associated with Wikipedia comment</li>
<li>&lt;TOXICITY&gt; is a toxicity value from 1 if the comment was considered toxic and value 0 if the comment was considered neutral or healthy</li>
<li>&lt; subgroup &gt; columns: One column per human attribute; True if the comment mentioned this identity.</li>
<li>Due to sensitivity, comments were removed to construct the modified dataset. The original data source can be found at: <u>https://github.com/conversationai/unintended-ml-biasanalysis/tree/master/data</u></li>
</ul>
&nbsp;

<strong>Step 2:</strong> – Identify the protected class categories and assign numerical values for each member associated with each protected class category by:

<ul>
<li>Combining values from the related subgroups into the relevant protected class category (e.g. christian + muslim + X -&gt; Religion)</li>
<li>To define values for each protected class member, convert FALSE to 0 and TRUE to a unique numerical value for each subgroup member (e.g. for gender identify: FALSE = 0; female = 1; binary = 2; etc.)</li>
<li>Provide the classification results (i.e. list of protected class categories and their associated protected class members)</li>
</ul>
<strong>Step 3: </strong>

<ul>
<li>Create a reduced data set by blending columns related to the protected class categories and deleting any rows that have all FALSE values for every column in that row</li>
<li>Calculate the correlation between the protected class category and TOXICITY. Provide the correlation coefficients in table format and identify the strength of the correlation. Select the three highest correlation coefficients and plot data for the correlated variables; indicate its correlation strength [Note: there may/may not be any strong correlations in this dataset].</li>
<li>As guidance, can use (Evans, J. D. (1996). Straightforward statistics for the behavioral sciences. Brooks/Cole Publishing) which suggests the following related to the absolute value of the correlation coefficient:
<ul>
<li>.00-.19 “very weak” correlation o .20-.39 “weak” correlation o .40-.59 “moderate” correlation o .60-.79 “strong” correlation</li>
<li>.80-1.0 “very strong” correlation</li>
</ul>
</li>
</ul>
&nbsp;

<strong><em>Example Output: </em></strong>

&nbsp;

Classification Results – Protected Class Variables:

<ul>
<li>Religion: christian, muslim</li>
<li>Age: younger, older</li>
</ul>
&nbsp;

Correlation Coefficients:

<table width="563">
<tbody>
<tr>
<td width="132">&nbsp;</td>
<td width="227">Religion (Protected Class Variable)</td>
<td width="204">Age (Protected Class Variable)</td>
</tr>
<tr>
<td width="132">TOXICITY</td>
<td width="227">0.03</td>
<td width="204">0.7</td>
</tr>
<tr>
<td width="132">CORRELATION STRENGTH</td>
<td width="227">Very weak correlation</td>
<td width="204">Strong correlation</td>
</tr>
</tbody>
</table>
&nbsp;

TOXICITY and Age are strongly correlated.

&nbsp;

<strong>&nbsp;</strong>

<strong>&nbsp;</strong>

<strong>Step 4:</strong> Calculate the population mean and population standard deviation of TOXICITY. What is the range of values around the mean that includes 95% of TOXICITY? Run the random sampling method using 25% and 50% of the data. For each, what is the mean, standard deviation, and margin of error?

&nbsp;

<em>For these questions, choose only one of the protected class categories. </em>

&nbsp;

<strong>Step 5:</strong> Calculate the mean and standard deviation of TOXICITY associated with the protected class category (<strong><em>Hint:</em></strong> TOXICITY values should only be included in the calculation when the associated protected class value is not FALSE). Run the random sampling method using 25% and 50% of the data. For each, what is the mean and standard deviation? Indicate (yes/no) if the values lie within the associated population margin of error.

&nbsp;

<strong>Step 6:</strong> Calculate the mean and standard deviation of TOXICITY associated with each subgroup that is a member of the protected class category (<strong><em>Hint:</em></strong> TOXICITY values should only be included in the calculation when the associated protected class value is not FALSE). Run the random sampling method using 25% and 50% of the data. For each subgroup, what is the mean and standard deviation? Indicate (yes/no) if the values lie within the associated population margin of error.

&nbsp;

<strong>Step 7: </strong>Plot (on one graph) – 1) the computed population mean/standard deviation (Step 4), (2) the computed mean/standard deviation for the protected class category (Step 5), and (3) the computed mean/standard deviation for each subgroup of the protected class category (Step 6). Which of the subgroups has the highest TOXICITY value? Which of the subgroups has the lowest TOXICITY value? Which of the subgroups has the largest difference in TOXICITY value when compared to the population mean? Does there seem to be any human bias in the data? Explain (in no more than 3-5 sentences).

&nbsp;

<strong>Step 8:</strong> Turn in a report documenting your outputs.

&nbsp;
