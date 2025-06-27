# Kaggle 卡路里消耗预测项目

## 写在前面：
这是我尝试的第一个 Kaggle 项目，它是一个playground series competition。
其实在开始之前，我完全没有接触过一点machine learning，但是偶然看到这个感觉挺有趣的就想尝试一下（一开始甚至不知道有截至时间）。
然后就从ml最基础的概念，模型，workflow开始学。虽然最后因为一些备考和其他事情一直中断，加起来断断续续总共学了不到两周吧，也只是做到了解了简单的基本模型和workflow, 借助大模型勉勉强强只是做到了完成了☹️。
它一点也不完美，但它依然是我第一次，值得记录的尝试。

Anyway, take ur time🫶
希望以后可以做出自己满意的project!


---

## Tech Stack
* **语言**: Python
* **库**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost, LightGBM

---

## My Workflow
1.  **数据探索 (EDA)**: 对数据进行了可视化分析，探索了特征分布和特征之间的相关性。
2.  **特征工程 (Feature Engineering)**: 创建了如 BMI、年龄分组、体重分组以及一些交互特征来尝试提升模型性能。
3.  **模型训练**: 分别训练了 XGBoost 和 LightGBM 两个强大的 Boosting 模型。
4.  **模型融合**: 最终采用了简单平均法对两个模型的预测结果进行了融合，以获得更稳健的预测。

---

## Personal Reflections
作为我的第一个 Kaggle 项目，我学到了很多：
* **有始有终的重要性**: 即使因为备考和其他事情中断了，但最终还是完成了。虽然它不够好，但也是值得记录一次尝试。
* **EDA 的价值**: 通过数据可视化，我更直观地理解了数据。
* **Boosting 模型的强大**: 第一次接触并使用了 XGBoost 和 LightGBM，感受到了它们的威力。
* **社区学习**: 通过参考其他优秀的 Notebook，我学到了很多实用的技巧和代码规范。


---
