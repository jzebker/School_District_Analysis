# School_District_Analysis

## Overview:
The school board has found evidence of academic dishonesty after an analysis of the school district has already been completed.  Repeat the school district analysis for Maria after removing compromised test scores and provide a written report on how the results have changed.

## Results:
### How is the district summary affected?
- All five scoring metrics saw slight decreases
<p align="center">
  <strong><i>Updated District Summary</i></strong>
  <img width="917" alt="newdistrictsummary" src="https://user-images.githubusercontent.com/84994321/125208910-40f22380-e24a-11eb-8e4f-7e33cbce2ab8.png">
</p>
<p align="center">
  <strong><i>Original District Summary</i></strong>
  <img width="919" alt="olddistrictsummary" src="https://user-images.githubusercontent.com/84994321/125208920-48b1c800-e24a-11eb-987d-5569bd95b794.png">
</p>

### How is the school summary affected?
- Thomas High School is the only school whose data was affected
- The average reading score at Thomas High School slightly increased
- All other categories saw slight decreases
<p align="center">
  <strong><i>Updated School Summary (Thomas High School)</i></strong>
  <img width="980" alt="THSheaders" src="https://user-images.githubusercontent.com/84994321/125207931-53695e80-e244-11eb-8d9a-de009e06ca47.png">
  <img width="962" alt="thomashighnew" src="https://user-images.githubusercontent.com/84994321/125207703-8dd1fc00-e242-11eb-9e2b-418f81ae0e3b.png">
</p>
<p align="center">
  <strong><i>Original School Summary (Thomas High School)</i></strong>
  <img width="980" alt="THSheaders" src="https://user-images.githubusercontent.com/84994321/125207931-53695e80-e244-11eb-8d9a-de009e06ca47.png">
  <img width="958" alt="thomashighold" src="https://user-images.githubusercontent.com/84994321/125209479-db079b00-e24d-11eb-8413-8e604cc90a16.png">
</p>

### How does replacing the ninth graders’ math and reading scores affect Thomas High School’s performance relative to the other schools?
- The updated scores did not affect Thomas High School's ranking by overall passing percentage
<p align="center">
  <strong><i>Updated Schools by Overall Passing Percentage</i></strong>
  <img width="991" alt="newtopfive" src="https://user-images.githubusercontent.com/84994321/125207880-fa012f80-e243-11eb-996a-0fa07c2000e1.png">
</p>
<p align="center">
  <strong><i>Original Schools by Overall Passing Percentage</i></strong>
  <img width="990" alt="oldtopfive" src="https://user-images.githubusercontent.com/84994321/125207979-b2c76e80-e244-11eb-8484-a52f40889776.png">
</p>

### How does replacing the ninth-grade scores affect the following:
#### Math and reading scores by grade
- Only the data for 9th grade students at Thomas High School was omitted
<p align="center">
  <strong><i>Updated Scores by Grade</i></strong>
</p>  
<p align="center">
  <img width="592" alt="updatedscoresbygrade" src="https://user-images.githubusercontent.com/84994321/125210519-2b362b80-e255-11eb-9090-87ea08306afe.png">
</p>
<p align="center">
  <strong><i>Original Scores by Grade</i></strong>
</p>
<p align="center">
  <img width="595" alt="oldscoresbygrade" src="https://user-images.githubusercontent.com/84994321/125210534-38531a80-e255-11eb-9b1f-4fda8641a047.png">
</p>

#### Scores by school spending
- Only data for the spending range $630-$644 (Thomas High School: $638) was affected
- The average reading score slightly increased
- All other categories saw slight decreases
<p align="center">
  <strong><i>Updated Scores by Spending</i></strong>
  <img width="838" alt="newdataspendingrange" src="https://user-images.githubusercontent.com/84994321/125208012-dee2ef80-e244-11eb-9b95-c454ee9fb0ac.png">
</p>
<p align="center">
  <strong><i>Original Scores by Spending</i></strong>
  <img width="826" alt="olddataspendingrange" src="https://user-images.githubusercontent.com/84994321/125208038-03d76280-e245-11eb-9d85-6f5bc7093972.png">
</p>

#### Scores by school size
- Only data for the medium school size range (Thomas High School: 1635) was affected
- The average reading score slightly increased
- All other categories saw slight decreases
<p align="center">
  <strong><i>Updated Scores by School Size</i></strong>
</p>
<p align="center">
  <img width="752" alt="newschoolsize" src="https://user-images.githubusercontent.com/84994321/125209950-76e6d600-e251-11eb-9551-aca0c8fba9b1.png">
</p>
<p align="center">
  <strong><i>Original Scores by School Size</i></strong>
</p>
<p align="center">
  <img width="766" alt="olddataschoolsize" src="https://user-images.githubusercontent.com/84994321/125208068-397c4b80-e245-11eb-85ba-eda576446d41.png">
</p>

#### Scores by school type
- Only data for charter schools (Thomas High School: charter) was affected
- The average reading score slightly increased
- All other categories saw slight decreases
<p align="center">
  <strong><i>Updated Scores by School Type</i></strong>
</p>
<p align="center">
  <img width="712" alt="newdataschooltype" src="https://user-images.githubusercontent.com/84994321/125208077-5022a280-e245-11eb-81d5-a15daa7e3c87.png">
</p>
<p align="center">
  <strong><i>Original Scores by School Type</i></strong>
</p>
<p align="center">
  <img width="719" alt="olddataschooltype" src="https://user-images.githubusercontent.com/84994321/125208099-64ff3600-e245-11eb-9cef-b345034752a1.png">
</p>

## Summary:
Summarize four changes in the updated school district analysis after reading and math scores for the ninth grade at Thomas High School have been replaced with NaNs.
- The average reading score, average math score, and overall passing rate for the entire school district all slightly decreased
- At Thomas High School in particular, the average reading score slightly increased while average math score and overall passing rate slightly decreased
- Thomas High School's ranking vs other district schools did not change as a result of the omitted data
- For the category corresponding to the group Thomas High School was classified into for school spending, size, and type, the average reading score slightly increased while the average math score and overall passing rate slightly decreased
