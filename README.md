# Online Appendix for "Automated parameter optimization of classification techniques for defect prediction models"

Chakkrit Tantithamthavorn, Shane McIntosh, Ahmed E. Hassan, Kenichi Matsumoto  
[In Proceedings of the 38th International Conference on Software Engineering - ICSE 2016](http://doi.acm.org/10.1145/2884781.2884857)

Abstract: Defect prediction models are classifiers that are trained to identify defect-prone software modules. Such classifiers have configurable parameters that control their characteristics (e.g., the number of trees in a random forest classifier). Recent studies show that these classifiers may underperform due to the use of suboptimal default parameter settings. However, it is impractical to assess all of the possible settings in the parameter spaces. In this paper, we investigate the performance, stability, and interpretation of defect prediction models where Caret - an automated parameter optimization technique - has been applied. Through a case study of 18 datasets from systems that span both proprietary and open source domains, we find that (1) Caret improves the AUC performance of defect prediction models by as much as 40 percentage points; (2) Caret-optimized classifiers are at least as stable as (with 35% of them being more stable than) classifiers that are trained using the default settings; (3) Caret substantially shifts the ranking of the importance of variables, with as few as 28% of the top-ranked variables from the Caret-optimized models appearing in those ranks in the default models; (4) the Caret-suggested setting of 85% of the 20 most sensitive parameters can be applied to datasets that share a similar set of metrics without a statistically significant drop in performance; (5) Caret adds less than 30 minutes of additional computation time to 65% of the studied classification techniques; and (6) Caret increases the likelihood of producing a top-performing classifier by as much as 83%. Hence, we conclude that parameter settings do indeed have a large impact on the performance, stability, and interpretation of defect prediction models, suggesting that researchers should experiment with the parameters of classification techniques. Automated parameter optimization techniques like Caret, on one hand, yield substantially benefits in terms of performance and stability, and can shift the impact of software metrics, while on the other hand, incur a manageable additional computational cost. Thus, we recommend that automated parameter optimization should be included in future defect prediction studies.

## Bibtex

```bibtex
@inproceedings{Tantithamthavorn:2016:APO:2884781.2884857,
 author = {Tantithamthavorn, Chakkrit and McIntosh, Shane and Hassan, Ahmed E. and Matsumoto, Kenichi},
 title = {Automated Parameter Optimization of Classification Techniques for Defect Prediction Models},
 booktitle = {Proceedings of the 38th International Conference on Software Engineering},
 series = {ICSE '16},
 year = {2016},
 isbn = {978-1-4503-3900-1},
 location = {Austin, Texas},
 pages = {321--332},
 numpages = {12},
 url = {http://doi.acm.org/10.1145/2884781.2884857},
 doi = {10.1145/2884781.2884857},
 acmid = {2884857},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {classification techniques, experimental design, parameter optimization, software defect prediction},
} 
```
## Additional Results for the logLoss performance measure

- [RQ1-1 Classifier Sensitivity](results/RQ1-ClassifierSensitivity-logLoss.pdf)

- [RQ1-2 Parameter Sensitivity](results/RQ1-ParameterSensitivity-logLoss.pdf)

- [RQ2-1 Classifier Stability](results/RQ2-Stability-logLoss.pdf)

- [RQ2-2 Parameter Stability](results/RQ2-ParameterStability-logLoss.pdf)

## Additional Results when dropping the NASA datasets (i.e., JM1 and PC5)

- [RQ1-1 Classifier Sensitivity](results/RQ1-ClassifierSensitivity-no-NASA.pdf)

- [RQ1-2 Parameter Sensitivity](results/RQ1-ParameterSensitivity-no-NASA.pdf)

- [RQ2-1 Classifier Stability](results/RQ2-Stability-no-NASA.pdf)

- [RQ2-2 Parameter Stability](results/RQ2-ParameterStability-no-NASA.pdf)
