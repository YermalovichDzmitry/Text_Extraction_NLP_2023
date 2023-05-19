# Extracting text snippets
<p>My project is a solution to the problem of extracting the required piece of text that matches the query. My model works with Russian texts. The purpose of the study is to understand which approach to solving this problem is better than QA or NER.</p>
<p><h1>Introduction</h1></p></p>
Often, when working with documents, you have to extract: arbitration claims, public procurement, enforcement proceedings. This is required in order to complete the application form. But a person does not cope with this task quickly: he needs to read the text, analyze it, highlight the desired fragment of the text. These activities take time. Therefore, I developed a model that will help the public procurement department extract the right piece of text from the document in order to form the application form.
<p></p><h1>Guide</h1></p>
<p>1 The folder "Data" contains data on which the model was trained and test data</p>
<p>2 In the "Models" folder there is a link to the Google drive with the model weights</p>
<p>3 FinalProject_Yermalovich.ipynb is the final project</p>
<p>4 Report_English.docx - report</p>
<p>5 Model usage. The file Inference.ipynb provides code for using the model, that is, processing the input sequence, loading libraries. If you want to use my model you only need to change the paths to the weights of the model. Also in this notebook there is a "predict_answer" function, where you pass a list of strings and queries to them, and it generates an answer which is: the beginning of the extracted text in text, the end of the extracted text in text, the selected text.</p> 
