# ee5934-project-2-solved
**TO GET THIS SOLUTION VISIT:** [EE5934  PROJECT#2 Solved](https://www.ankitcodinghub.com/product/ee5934-project2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;93460&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;EE5934&nbsp; PROJECT#2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

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
&nbsp;

In this project, you’re supposed to address a weakly-supervised segmentation task presented in a deep learning competition website, Kaggle (www.kaggle.com). The title of this competition is Human Protein Atlas – Single Cell Classification.

Target

The type and function of a cell is related to protein distribution in this cell. Hence, the target of the project#2 is to train a neural network which can segment cells in an image of proteins under the microscope with other images as references.

Data

Inputs of a sample are four microscope images corresponding to same cells. Four images are the protein of interest (green), nucleus (blue), microtubules (red), endoplasmic reticulum (yellow) respectively. Due to the target of this project which finds the mapping between protein distribution and kinds of cells, green images should be employed to predict labels while other images are considered as references. There are 19 different labels indicating types of cells (The labels 0-17 are different cells, the label 18 is for negative and unspecific cells)

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
As this is a weakly supervised learning task, although labels of a sample in the training set is image-level label which indicates what are kinds of cells in the sample, the target of the test set is to segment the cells in the images (lists of instance binary segmentation masks) and predict the labels of those segmented cells. Here is an example:

(a) nucleus(blue) (b) protein of interest(green)

(c) microtubules(red) (d) endoplasmic reticulum(yellow)

Fig 1. A sample of input images with the train label 16 | 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
(a) the mask filtering out cell 16 (b) the mask filtering out cell 2 Fig 2. Desired binary segmentation masks when test

Evaluation

For each image in the test set, you must predict a list of instance binary segmentation masks and their associated detection score (Confidence). To save the storage, each mask is required to be encoded to a string via the code in the Kaggle website-&gt; Overview-&gt;Evaluation.

Submission to Kaggle

You need to create a notebook in the Kaggle. You can train and test your model in this notebook. After testing, you only leave testing code in the notebook which generates a submission file named “submission.csv” whose format is same with the file “sample_submission.csv”. Lastly, click “submit predictions” to submit the notebook.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
For more information please refer to the Kaggle website: https://www.kaggle.com/c/hpa-single-cell-image- classification/overview

Kaggle provides free 30 Gpu hours and 30 Tpu hours per week.

Reference papers

“Learning Deep Features for Discriminative Localization” (CVPR 2016)

“Weakly Supervised Learning of Instance Segmentation with Inter-pixel Relations” (CVPR 2019)

These two papers may inspire you.

Project#2 submission: (Deadline: April 23)

1. Save you training code and test code into folders training and test respectively. Add the final parameters of your trained neural network into the test folder.

2. A report to explain details of your model, the training process and the testing performance. Also include analysis on the results and discussion on possible improvement on your model in your report.

3. Create a new folder containing training and test folder and your report. Compress the new folder into a zip file and rename it as: “Yourgroupid_Project2.zip”

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Evaluation criteria for the project 2:

<ol>
<li>Performance of your model.</li>
<li>The completeness and in-depth discussion of your submitted
report.
</li>
<li>The novelty of your designed model and method.</li>
<li>Submission on time.</li>
</ol>
</div>
</div>
</div>
