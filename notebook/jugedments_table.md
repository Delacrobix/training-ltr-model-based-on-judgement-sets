<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>query_id</th>
      <th>query</th>
      <th>doc_id</th>
      <th>text</th>
      <th>genre</th>
      <th>grade</th>
      <th>text_bm25_score</th>
      <th>genre_boost_score</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc1</td>
      <td>DiCaprio's performance in The Revenant was bre...</td>
      <td>Drama</td>
      <td>4</td>
      <td>1.481370</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>1</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc2</td>
      <td>Inception shows Leonardo DiCaprio in one of hi...</td>
      <td>Sci-Fi</td>
      <td>4</td>
      <td>2.508342</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>2</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc3</td>
      <td>The Wolf of Wall Street features DiCaprio's ch...</td>
      <td>Drama</td>
      <td>3</td>
      <td>1.481370</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>3</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc4</td>
      <td>Titanic showcases DiCaprio's early career brea...</td>
      <td>Romance</td>
      <td>3</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>4</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc5</td>
      <td>Brad Pitt delivers a solid performance in this...</td>
      <td>Crime</td>
      <td>0</td>
      <td>1.481370</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>5</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc6</td>
      <td>Tom Hanks gives an outstanding performance in ...</td>
      <td>War</td>
      <td>0</td>
      <td>1.584190</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>6</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc15</td>
      <td>An action-packed adventure with stunning visua...</td>
      <td>Action</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>7</th>
      <td>query1</td>
      <td>DiCaprio performance</td>
      <td>doc12</td>
      <td>A lighthearted comedy that will make you laugh...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>8</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc8</td>
      <td>A heartbreaking story of love and loss that ma...</td>
      <td>Drama</td>
      <td>4</td>
      <td>3.930469</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>9</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc9</td>
      <td>One of the saddest movies ever made — bring ti...</td>
      <td>Drama</td>
      <td>4</td>
      <td>4.160228</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>10</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc10</td>
      <td>A tragic tale of separation and longing that l...</td>
      <td>Romance</td>
      <td>3</td>
      <td>1.140901</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>11</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc11</td>
      <td>This devastating war film shows the human cost...</td>
      <td>War</td>
      <td>3</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>12</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc1</td>
      <td>DiCaprio's performance in The Revenant was bre...</td>
      <td>Drama</td>
      <td>2</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>13</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc12</td>
      <td>A lighthearted comedy that will make you laugh...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>5.796269</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>14</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc13</td>
      <td>This hilarious romantic comedy features witty ...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>15</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc15</td>
      <td>An action-packed adventure with stunning visua...</td>
      <td>Action</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>16</th>
      <td>query2</td>
      <td>sad movies that make you cry</td>
      <td>doc14</td>
      <td>An absurdist comedy that will have you rolling...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>2.855625</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>17</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc2</td>
      <td>Inception shows Leonardo DiCaprio in one of hi...</td>
      <td>Sci-Fi</td>
      <td>4</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>18</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc16</td>
      <td>A science-fiction epic full of action and exci...</td>
      <td>Sci-Fi</td>
      <td>4</td>
      <td>5.332052</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>19</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc17</td>
      <td>This space opera combines epic battles with de...</td>
      <td>Sci-Fi</td>
      <td>4</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>20</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc4</td>
      <td>Titanic showcases DiCaprio's early career brea...</td>
      <td>Romance</td>
      <td>1</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>21</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc15</td>
      <td>An action-packed adventure with stunning visua...</td>
      <td>Action</td>
      <td>2</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>22</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc8</td>
      <td>A heartbreaking story of love and loss that ma...</td>
      <td>Drama</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>23</th>
      <td>query3</td>
      <td>science fiction movies</td>
      <td>doc12</td>
      <td>A lighthearted comedy that will make you laugh...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>24</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc18</td>
      <td>A psychological thriller that will keep you on...</td>
      <td>Thriller</td>
      <td>4</td>
      <td>1.702570</td>
      <td>2.412232</td>
    </tr>
    <tr>
      <th>25</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc20</td>
      <td>A suspenseful mystery thriller with unexpected...</td>
      <td>Thriller</td>
      <td>4</td>
      <td>2.131047</td>
      <td>2.412232</td>
    </tr>
    <tr>
      <th>26</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc19</td>
      <td>This horror film features terrifying jump scar...</td>
      <td>Horror</td>
      <td>3</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>27</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc5</td>
      <td>Brad Pitt delivers a solid performance in this...</td>
      <td>Crime</td>
      <td>3</td>
      <td>1.923577</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>28</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc11</td>
      <td>This devastating war film shows the human cost...</td>
      <td>War</td>
      <td>1</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>29</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc12</td>
      <td>A lighthearted comedy that will make you laugh...</td>
      <td>Comedy</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>30</th>
      <td>query4</td>
      <td>thriller suspense movies</td>
      <td>doc21</td>
      <td>A beautiful love story that spans decades and ...</td>
      <td>Romance</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>31</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc21</td>
      <td>A beautiful love story that spans decades and ...</td>
      <td>Romance</td>
      <td>4</td>
      <td>3.118642</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>32</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc22</td>
      <td>This romantic drama explores the complexities ...</td>
      <td>Romance</td>
      <td>4</td>
      <td>2.409131</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>33</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc4</td>
      <td>Titanic showcases DiCaprio's early career brea...</td>
      <td>Romance</td>
      <td>4</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>34</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc10</td>
      <td>A tragic tale of separation and longing that l...</td>
      <td>Romance</td>
      <td>3</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>35</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc13</td>
      <td>This hilarious romantic comedy features witty ...</td>
      <td>Comedy</td>
      <td>2</td>
      <td>2.495745</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>36</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc8</td>
      <td>A heartbreaking story of love and loss that ma...</td>
      <td>Drama</td>
      <td>3</td>
      <td>2.252769</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>37</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc15</td>
      <td>An action-packed adventure with stunning visua...</td>
      <td>Action</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
    <tr>
      <th>38</th>
      <td>query5</td>
      <td>romantic love stories</td>
      <td>doc19</td>
      <td>This horror film features terrifying jump scar...</td>
      <td>Horror</td>
      <td>0</td>
      <td>NaN</td>
      <td>NaN</td>
    </tr>
  </tbody>
</table>
</div>