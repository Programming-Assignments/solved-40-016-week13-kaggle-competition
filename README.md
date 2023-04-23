Download Link: https://assignmentchef.com/product/solved-40-016-week13-kaggle-competition
<br>
Participatory monitoring is a novel form of data collection based on observations gathered by local residents. Such data collection process can rely on a variety of tools, ranging from amateur equipment to social media (e.g., Twitter, Facebook), on which people post comments and observations concerning various environmental and socio-economic processes. Participatory monitoring is quickly permeating multiple scientific domains as an alternative, or addition, to professional scientist-executed monitoring. During a flooding event, for example, agencies, utilities, and service providers could rely on both radar data and tweets to pinpoint the most affected areas. Are tweets reliable? How can one extract useful information from tweets? This is where data analytics can give us an edge.

In this project, you are tasked with the problem of inferring automatically the information contained in a large amount of tweets concerning the state of the weather. Specifically, your task is to develop an algorithm that determines—with the highest accuracy—what sort of weather the tweets reference. <strong>The analysis must be carried out in the R computing environment. You can use any R package.</strong>

<h1>2          Schedule</h1>

The schedule of events for this data competition is outlined in Table 1.

<table width="467">

 <tbody>

  <tr>

   <td width="133">December 3, 2020</td>

   <td width="334">Announcement of the Data Competition</td>

  </tr>

  <tr>

   <td width="133">December 3, 2020</td>

   <td width="334">Publication of problem details and competition rules</td>

  </tr>

  <tr>

   <td width="133">(17.00)</td>

   <td width="334">+ Release of the training dataset+ Release of the test dataset</td>

  </tr>

  <tr>

   <td width="133">December 11, 2020</td>

   <td width="334">Last opportunity for submitting the results on Kaggle</td>

  </tr>

  <tr>

   <td width="133">(23.59)December 13, 2020(23.59)</td>

   <td width="334">Submission of reports, code, and peer evaluation form</td>

  </tr>

 </tbody>

</table>

Table 1: Schedule of events.

Other info about the data competition will be published on Kaggle, which will act as a portal for downloading the data and uploading the predictions for the test dataset. Reports, code, and peer evaluation form should be submitted on eDimension through a dedicated link.

1

<h1>3          Problem description</h1>

As mentioned in Section 1, your task is to develop an algorithm that determines what sort of weather the tweets reference. Specifically, the challenge is to determine whether a tweet has a negative, neutral, or positive sentiment. The following datasets are provided:

<ul>

 <li><em>csv</em>: 22,500 tweets with the corresponding classification / sentiment. The integers 1, 2, and 3 indicate negative, neutral, and positive sentiment, respectively.</li>

 <li><em>csv</em>: 7,500 tweets. Naturally, this dataset has no labels. It will be used to quantify the performance of the algorithms.</li>

</ul>

The performance of the algorithms will be then evaluated based on their capability of classifying correctly the sentiment of each tweet in the test dataset. In particular, the evaluation will be based on the <strong>accuracy metric</strong>, defined as the ratio between the number of correctly-classified samples and the total number of samples. Kaggle will calculate the value of the accuracy on two subsets of the test dataset, named <em>public </em>and <em>private</em>. The results on the public dataset will be available during the competition (<em>public leaderboard</em>), while the results on the private one will be available at the end of the competition (<em>private leaderboard</em>).


