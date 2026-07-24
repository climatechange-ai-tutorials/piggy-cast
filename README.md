# PiggyCast - Improving Weather Prediction Accuracy through a Stacking-Based Ensemble AI Approach
Accurate weather prediction is fundamental to understanding and adapting to the impacts of climate change. As our climate shifts, the frequency and intensity of extreme weather events are changing, making reliable forecasts more critical than ever.
This tutorial introduces PiggyCast, an ensemble machine learning model designed to improve weather prediction accuracy by stacking forecasts from various numerical, AI-based, and hybrid weather prediction models. We demonstrate how a combined approach, using gradient-boosted decision trees (XGBoost), can surpass the predictive performance of individual base models.

The main contributions of this tutorial are:

1. **Developing and assessing an ensemble model:** We build and evaluate PiggyCast, a stacking-based ensemble model that leverages forecasts from state-of-the-art weather prediction models (IFS HRES, GraphCast, Pangu Weather, and NeuralGCM) and trains an XGBoost regressor on top of them to produce more accurate predictions of geopotential height at 500 hPa.
2. **Investigating feature importance:** We use SHAP (SHapley Additive exPlanations) values to analyze the contribution of each base model's forecast and geographic coordinates to PiggyCast's predictions, providing insights into the model's decision-making process.

Author(s):
- Josiah Kiarie Kimani - African Institute for Mathematical Sciences (AIMS) South Africa, [josiah@aims.ac.za](josiah@aims.ac.za)
- Oliver Angélil, PhD - Ishango AI
- Chris Toumping Fotso - Ishango AI
- Steffen Knoblauch - Heidelberg University

Originally presented at the CCAI Tackling Climate Change with Machine Learning Workshop at NeurIPS 2025.

## Access this tutorial

We recommend executing this notebook in a Colab environment to gain access to GPUs and to manage all necessary dependencies. <a target="_blank" href="https://colab.research.google.com/drive/1W31BqzM0izzH4jHpt_W2qBVD_cvCGPVI">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Estimated time to execute end-to-end: 30 minutes 

## Contribute to this tutorial

Please refer to these [GitHub instructions](https://docs.github.com/en/get-started/exploring-projects-on-github/contributing-to-a-project#about-forking) to open a pull request via the "fork and pull request" workflow. 

Pull requests will be reviewed by members of the Climate Change AI Tutorials team for relevance, accuracy, and conciseness.

## Climate Change AI Tutorials
Check out the [tutorials page](https://www.climatechange.ai/tutorials?) on our website for a full list of tutorials demonstrating how AI can be used to tackle problems related to climate change.

## License
Usage of this tutorial is subject to the MIT License.

## Cite

### Plain Text
Kimani, J., Angélil, O., Toumping, C., and Knoblauch, S. (2026). PiggyCast - Improving Weather Prediction Accuracy through a Stacking-Based Ensemble AI Approach [Tutorial]. In Tackling Climate Change with Machine Learning Workshop at NeurIPS 2025. Climate Change AI.

### BibTeX

```
@misc{jkimani2026piggycast,
  title={PiggyCast - Improving Weather Prediction Accuracy through a Stacking-Based Ensemble AI Approach
},
  author={Kimani, Josiah and Angélil, Oliver and Toumping, Chris and Knoblauch, Steffen},
  year={2026},
  organization={Climate Change AI},
  type={Tutorial},
  booktitle={Tackling Climate Change with Machine Learning Workshop at NeurIPS 2025},
  howpublished={\url{https://github.com/climatechange-ai-tutorials/piggy-cast}}
}
```
