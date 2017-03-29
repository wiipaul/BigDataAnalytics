
Questions:

(1) 哪些屬性對於惡意程式分類有效？
Ans:
以下屬性對於惡意程式分類有效
section_names_header
ent_q_diff_diffs_2_min
ent_p_12
dc_por
ent_p_7
ent_q_diff_diffs_1_min
ent_q_diffs_19
ent_q_diff_diffs_10
Img49               

(2) 哪些屬性對於惡意程式分類無效？
Ans:
以下屬性對於惡意程式分類無效
__vbaVar2Vec
__vbaFixstrConstruct
GetFileTitleA
ProcCallEngine
__vbaAryConstruct2
MethCallEngine
*invalid*
INTERNET_STATUS_CALLBACK
fstcwimul
DeleteEnhMetaFile
PCCTL_CONTEXT
__vbaLsetFixstr

(3) 用什麼方法可以幫助你決定上述的結論？
Ans:
   利用sklearn裡的ExtraTreesClassifier方法(設定criteria為entropy)，計算每個屬性的Information gained來做判別

(4) 透過Python哪些套件以及方法可以幫助你完成上面的工作？
Ans:
   Numpy、Matplotlib、pandas、scikit-learn


