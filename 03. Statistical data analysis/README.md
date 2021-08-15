# Statistical data analysis

__Definition of a prospective tariff for a telecom company__

__Client__ - federal mobile operator.

__Input data__ - data from 500 users: who they are, where they come from, what tariff they use, how many calls and messages each one sent in 2018.

__Target__ - analyze customer behavior and conclude - which tariff is better.

__What's done__:
- data preprocessing:
    - analysis of 5 source files;
    - index columns change;
    - data types correction;
    - 0 replacement with small values for calls and internet sessions.
- calculation of new features:
    - number of calls made and spent minutes of conversation by month;
    - number of messages sent by month;
    - internet traffic consumed by month;
    - monthly revenue from each user.
- EDA preformed - two tariffs were compared with, mean, variance, standard deviation, graphs (histograms and boxplots) and 3 sigma rule by users, calls, messages and internet-sessions;
- the hypothesis that the average revenue of users of the two tariffs is the same tested and rejected;
- the hypothesis that the average revenue of users from Moscow and other regions is the same tested and not rejected;
- the hypothesis that the average revenue of users of the Ultra and Smart tariffs is the same tested and rejected - the average revenue of the Smart tariff is less than the revenue of the Ultra tariff.
- tariff "Ultra" was recognized as the best.

__Tools used__ - pandas, NumPy, Matplotlib, SciPy.