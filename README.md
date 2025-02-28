# ABD-PRJ-25-22-

https://www.kaggle.com/datasets/deepakshende/onlinenewspopularity

This dataset summarizes a heterogeneous set of features about articles published by Mashable in a period of two years.
The goal is to predict the number of shares in social networks, i.e. how popular any given article is. 
The dataset is publicly available at University of California Irvine Machine Learning Repository.


|№|Столбец|Eng|Рус|тип данных|
|--|-----|---|-- |---|
|1.|  url |URL of the article| URL адрес источника|
|2.|  timedelta|Days between the article publication and the dataset acquisition|кол-во дней между публикацией до получения данных|КолДискр|
|3.|  n_tokens_title|Number of words in the title|кол-во слов в заголовке|КолДискр|
|4.|  n_tokens_content|Number of words in the content|кол-во слов в статье|КолДискр|
|5.|  n_unique_tokens|Rate of unique words in the content|доля уникальных слов в статье|КолНепр|
|6.|  n_non_stop_words|Rate of non-stop words in the content|доля нонстоп-слов в статье|КолНепр|
|7.|  n_non_stop_unique_tokens|Rate of unique non-stop words in the content|доля уникальных нонстоп-слов в статье|КолНепр|
|8.|  num_hrefs|Number of links|кол-во ссылок в статье|КолДискр|
|9.|  num_self_hrefs|Number of links to other articles published by Mashable|кол-во ссылок на другие статьи, опубликованные в Mashable|КолДискр|
|10.| num_imgs|Number of images|кол-во изображений в статье|КолДискр|
|11.| num_videos|Number of videos|кол-во видео в статье|КолДискр|
|12.| average_token_length|Average length of the words in the content|средняя длина слов в статье|КолНепр|
|13.| num_keywords|Number of keywords in the metadata|кол-во ключевых слов в метаданных|КолДискр|
|14.| data_channel_is_lifestyle|Is data channel 'Lifestyle'?|из рубрики 'Lifestyle'?|КатБином|
|15.| data_channel_is_entertainment|Is data channel 'Entertainment'?|из рубрики 'Entertainment'?|КатБином|
|16.| data_channel_is_bus|Is data channel 'Business'?|из рубрики 'Business'?|КатБином|
|17.| data_channel_is_socmed|Is data channel 'Social Media'?|из рубрики 'Social Media'?|КатБином|
|18.| data_channel_is_tech|Is data channel 'Tech'?|из рубрики 'Tech'?|КатБином|
|19.| data_channel_is_world|Is data channel 'World'?|из рубрики 'World'?|КатБином|
|20.| kw_min_min|Worst keyword (min. shares)|худшее ключевое слово (мин кол-во cсылок)|КолДискр|
|21.| kw_max_min|Worst keyword (max. shares)|худшее ключевое слово (макс. кол-во cсылок)|КолДискр|
|22.| kw_avg_min|Worst keyword (avg. shares)|худшее ключевое слово (средн. кол-во cсылок)|КолНепр|
|23.| kw_min_max|Best keyword (min. shares)|лучшее ключевое слово (мин. кол-во cсылок)|КолНепр|
|24.| kw_max_max|Best keyword (max. shares)|лучшее ключевое слово (макс. кол-во cсылок)|КолНепр|
|25.| kw_min_avg|Best keyword (avg. shares)|лучшее ключевое слово (средн. кол-во cсылок)|КолНепр|
|26.| kw_min_avg|Avg. keyword (min. shares)|среднее ключевое слово (средн. кол-во cсылок)|КолНепр|
|27.| kw_max_avg|Avg. keyword (max. shares)|среднее ключевое слово (макс.  кол-во cсылок)|КолНепр|
|28.| kw_avg_avg|Avg. keyword (avg. shares)|среднее ключевое слово (средн.  кол-во cсылок)|КолНепр|
|29.| self_reference_min_shares|Min. shares of referenced articles in Mashable|мин. кол-во упоминаемых статей в Mashable|КолДискр|
|30.| self_reference_max_shares|Max. shares of referenced articles in Mashable|макс. кол-во упоминаемых статей в Mashable|КолДискр|
|31.| self_reference_avg_sharess|Avg. shares of referenced articles in Mashable|средн. кол-во упоминаемых статей в Mashable|КолНепр|
|32.| weekday_is_monday|Was the article published on a Monday?|день публикации 'Понедельник'?|КатБином|
|33.| weekday_is_tuesday|Was the article published on a Tuesday?|день публикации 'Вторник'?|КатБином|
|34.| weekday_is_wednesday|Was the article published on a Wednesday?|день публикации 'Среда'?|КатБином|
|35.| weekday_is_thursday|Was the article published on a Thursday?|день публикации 'Четверг'?|КатБином|
|36.| weekday_is_friday|Was the article published on a Friday?|день публикации 'Пятница'?|КатБином|
|37.| weekday_is_saturda|Was the article published on a Saturday?|день публикации 'Суббота'|КатБином|
|38.| weekday_is_sunday|Was the article published on a Sunday?|день публикации 'Воскресенье'?|КатБином|
|39.| is_weekend|Was the article published on the weekend?|день публикации 'Выходные'|КатБином|
|40.| LDA_00|Closeness to LDA topic 0|близость LDA (Latent Dirichlet Allocation):  0|КолНепр|
|41.| LDA_01|Closeness to LDA topic 1|близость LDA (Latent Dirichlet Allocation):  1|КолНепр|
|42.| LDA_02|Closeness to LDA topic 2|близость LDA (Latent Dirichlet Allocation): 2|КолНепр|
|43.| LDA_03|Closeness to LDA topic 3|близость LDA (Latent Dirichlet Allocation):  3|КолНепр|
|44.| LDA_04|Closeness to LDA topic 4|близость LDA (Latent Dirichlet Allocation):  4|КолНепр|
|45.| global_subjectivity|Text subjectivity|субъективность текста|КолНепр|
|46.| global_sentiment_polarity|Text sentiment polarity|общая полярность настроения текста|КолНепр|
|47.| global_rate_positive_words|Rate of positive words in the content|доля позитивных слов в статье|КолНепр|
|48.| global_rate_negative_words|Rate of negative words in the content|доля негативных слов в статье|КолНепр|
|49.| rate_positive_words|Rate of positive words among non-neutral tokens|доля позитивных слов среди не нейтральных слов|КолНепр|
|50.| rate_negative_words|Rate of negative words among non-neutral tokens|доля негативных слов среди не нейтральных слов|КолНепр|
|51.| avg_positive_polarity|Avg. polarity of positive words|средн. полярность положительных слов|КолНепр|
|52.| min_positive_polarity|Min. polarity of positive words|мин. полярность положительных слов|КолНепр|
|53.| max_positive_polarity|Max. polarity of positive words|макс. полярность положительных слов|КолНепр|
|54.| avg_negative_polarity|Avg. polarity of negative words|средн. полярность отрицательных слов|КолНепр|
|55.| min_negative_polarity|Min. polarity of negative words|мин. полярность отрицательных слов|КолНепр|
|56.| max_negative_polarity|Max. polarity of negative words|макс. полярность отрицательных слов|КолНепр|
|57.| title_subjectivity|Title subjectivity|субъективность заголовка|КолНепр|
|58.| title_sentiment_polarity|Title polarity|полярность настроения заголовка|КолНепр|
|59.| abs_title_subjectivity|Absolute subjectivity level|уровень абсолютной субъективности заголовка|КолНепр|
|60.| abs_title_sentiment_polarity|Absolute polarity level|уровень абсолютой полярности заголовка|КолНепр|
|61.| shares|Number of shares|кол-во ссылок|КолДискр|
