# AWS-AI-Practitioner-Study-Test
This is an AWS Certified AI Practitioner Challenge by Quad_ree

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AWS Certified AI Practitioner Quiz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 20px;
            max-width: 800px;
            margin: 0 auto;
        }
        .question {
            margin-bottom: 30px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background-color: #f9f9f9;
        }
        .question-number {
            font-weight: bold;
            margin-bottom: 10px;
        }
        .options {
            margin-left: 20px;
        }
        .option {
            margin-bottom: 10px;
        }
        .explanation {
            margin-top: 15px;
            padding: 10px;
            background-color: #e6f7ff;
            border-left: 4px solid #1890ff;
            display: none;
        }
        button {
            background-color: #1890ff;
            color: white;
            border: none;
            padding: 8px 15px;
            border-radius: 4px;
            cursor: pointer;
            margin-top: 10px;
        }
        button:hover {
            background-color: #40a9ff;
        }
        .correct {
            color: green;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <h1>AWS Certified AI Practitioner Challenge by Quad_ree😊✅  </h1>

 <!-- Question 1 -->
    <div class="question">
        <div class="question-number">Question #1</div>
        <div class="question-text">
            A company has built a chatbot that can respond to natural language questions with images. The company wants to ensure that the chatbot does not return inappropriate or unwanted images.
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q1" id="q1a" value="A">
                <label for="q1a">A. Implement moderation APIs.</label>
            </div>
            <div class="option">
                <input type="radio" name="q1" id="q1b" value="B">
                <label for="q1b">B. Retrain the model with a general public dataset.</label>
            </div>
            <div class="option">
                <input type="radio" name="q1" id="q1c" value="C">
                <label for="q1c">C. Perform model validation.</label>
            </div>
            <div class="option">
                <input type="radio" name="q1" id="q1d" value="D">
                <label for="q1d">D. Automate user feedback integration.</label>
            </div>
        </div>
        <button onclick="showAnswer(1)">Show Answer</button>
        <div class="explanation" id="explanation1">
            <span class="correct">Correct Answer: A. Implement moderation APIs.</span>
            <p>Explanation: To prevent inappropriate or unwanted images from being returned, moderation APIs are commonly used. These APIs can analyze and filter content based on defined criteria for appropriateness, identifying any explicit, violent, or otherwise undesired content. This provides a proactive, automated approach to content moderation, making it a practical solution for ensuring content safety in real-time interactions.</p>
            <p><strong>Explanation of Other Options:</strong></p>
            <ul>
                <li><strong>B. Retrain the model with a general public dataset</strong>: Retraining on a general dataset doesn't specifically address moderation. While it may help improve general responses, it won't reliably prevent inappropriate content.</li>
                <li><strong>C. Perform model validation</strong>: Model validation is necessary to ensure general performance and accuracy but does not inherently include image moderation.</li>
                <li><strong>D. Automate user feedback integration</strong>: Automating feedback may help improve the system gradually but is a slower process and does not prevent unwanted images in real-time.</li>
            </ul>
        </div>
    </div>

    <hr>

    <!-- Question 2 -->
    <div class="question">
        <div class="question-number">Question #2</div>
        <div class="question-text">
            An accounting firm wants to implement a large language model (LLM) to automate document processing. The firm must proceed responsibly to avoid potential harms. What should the firm do when developing and deploying the LLM? (Select TWO.)
        </div>
        <div class="options">
            <div class="option">
                <input type="checkbox" name="q2" id="q2a" value="A">
                <label for="q2a">A. Include fairness metrics for model evaluation.</label>
            </div>
            <div class="option">
                <input type="checkbox" name="q2" id="q2b" value="B">
                <label for="q2b">B. Adjust the temperature parameter of the model.</label>
            </div>
            <div class="option">
                <input type="checkbox" name="q2" id="q2c" value="C">
                <label for="q2c">C. Modify the training data to mitigate bias.</label>
            </div>
            <div class="option">
                <input type="checkbox" name="q2" id="q2d" value="D">
                <label for="q2d">D. Avoid overfitting on the training data.</label>
            </div>
            <div class="option">
                <input type="checkbox" name="q2" id="q2e" value="E">
                <label for="q2e">E. Apply prompt engineering techniques.</label>
            </div>
        </div>
        <button onclick="showAnswer(2)">Show Answer</button>
        <div class="explanation" id="explanation2">
            <span class="correct">Correct Answers: A. Include fairness metrics for model evaluation and C. Modify the training data to mitigate bias.</span>
            <p>Explanation: To responsibly develop and deploy an LLM for document processing, it's essential to address ethical considerations like fairness and bias:</p>
            <ul>
                <li><strong>A. Include fairness metrics for model evaluation</strong>: Incorporating fairness metrics ensures that the model is evaluated for equitable performance across different demographic or user groups. This helps in identifying and addressing biases that could lead to unfair outcomes.</li>
                <li><strong>C. Modify the training data to mitigate bias</strong>: Bias in the training data can lead to biased outputs, which could be problematic in sensitive applications like accounting. Adjusting the training data to reduce or eliminate bias is a key step in building a responsible and fair LLM.</li>
            </ul>
            <p><strong>Explanation of Other Options:</strong></p>
            <ul>
                <li><strong>B. Adjust the temperature parameter of the model</strong>: This parameter controls randomness in generation but does not directly impact fairness, bias, or responsible deployment.</li>
                <li><strong>D. Avoid overfitting on the training data</strong>: Avoiding overfitting is essential for model performance but doesn't specifically address ethical concerns like fairness or bias.</li>
                <li><strong>E. Apply prompt engineering techniques</strong>: Prompt engineering can improve model responses but does not address fairness or bias, which are critical for responsible deployment.</li>
            </ul>
        </div>
    </div>

    <hr>

    <!-- Question 3 -->
    <div class="question">
        <div class="question-number">Question #3</div>
        <div class="question-text">
            A company has thousands of customer support interactions per day and wants to analyze these interactions to identify frequently asked questions and develop insights. Which AWS service can the company use to meet this requirement?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q3" id="q3a" value="A">
                <label for="q3a">A. Amazon Lex</label>
            </div>
            <div class="option">
                <input type="radio" name="q3" id="q3b" value="B">
                <label for="q3b">B. Amazon Comprehend</label>
            </div>
            <div class="option">
                <input type="radio" name="q3" id="q3c" value="C">
                <label for="q3c">C. Amazon Transcribe</label>
            </div>
            <div class="option">
                <input type="radio" name="q3" id="q3d" value="D">
                <label for="q3d">D. Amazon Translate</label>
            </div>
        </div>
        <button onclick="showAnswer(3)">Show Answer</button>
        <div class="explanation" id="explanation3">
            <span class="correct">Correct Answer: B. Amazon Comprehend</span>
            <p>Explanation: <strong>Amazon Comprehend</strong> is a natural language processing (NLP) service that can analyze text to extract insights such as frequently asked questions, customer sentiment, and key topics. This makes it ideal for analyzing large volumes of customer interactions.</p>
        </div>
    </div>

    <hr>

    <!-- Question 4 -->
    <div class="question">
        <div class="question-number">Question #4</div>
        <div class="question-text">
            A company has a database of petabytes of unstructured data from internal sources. The company wants to transform this data into a structured format so that its data scientists can perform machine learning (ML) tasks. Which service will meet these requirements?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q4" id="q4a" value="A">
                <label for="q4a">A. Amazon Lex</label>
            </div>
            <div class="option">
                <input type="radio" name="q4" id="q4b" value="B">
                <label for="q4b">B. Amazon Rekognition</label>
            </div>
            <div class="option">
                <input type="radio" name="q4" id="q4c" value="C">
                <label for="q4c">C. Amazon Kinesis Data Streams</label>
            </div>
            <div class="option">
                <input type="radio" name="q4" id="q4d" value="D">
                <label for="q4d">D. AWS Glue</label>
            </div>
        </div>
        <button onclick="showAnswer(4)">Show Answer</button>
        <div class="explanation" id="explanation4">
            <span class="correct">Correct Answer: D. AWS Glue</span>
            <p>Explanation: <strong>AWS Glue</strong> is an ETL (Extract, Transform, Load) service designed to transform and catalog large amounts of unstructured data into a structured format. This is ideal for data scientists who need structured data for ML tasks.</p>
        </div>
    </div>

    <hr>

    <!-- Question 5 -->
    <div class="question">
        <div class="question-number">Question #5</div>
        <div class="question-text">
            Which AWS service or feature can help an AI development team quickly deploy and consume a foundation model (FM) within the team's VPC?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q5" id="q5a" value="A">
                <label for="q5a">A. Amazon Personalize</label>
            </div>
            <div class="option">
                <input type="radio" name="q5" id="q5b" value="B">
                <label for="q5b">B. Amazon SageMaker JumpStart</label>
            </div>
            <div class="option">
                <input type="radio" name="q5" id="q5c" value="C">
                <label for="q5c">C. PartyRock, an Amazon Bedrock Playground</label>
            </div>
            <div class="option">
                <input type="radio" name="q5" id="q5d" value="D">
                <label for="q5d">D. Amazon SageMaker endpoints</label>
            </div>
        </div>
        <button onclick="showAnswer(5)">Show Answer</button>
        <div class="explanation" id="explanation5">
            <span class="correct">Correct Answer: B. Amazon SageMaker JumpStart</span>
            <p>Explanation: <strong>Amazon SageMaker JumpStart</strong> offers pre-trained models, including foundation models, which can be easily deployed and used within a VPC. This service is specifically designed to help teams quickly access, deploy, and integrate ML models.</p>
        </div>
    </div>

    <hr>

    <!-- Question 6 -->
    <div class="question">
        <div class="question-number">Question #6</div>
        <div class="question-text">
            A company wants to use a large language model (LLM) on Amazon Bedrock for sentiment analysis. The company wants to classify the sentiment of text passages as positive or negative. Which prompt engineering strategy meets these requirements?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q6" id="q6a" value="A">
                <label for="q6a">A. Provide examples of text passages with corresponding positive or negative labels in the prompt followed by the new text passage to be classified.</label>
            </div>
            <div class="option">
                <input type="radio" name="q6" id="q6b" value="B">
                <label for="q6b">B. Provide a detailed explanation of sentiment analysis and how LLMs work in the prompt.</label>
            </div>
            <div class="option">
                <input type="radio" name="q6" id="q6c" value="C">
                <label for="q6c">C. Provide the new text passage to be classified without any additional context or examples.</label>
            </div>
            <div class="option">
                <input type="radio" name="q6" id="q6d" value="D">
                <label for="q6d">D. Provide the new text passage with a few examples of unrelated tasks, such as text summarization or question answering.</label>
            </div>
        </div>
        <button onclick="showAnswer(6)">Show Answer</button>
        <div class="explanation" id="explanation6">
            <span class="correct">Correct Answer: A. Provide examples of text passages with corresponding positive or negative labels in the prompt followed by the new text passage to be classified.</span>
            <p>Explanation: Including labeled examples in the prompt gives the LLM context for how to classify sentiment, improving its accuracy in recognizing positive or negative sentiment in new text passages.</p>
        </div>
    </div>

    <hr>


 <!-- Question 7 -->
    <div class="question">
        <div class="question-number">Question #7</div>
        <div class="question-text">
            A company wants to develop a large language model (LLM) application by using Amazon Bedrock and customer data that is uploaded to Amazon S3. The company's security policy states that each team can access data for only the team's own customers.
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q7" id="q7a" value="A">
                <label for="q7a">A. Create an Amazon Bedrock custom service role for each team that has access to only the team's customer data.</label>
            </div>
            <div class="option">
                <input type="radio" name="q7" id="q7b" value="B">
                <label for="q7b">B. Create a custom service role that has Amazon S3 access. Ask teams to specify the customer name on each Amazon Bedrock request.</label>
            </div>
            <div class="option">
                <input type="radio" name="q7" id="q7c" value="C">
                <label for="q7c">C. Redact personal data in Amazon S3. Update the S3 bucket policy to allow team access to customer data.</label>
            </div>
            <div class="option">
                <input type="radio" name="q7" id="q7d" value="D">
                <label for="q7d">D. Create one Amazon Bedrock role that has full Amazon S3 access. Create IAM roles for each team that have access to only each team's customer folders.</label>
            </div>
        </div>
        <button onclick="showAnswer(7)">Show Answer</button>
        <div class="explanation" id="explanation7">
            <span class="correct">Correct Answer: A. Create an Amazon Bedrock custom service role for each team that has access to only the team's customer data.</span>
            <p>Explanation: Using Amazon Bedrock custom service roles that limit each team's access to their specific customer data aligns with security policies and ensures that data segregation and compliance are maintained.</p>
        </div>
    </div>

    <!-- Question 8 -->
    <div class="question">
        <div class="question-number">Question #8</div>
        <div class="question-text">
            A company has built an image classification model to predict plant diseases from photos of plant leaves. The company wants to evaluate how many images the model classified correctly.
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q8" id="q8a" value="A">
                <label for="q8a">A. R-squared score</label>
            </div>
            <div class="option">
                <input type="radio" name="q8" id="q8b" value="B">
                <label for="q8b">B. Accuracy</label>
            </div>
            <div class="option">
                <input type="radio" name="q8" id="q8c" value="C">
                <label for="q8c">C. Root mean squared error (RMSE)</label>
            </div>
            <div class="option">
                <input type="radio" name="q8" id="q8d" value="D">
                <label for="q8d">D. Learning rate</label>
            </div>
        </div>
        <button onclick="showAnswer(8)">Show Answer</button>
        <div class="explanation" id="explanation8">
            <span class="correct">Correct Answer: B. Accuracy</span>
            <p>Explanation: Accuracy is the appropriate metric for evaluating how many images the model classified correctly out of the total number of images. It provides a straightforward measure of the model's overall correctness in a classification task.</p>
        </div>
    </div>

    <!-- Question 9 -->
    <div class="question">
        <div class="question-number">Question #9</div>
        <div class="question-text">
            A company wants to make a chatbot to help customers. The chatbot will help solve technical problems without human intervention. The company chose a foundation model (FM) for the chatbot. The chatbot needs to produce responses that adhere to company tone.
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q9" id="q9a" value="A">
                <label for="q9a">A. Set a low limit on the number of tokens the FM can produce.</label>
            </div>
            <div class="option">
                <input type="radio" name="q9" id="q9b" value="B">
                <label for="q9b">B. Use batch inferencing to process detailed responses.</label>
            </div>
            <div class="option">
                <input type="radio" name="q9" id="q9c" value="C">
                <label for="q9c">C. Experiment and refine the prompt until the FM produces the desired responses.</label>
            </div>
            <div class="option">
                <input type="radio" name="q9" id="q9d" value="D">
                <label for="q9d">D. Define a higher number for the temperature parameter.</label>
            </div>
        </div>
        <button onclick="showAnswer(9)">Show Answer</button>
        <div class="explanation" id="explanation9">
            <span class="correct">Correct Answer: C. Experiment and refine the prompt until the FM produces the desired responses.</span>
            <p>Explanation: To produce responses that match the company tone, prompt engineering is essential. By experimenting and refining the prompt, the company can guide the FM to generate responses that align with their specific requirements for tone and style.</p>
        </div>
    </div>

    <!-- Question 10 -->
    <div class="question">
        <div class="question-number">Question #10</div>
        <div class="question-text">
            A company has installed a security camera. The company uses an ML model to evaluate the security camera footage for potential thefts. The company has discovered that the model disproportionately flags people who are members of a specific ethnic group.
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q10" id="q10a" value="A">
                <label for="q10a">A. Measurement bias</label>
            </div>
            <div class="option">
                <input type="radio" name="q10" id="q10b" value="B">
                <label for="q10b">B. Sampling bias</label>
            </div>
            <div class="option">
                <input type="radio" name="q10" id="q10c" value="C">
                <label for="q10c">C. Observer bias</label>
            </div>
            <div class="option">
                <input type="radio" name="q10" id="q10d" value="D">
                <label for="q10d">D. Confirmation bias</label>
            </div>
        </div>
        <button onclick="showAnswer(10)">Show Answer</button>
        <div class="explanation" id="explanation10">
            <span class="correct">Correct Answer: B. Sampling bias</span>
            <p>Explanation: Sampling bias occurs when the training data used is not representative of the broader population, which can lead to a model that unfairly targets specific groups. In this case, if the model disproportionately flags a specific ethnic group, the likely cause is a bias in the training sample data.</p>
        </div>
    </div>

    <!-- Question 11 -->
    <div class="question">
        <div class="question-number">Question #11</div>
        <div class="question-text">
            What is the primary difference between AI and ML?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q11" id="q11a" value="A">
                <label for="q11a">A) AI is a subset of ML</label>
            </div>
            <div class="option">
                <input type="radio" name="q11" id="q11b" value="B">
                <label for="q11b">B) ML is a subset of AI</label>
            </div>
            <div class="option">
                <input type="radio" name="q11" id="q11c" value="C">
                <label for="q11c">C) They are completely unrelated fields</label>
            </div>
            <div class="option">
                <input type="radio" name="q11" id="q11d" value="D">
                <label for="q11d">D) AI and ML are the same thing</label>
            </div>
        </div>
        <button onclick="showAnswer(11)">Show Answer</button>
        <div class="explanation" id="explanation11">
            <span class="correct">Correct Answer: B) ML is a subset of AI</span>
            <p>Explanation: ML is a subset of AI. Understanding the distinctions between AI, ML, and deep learning is fundamental to the field (Task Statement 1.1).</p>
        </div>
    </div>

    <!-- Question 12 -->
    <div class="question">
        <div class="question-number">Question #12</div>
        <div class="question-text">
            Which of the following is NOT a type of machine learning?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q12" id="q12a" value="A">
                <label for="q12a">A) Supervised learning</label>
            </div>
            <div class="option">
                <input type="radio" name="q12" id="q12b" value="B">
                <label for="q12b">B) Unsupervised learning</label>
            </div>
            <div class="option">
                <input type="radio" name="q12" id="q12c" value="C">
                <label for="q12c">C) Reinforcement learning</label>
            </div>
            <div class="option">
                <input type="radio" name="q12" id="q12d" value="D">
                <label for="q12d">D) Diagnostic learning</label>
            </div>
        </div>
        <button onclick="showAnswer(12)">Show Answer</button>
        <div class="explanation" id="explanation12">
            <span class="correct">Correct Answer: D) Diagnostic learning</span>
            <p>Explanation: Diagnostic learning is not a recognized category of machine learning. Typical types include supervised, unsupervised, and reinforcement learning (Task Statement 1.1).</p>
        </div>
    </div>

    <!-- Question 13 -->
    <div class="question">
        <div class="question-number">Question #13</div>
        <div class="question-text">
            What type of data is most suitable for training a computer vision model?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q13" id="q13a" value="A">
                <label for="q13a">A) Tabular data</label>
            </div>
            <div class="option">
                <input type="radio" name="q13" id="q13b" value="B">
                <label for="q13b">B) Time-series data</label>
            </div>
            <div class="option">
                <input type="radio" name="q13" id="q13c" value="C">
                <label for="q13c">C) Image data</label>
            </div>
            <div class="option">
                <input type="radio" name="q13" id="q13d" value="D">
                <label for="q13d">D) Text data</label>
            </div>
        </div>
        <button onclick="showAnswer(13)">Show Answer</button>
        <div class="explanation" id="explanation13">
            <span class="correct">Correct Answer: C) Image data</span>
            <p>Explanation: Computer vision models are designed to work with image data (Task Statement 1.1).</p>
        </div>
    </div>

    <!-- Question 14 -->
    <div class="question">
        <div class="question-number">Question #14</div>
        <div class="question-text">
            Which AWS service is best suited for natural language processing tasks?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q14" id="q14a" value="A">
                <label for="q14a">A) Amazon SageMaker</label>
            </div>
            <div class="option">
                <input type="radio" name="q14" id="q14b" value="B">
                <label for="q14b">B) Amazon Comprehend</label>
            </div>
            <div class="option">
                <input type="radio" name="q14" id="q14c" value="C">
                <label for="q14c">C) Amazon Polly</label>
            </div>
            <div class="option">
                <input type="radio" name="q14" id="q14d" value="D">
                <label for="q14d">D) Amazon Transcribe</label>
            </div>
        </div>
        <button onclick="showAnswer(14)">Show Answer</button>
        <div class="explanation" id="explanation14">
            <span class="correct">Correct Answer: B) Amazon Comprehend</span>
            <p>Explanation: Amazon Comprehend is specifically for NLP tasks, supporting analysis of language-based data (Task Statement 1.2).</p>
        </div>
    </div>

    <!-- Question 15 -->
    <div class="question">
        <div class="question-number">Question #15</div>
        <div class="question-text">
            What is the primary purpose of exploratory data analysis (EDA) in the ML development lifecycle?
        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q15" id="q15a" value="A">
                <label for="q15a">A) To train the model</label>
            </div>
            <div class="option">
                <input type="radio" name="q15" id="q15b" value="B">
                <label for="q15b">B) To deploy the model</label>
            </div>
            <div class="option">
                <input type="radio" name="q15" id="q15c" value="C">
                <label for="q15c">C) To understand the characteristics of the data</label>
            </div>
            <div class="option">
                <input type="radio" name="q15" id="q15d" value="D">
                <label for="q15d">D) To monitor the model in production</label>
            </div>
        </div>
        <button onclick="showAnswer(15)">Show Answer</button>
        <div class="explanation" id="explanation15">
            <span class="correct">Correct Answer: C) To understand the characteristics of the data</span>
            <p>Explanation: EDA helps in understanding the data's characteristics, a crucial step before model training (Task Statement 1.3).</p>
        </div>
    </div>

    <script>
        function showAnswer(questionNumber) {
            const explanation = document.getElementById(`explanation${questionNumber}`);
            if (explanation.style.display === "block") {
                explanation.style.display = "none";
            } else {
                explanation.style.display = "block";
            }
        }
    </script>
