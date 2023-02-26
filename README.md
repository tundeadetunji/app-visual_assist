# Visual Assist

<li>Requirements</li>
<li>Technical</li>
<li>Currently</li>
<br>
<br>
<h3>Requirements</h3>
<hr>

<h4>SCENARIO</h4>
As a user, I want to identify the content of the picture I snap from my phone.
<h4>DEPENDENCIES</h4>
Internet Connection.
<br/>
Azure Cognitive Service.
<br/>
<h4>ASSUMPTIONS</h4>
I can access the service at any time from my phone.
<br/>
<h4>EXAMPLES</h4>
<strong>1</strong>
<br/>
<strong>Given </strong>My phone is connected to the service
<br/>
<strong>When </strong>I snap a picture
<br/>
<strong>Then </strong>The app tells me verbally what is in the picture and how certain the claim is.

<br/>
<br/>
<br>
<h3>Technical</h3>
<hr>
Connect Web/Android interface to Azure Cognitive Services, to get picture/video data and provide feedback in real time on what the picture/video frame contain.
<br/>


