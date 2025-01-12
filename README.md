<h1 align="center">Item-Based | Content-Based | Hybrid Recommendation Systems</h1>

<br/>

<h2>🚀 <strong>Objective</strong></h2>
<p>
This project explores the power of recommendation systems by leveraging a movie dataset. The aim is to develop item-based, content-based, and hybrid recommendation systems, analyze their strengths, and showcase how combining these approaches can improve personalization and accuracy in movie recommendations.
</p>

<h2>📂 <strong>Dataset</strong></h2>
<p>
The analysis utilizes "The Movies Dataset," which provides detailed information about movies, including titles, overviews, user ratings, and more. This data allows us to combine user interactions and content-related features for robust recommendations.
</p>

<p><em>Dataset available on <a href="https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset" target="_blank">Kaggle</a>.</em></p>

<h2>📈 <strong>Methodology</strong></h2>
<ul>
  <li><strong>Item-Based Recommendation:</strong> Utilizes user-item interactions to identify similarities between movies based on user ratings.</li>
  <li><strong>Content-Based Recommendation:</strong> Leverages textual features of movies, such as overviews, using techniques like TF-IDF and cosine similarity.</li>
  <li><strong>Hybrid Recommendation System:</strong> Combines the strengths of item-based and content-based methods to deliver refined and holistic movie recommendations.</li>
</ul>

<h2>🔍 <strong>Steps in the Process</strong></h2>

<h3>📋 Reading and Cleaning Data</h3>
<ul>
  <li>Loaded and preprocessed datasets, including removing missing values and duplicates.</li>
  <li>Renamed columns and ensured consistency in data types for seamless integration.</li>
  <li>Joined datasets to link user interactions with movie metadata.</li>
</ul>

<h3>📌 Item-Based Recommendation</h3>
<ul>
  <li>Computed user-movie interaction matrices.</li>
  <li>Identified movies similar to a target movie by analyzing correlation scores.</li>
  <li>Generated recommendations based on item similarities.</li>
</ul>

<h3>📌 Content-Based Recommendation</h3>
<ul>
  <li>Used <strong>TF-IDF Vectorization</strong> to analyze movie overviews.</li>
  <li>Calculated cosine similarity to find movies with similar content.</li>
  <li>Generated content-based recommendations by ranking movies with the highest similarity scores.</li>
</ul>

<h3>📌 Hybrid Recommendation System</h3>
<ul>
  <li>Combined item-based and content-based scores using <strong>MinMaxScaler</strong>.</li>
  <li>Calculated a hybrid score by multiplying normalized item-based and content-based scores.</li>
  <li>Ranked movies based on their hybrid scores to produce final recommendations.</li>
</ul>

<h2>🔧 <strong>Technologies Used</strong></h2>
<div align="center">
    <img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" alt="Python"/>
    <img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas"/>
    <img src="https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy"/>
    <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn"/>
    <img src="https://img.shields.io/badge/matplotlib-11557C?style=for-the-badge&logo=matplotlib&logoColor=white" alt="Matplotlib"/>
</div>

<h2>📊 <strong>Key Insights</strong></h2>
<ul>
  <li><strong>Item-Based:</strong> Provides excellent recommendations for movies frequently co-rated by users.</li>
  <li><strong>Content-Based:</strong> Excels in suggesting movies with similar plots and genres.</li>
  <li><strong>Hybrid Approach:</strong> Delivers the best of both worlds, balancing user preferences and content similarities for more accurate recommendations.</li>
</ul>

<h2>📢 <strong>Contact</strong></h2>
<ul>
  <li><a href="https://www.linkedin.com/in/yourusername/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white" alt="LinkedIn"/></a></li>
  <li><a href="mailto:your.email@example.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white" alt="Email"/></a></li>
</ul>

<p align="center">&copy; 2025 Your Name. All rights reserved.</p>

<hr/>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ecembayindir&repo=movie-recommendation-systems&label=Repository%20views&color=0e75b6&style=flat" alt="Repository Views">
</p>
