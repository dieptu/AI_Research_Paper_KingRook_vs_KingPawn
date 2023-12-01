# AI_Research_Paper_KingRook_vs_KingPawn
In this project we are going to perform classification on the chess(King-Rook vs King) Dataset.We are going to use Decision Tree Classifier to perform the classification task. We are going to predict the values of the column named as result in the above mentioned dataset.

## Sources:
    (a) Database originally generated and described by Alen Shapiro.
    (b) Donor/Coder: Rob Holte (holte@uottawa.bitnet).  The database
        was supplied to Holte by Peter Clark of the Turing Institute
        in Glasgow (pete@turing.ac.uk).
    (c) Date: 1 August 1989

## Relevant Information:
    1. The dataset format is described below.  Note: the format of this
    database was modified on 2/26/90 to conform with the format of all
    the other databases in the UCI repository of machine learning databases.
    2. Number of Instances: 3196 total
    3. Number of Attributes: 36
    4. Attribute Summaries:
      Classes (2):  -- White-can-win ("won") and White-cannot-win ("nowin").
            I believe that White is deemed to be unable to win if the Black pawn
            can safely advance.
      Attributes: see Shapiro's book.
    5. Missing Attributes: --  none
    6. Class Distribution:
    In 1669 of the positions (52%), White can win.
    In 1527 of the positions (48%), White cannot win.

The format for instances in this database is a sequence of 37 attribute values.
Each instance is a board-descriptions for this chess endgame.  The first
36 attributes describe the board.  The last (37th) attribute is the
classification: "win" or "nowin".  There are 0 missing values.
A typical board-description is

f,f,f,f,f,f,f,f,f,f,f,f,l,f,n,f,f,t,f,f,f,f,f,f,f,t,f,f,f,f,f,f,f,t,t,n,won

The names of the features do not appear in the board-descriptions.
Instead, each feature correponds to a particular position in the
feature-value list.  For example, the head of this list is the value
for the feature "bkblk".  The following is the list of features, in
the order in which their values appear in the feature-value list:

[bkblk,bknwy,bkon8,bkona,bkspr,bkxbq,bkxcr,bkxwp,blxwp,bxqsq,cntxt,dsopp,dwipd,
 hdchk,katri,mulch,qxmsq,r2ar8,reskd,reskr,rimmx,rkxwp,rxmsq,simpl,skach,skewr,
 skrxp,spcop,stlmt,thrsk,wkcti,wkna8,wknck,wkovl,wkpos,wtoeg]

In the file, there is one instance (board position) per line.
