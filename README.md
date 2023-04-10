# pandas_challenge
Module 4 Challenge

4/9/23 - Resubmitting Pandas Challenge

Acknowledgements: Tutor - David Pecot for review of Pandas material specifically Module 4 which helped with grouping and aggregation of data in Pandas. I rewatched all three lectures and reviewed solutions to activities. I also leaned heavily on Pandas documentation, Binning discussion from class, but went back to  Stackoverflow for pd.cut examples in resolving issues with "integer versus string variables" and need to change mask on 'Per Student Budget' as follows: school_spending_df["Per Student Budget"] = school_spending_df["Per Student Budget"].str.replace("$", "") and convert to .astype (float) in Pd.cut.
