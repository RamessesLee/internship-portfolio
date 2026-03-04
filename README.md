# internship-portfolio

序列設計(使用 C 語言):

-PCP  (Periodic Complementary Pair)  Sequence
目標: 尋找N>70 且具備理想自相關特性（AACF）之 PCP 序列
簡述: 因硬體無法應付龐大的搜尋空間，透過閱讀論文後導入 SDS (Sum of Difference Sets) 理論架構縮小候選範圍，並優化通訊系統 PAPR 表現

-PACP/PQCP Sequence
目標: 針對特定長度 N 無法取得完美 PCP 之限制，轉而搜尋 PACP(Periodic Almost Complementary Pair) 
與 PQCP (Periodic Quasi-Complementary Pair)  序列，以增加系統設計彈性
簡述: 利用序列的對稱性和等價進行剪枝（Pruning），並設定最大相關值門檻以提前排除不符條件之候選序列，再進行平行化運算以提升搜尋效率


錯誤更正碼(使用 C 語言):

-Convolutional codes
簡述: 實作Viterbi 解碼演算法，比較Hard-Decision與Soft-Decision解碼性能差異，並分析不同SNR條件下之BER表現

-LDPC decoder:
簡述: 實作 SPA (Sum-Product Algorithm) 與 MSA (Min-Sum Algorithm)  兩種主流迭代演算法，並繪製不同SNR條件下之BER / BLER 曲線


報告(無實作): OFDM
