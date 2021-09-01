![object detection with TF.js in Twilio Video](bbox.gif)
<ol>
<li>Make a Twilio video application ie <a href = "https://www.twilio.com/blog/build-a-video-app-javascript-twilio-cli-quickly" target="_blank">this one in 9 minutes</a>, including the <a href="https://www.twilio.com/docs/labs/serverless-toolkit" target="_blank">Twilio Serverless Toolkit</a> installed.</li>

<li>All the <a href = "https://www.tensorflow.org/js" target="_blank">tensorflow.js</a>code is in <em>assets/index.js</em>.</li>

<li>To run the app, go into the root directory and run `twilio serverless:deploy` and grab the URL ending in `video.html`. Open it in a web browser, click <em>Join Room</em>, and start detecting objects in a Twilio Video room using TensorFlow.js!
</ol>