</body>
</html>



 <!-- Question 16 -->
    <div class="question">
        <div class="question-number">Question #16</div>
        <div class="question-text">
            An organization is developing a model to predict the price of a product based on various features like size, weight, brand, and manufacturing date. Which machine learning approach would be best suited for this task?

        </div>
        <div class="options">
            <div class="option">
                <input type="radio" name="q16" id="q16a" value="A">
                <label for="q15a">A) Classification</label>
            </div>
            <div class="option">
                <input type="radio" name="q16" id="q16b" value="B">
                <label for="q15b">B) Regression</label>
            </div>
            <div class="option">
                <input type="radio" name="q16" id="q16c" value="C">
                <label for="q15c">C) Clustering</label>
            </div>
            <div class="option">
                <input type="radio" name="q16" id="q16d" value="D">
                <label for="q15d">D) Dimensionality Reduction</label>
            </div>
        </div>
        <button onclick="showAnswer(16)">Show Answer</button>
        <div class="explanation" id="explanation16">
            <span class="correct">Correct Answer: B. Regression</span>
            <p>Explanation: Regression is the correct approach because predicting a continuous numerical value (price) based on input features is a classic regression problem. Classification (A) is used for categorical outputs, clustering (C) is for grouping similar items, and dimensionality reduction (D) is for reducing the number of input variables (Task Statement 1.3).</p>
        </div>
    </div>

    <script>
        function showAnswer(questionNumber) {
            const explanation = document.getElementById(`explanation${questionNumber}`);
            if (explanation.style.display === "block") {
                explanation.style.display = "none";
            } else {
                explanation.style.display = "block";
            }
        }
    </script>
</body>
</html>
