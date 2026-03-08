# internship-portfolio

序列設計(使用 C 語言):

-PCP  (Periodic Complementary Pair)  Sequence
目標: 尋找N>70 且具備理想自相關特性（AACF）之 PCP 序列
簡述: 針對指數級增長的搜尋空間，透過自主研讀學術論文並成功重現其 SDS SDS (Sum of Difference Sets) 理論架構，將序列搜尋問題轉化為代數集合之組合問題，並推導出必要代數約束，解決硬體運算資源限制。

-PACP/PQCP Sequence
目標: 針對特定長度 N 下 PCP 序列之存在性限制，轉而搜尋具備低旁瓣特性的PACP與 PQCP，以增加系統在同步與通道估計上的設計彈性
簡述: 
(1)運算複雜度優化：將序列自相關計算轉換為Hamming Distance，並推導出簡潔的「變動位元總數」數值限制，顯著提升單次迭代的運算速度    (2)理論空間縮減：應用 Parseval's Theorem 推導出 {+1, -1} 分布個數之理論邊界，並結合序列對稱性與等價性進行多重剪枝 (pruning)，在搜尋初期排除不符條件之候選空間


錯誤更正碼(使用 C 語言):

-Convolutional codes
簡述: 建構通訊系統模擬環境，透過設定 Random Seed 確保實驗結果之可重現性。實作 Viterbi 解碼演算法，並繪製Hard-Decision與Soft-Decision在不同SNR條件下的解碼性能差異

-LDPC decoder:
簡述: 實作 SPA (Sum-Product Algorithm)、MSA (Min-Sum Algorithm) 與 BF (Bit-Flipping) 解碼演算法，並繪製不同 SNR 條件下的 BER / BLER 曲線；同時透過設定不同迭代次數觀察 BF 解碼效能變化

報告(無實作): OFDM
