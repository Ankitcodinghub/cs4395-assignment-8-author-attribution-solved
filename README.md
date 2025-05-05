# cs4395-assignment-8-author-attribution-solved
**TO GET THIS SOLUTION VISIT:** [CS4395 Assignment 8-Author Attribution Solved](https://www.ankitcodinghub.com/product/cs4395-assignment-7-author-attribution-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101551&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS4395 Assignment 8-Author Attribution Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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

<div class="kksr-stars-active" style="width: 0px;">
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
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Author Attribution

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>Gain experience with machine learning using sklearn</li>
<li>Experiment with the NLP task author attributionTurn in:</li>
</ul>
<ul>
<li>Use Google Colab or a local Jupyter notebook</li>
<li>File -&gt; Print to pdf, turn in the pdf to eLearning and upload it to your portfolioBackground:
The Federalist Papers is a collection of documents written by Alexander Hamilton, James Madison, and John Jay collectively under the pseudonym Publius. These documents were written to persuade voters to ratify the US Constitution. These documents continue to be influential to this day, as they are frequently cited in Federal court rulings, as well as law blogs, and political opinions.

Overview:

The data set used in this assignment is a collection of Federalist Papers from Project Gutenberg. There are 83 documents in this data set which has two columns: one for the author(s), and one for the text of the document.

The NLP task of authorship attribution is the attempt to identify the author of a document, given samples of authors’ work. In this data set, the breakdown by author is as follows:
</li>
</ul>
<ul>
<li>Alexander Hamilton 49</li>
<li>James Madison 15</li>
<li>John Jay 5There are several documents for which authorship is in dispute by historians:</li>
<li>Hamilton or Madison 11</li>
<li>Hamilton and Madison 3Caution: All course work is run through plagiarism detection software comparing students’ work as well as work from previous semesters and other sources.</li>
</ul>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea"></div>
<div class="layoutArea">
<div class="column">
Instructions:

<ol>
<li>Read in the csv file using pandas. Convert the author column to categorical data. Display the first few rows. Display the counts by author.</li>
<li>Divide into train and test, with 80% in train. Use random state 1234. Display the shape of train and test.</li>
<li>Process the text by removing stop words and performing tf-idf vectorization, fit to the training data only, and applied to train and test. Output the training set shape and the test set shape.</li>
<li>Try a Bernoulli Naïve Bayes model. What is your accuracy on the test set?</li>
<li>The results from step 4 will be disappointing. The classifier just guessed the predominant class,Hamilton, every time. Looking at the train data shape above, there are 7876 unique words in the vocabulary. This may be too much, and many of those words may not be helpful. Redo the vectorization with max_features option set to use only the 1000 most frequent words. In addition to the words, add bigrams as a feature. Try Naïve Bayes again on the new train/test vectors and compare your results.</li>
<li>Try logistic regression. Adjust at least one parameter in the LogisticRegression() model to see if you can improve results over having no parameters. What are your results?</li>
<li>Try a neural network. Try different topologies until you get good results. What is your final accuracy?</li>
</ol>
</div>
</div>
</div>
