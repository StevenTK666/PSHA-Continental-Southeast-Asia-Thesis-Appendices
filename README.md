# 中南半島地震危害分析論文附錄  
# Thesis Appendices for Probabilistic Seismic Hazard Assessments for Continental Southeast Asia

本資料庫收錄碩士論文《中南半島地震危害分析》之附錄、補充資料與 OpenQuake-engine 輸入檔案。內容包括活動斷層參數表、整體研究區規模－頻率回歸圖、各研究分區規模－頻率回歸圖，以及本研究地震危害分析所使用之主要輸入檔案。

This repository contains thesis appendices, supplementary materials, and OpenQuake-engine input files for the master's thesis *Probabilistic Seismic Hazard Assessments for Continental Southeast Asia*. The materials include active fault parameters, magnitude–frequency regression figures for the overall study region, regression figures for individual seismic source zones, and major input files used in the seismic hazard calculations.

## Contents / 內容

### Appendix 1. Fault Parameters / 附錄一：活動斷層參數

This folder contains the active fault parameter table used in this study, including the fault geometry, slip rate, faulting style, and parameters derived from empirical scaling relations. WC1994 refers to Wells and Coppersmith (1994), L2014 refers to Leonard (2014), and T2017 refers to Thingbaijam et al. (2017).

本資料夾收錄本研究採用之活動斷層參數表，包括斷層幾何、滑移率、斷層型態，以及由經驗尺度關係推估之相關參數。其中，WC1994 代表 Wells and Coppersmith（1994），L2014 代表 Leonard（2014），T2017 代表 Thingbaijam et al.（2017）。

### Appendix 2. Magnitude–Frequency Regression Figures for the Overall Study Region / 附錄二：不同去叢集方法下全研究區 b 值估算之規模－頻率分布圖

This folder contains the magnitude–frequency distribution figures used to estimate the b value for the overall study region under different declustering methods, including the Gardner and Knopoff (1974), Grünthal (personal communication), and Uhrhammer (1986) methods.

本資料夾收錄本研究於全研究區範圍內，分別採用 Gardner and Knopoff（1974）、Grünthal（personal communication）及 Uhrhammer（1986）去叢集方法後，用於估算 b 值之規模－頻率分布圖。圖中淺藍色點表示未納入迴歸之觀測資料，深藍色點表示用於迴歸之觀測資料，紅色實線表示 Gutenberg–Richter 模型擬合結果，粉紅色虛線表示標準差範圍，綠色虛線表示本研究採用之規模範圍。

### Appendix 3. Magnitude–Frequency Regression Figures for Individual Source Zones / 附錄三：不同去叢集方法下各分區 a 值估算之規模－頻率分布圖

This folder contains the magnitude–frequency distribution figures used to estimate the a values for individual seismic source zones under different declustering methods.

本資料夾收錄各研究分區分別採用 Gardner and Knopoff（1974）、Grünthal（personal communication）及 Uhrhammer（1986）去叢集方法後，用於估算 a 值之規模－頻率分布圖。圖中淺藍色點表示未納入迴歸之觀測資料，深藍色點表示用於迴歸之觀測資料，紅色實線表示 Gutenberg–Richter 模型擬合結果，粉紅色虛線表示標準差範圍，綠色虛線表示本研究採用之規模範圍。

### Appendix 4. Magnitude–Frequency Regression Figures for Zone 19 / 附錄四：不同去叢集方法下區域 19 之 a、b 值估算之規模－頻率分布圖

This folder contains the magnitude–frequency distribution figures used to estimate the a and b values for Zone 19 under different declustering methods.

本資料夾收錄區域 19 分別採用 Gardner and Knopoff（1974）、Grünthal（personal communication）及 Uhrhammer（1986）去叢集方法後，用於估算 a、b 值之規模－頻率分布圖。圖中淺藍色點表示未納入迴歸之觀測資料，深藍色點表示用於迴歸之觀測資料，紅色實線表示 Gutenberg–Richter 模型擬合結果，粉紅色虛線表示標準差範圍，綠色虛線表示本研究採用之規模範圍。

### OpenQuake Input Files / OpenQuake 輸入檔案

This folder contains the major OpenQuake-engine input files used in the PSHA calculations.

本資料夾收錄本研究進行機率式地震危害分析所使用之主要 OpenQuake-engine 輸入檔案。

## Author / 作者

Yuankai Chang  
Department of Earth Sciences, National Central University  
張原凱  
國立中央大學地球科學系
