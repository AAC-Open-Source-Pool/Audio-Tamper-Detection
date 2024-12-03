# Audio-Tamper-Detection
<h2>Team Details</h2>
<b>Team Number: </b><p>24AACR11</p>
<b>Senior Mentor:</b><p> Anjali </p>
<b>Junior Mentor:</b><p> Sathvik</p>
<b>Team Member 1:</b><p> Advitha</p>
<b>Team Member 2:</b><p> Dhanush</p>
<b>Team Member 3:</b><p> Sriya Rajam</p>
<b>Team Member 4:</b><p> Pavan</p>
<b>Team Member 5:</b><p> Nadeem</p>

<h1>About this project:</h1>
<p>The goal of this project is to develop a system capable of detecting tampered or manipulated audio files using Convolutional Neural Networks (CNN). With the increasing prevalence of audio-based media, there is a growing need to verify the authenticity of audio content, especially in areas like news broadcasting, forensic analysis, and digital rights management. This project aims to leverage the power of deep learning, specifically CNNs, to automatically identify and classify audio as either genuine or tampered.</p>

<h1>Table of Contents</h1>
    <ol>
        <li><a href="#introduction">Introduction</a></li>
        <li><a href="#requirements">Requirements</a></li>
        <li><a href="#howuse">How to use</a></li>
        <li><a href="#preview">Preview</a></li>
        <li><a href="#contribution">Contribution</a></li>
    </ol>
<h2 id="introduction">Introduction</h2>
    <p>
        This project uses deep learning models to detect audio tampering. The key features of the project 
        include extracting audio features, training a CNN-based model, and classifying the audio files. 
        The project focuses on providing a scalable and reliable solution for identifying tampered audio files.
    </p>
<h2 id="requirements">Requirements</h2>
    <table border="1" cellspacing="0" cellpadding="5">
        <thead>
            <tr>
                <th>Tool/Library</th>
                <th>Versions</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Python</td>
                <td>3.8 or 3.9</td>
            </tr>
            <tr>
                <td>NumPy</td>
                <td>Version 1.23.1</td>
            </tr>
            <tr>
                <td>TensorFlow/Keras</td>
                <td>Version 2.12</td>
            </tr>
            <tr>
                <td>Librosa</td>
                <td>Version 0.10.0</td>
            </tr>
            <tr>
                <td>Matplotlib</td>
                <td>Version 3.7.1</td>
            </tr>
            <tr>
                <td>Scikit-learn</td>
                <td>Version 1.2.2</td>
            </tr>
            <tr>
                <td>Pandas</td>
                <td>Version 1.5.3</td>
            </tr>
        </tbody>
    </table>
<h2 id="howuse">How to Use</h2>
<ol>
    <li><strong>Clone the Repository:</strong>
        <p>Open your terminal and run the following command:</p>
        <pre><code>git clone https://github.com/your-repo/audio-tamper-detection.git</code></pre>
    </li>
    <li><strong>Navigate to the Project Directory:</strong>
        <p>Navigate to the project folder:</p>
        <pre><code>cd audio-tamper-detection</code></pre>
    </li>
    <li><strong>Install Dependencies:</strong>
        <p>Ensure Python 3.8 or 3.9 is installed, then run:</p>
        <pre><code>pip install numpy tensorflow librosa matplotlib scikit-learn
</code></pre>
    </li>
    <li><strong>Prepare Your Dataset:</strong>
        <p>download your datasets from the given link</p>
        <a href="https://owncloud.fraunhofer.de/index.php/s/JZgXh0JEAF0elxa/download" target="_blank">Dataset link</a>
    </li>
    <li>Execute the code:</strong>
    <pre><code>audiotampering.ipynb</code></pre>
    </li>
    <li><strong>View Results:</strong>
        <p>The script will output whether the audio file is classified as <code>not tampered</code> or <code>tampered</code>.</p>
    </li>
</ol>

<h2 id="preview">Preview</h2>
    <p>
        <img src="https://i.imgur.com/XjANgyK.jpeg" alt="Audio Detection sample" />
    </p>
<h2 id="contribution">Contribution</h2>
<p><strong>This section provides instructions and details on how to submit a contribution via a pull request. It is important to follow these guidelines to make sure your pull request is accepted.</strong></p>
<p>1. Before choosing to propose changes to this project, it is advisable to go through the <code>readme.md</code> file of the project to get the philosophy and the motive that went behind this project. The pull request should align with the philosophy and the motive of the original poster of this project.</p>
<p>2. To add your changes, make sure that the programming language in which you are proposing the changes should be the same as the programming language that has been used in the project. The versions of the programming language and the libraries (if any) used should also match with the original code.</p>
<p>3. Write a documentation on the changes that you are proposing. The documentation should include the problems you have noticed in the code (if any), the changes you would like to propose, the reason for these changes, and sample test cases. Remember that the topics in the documentation are strictly not limited to the topics aforementioned, but are just an inclusion.</p>
<p>4. Submit a pull request via <a href="https://gist.github.com/mikepea/863f63d6e37281e329f8" target="_blank">Git etiquettes</a>.</p>

