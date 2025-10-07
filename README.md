# 📊 Z-test Mastery Hub 🚀

<div align="center">

![Statistics](https://img.shields.io/badge/Statistics-Z--test-blue)
![Python](https://img.shields.io/badge/Python-3.8%2B-green)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-yellow)

**Your ultimate playground for mastering Z-tests!** ✨

*Unlock the power of statistical testing with hands-on examples and real-world applications*

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Prachi005748/Z-test-Practice)
[![Download Notebooks](https://img.shields.io/badge/Download-Notebooks-brightgreen)](./notebooks/)

</div>

## 🌟 What's Inside?

### 🎯 Core Features
| Feature | Description | Emoji |
|---------|-------------|--------|
| **📖 Theory Made Simple** | Easy-to-understand Z-test concepts | 📚 |
| **💻 Ready-to-Run Code** | Python implementations with examples | 🐍 |
| **🎓 Practice Problems** | Hands-on exercises with solutions | ✅ |
| **📊 Real Datasets** | Practical applications on real data | 🗃️ |
| **📈 Visualization** | Beautiful graphs and charts | 📉 |

### 🚀 Quick Start

```bash
# Clone and explore in 60 seconds! ⏰
git clone https://github.com/Prachi005748/Z-test-Practice.git
cd Z-test-Practice
pip install -r requirements.txt
jupyter notebook
```

## 📚 Learning Path

### 🎪 Step 1: Z-test Fundamentals
```python
# 🎯 One-sample Z-test Magic!
from scipy.stats import norm
import numpy as np

def z_test_showcase():
    sample = np.random.normal(100, 15, 50)  # 🎲 Generate sample
    z_score = (np.mean(sample) - 100) / (15/np.sqrt(50))
    p_value = 2 * (1 - norm.cdf(abs(z_score)))
    
    print(f"🎯 Z-Score: {z_score:.3f}")
    print(f"📊 P-Value: {p_value:.4f}")
    print("✨ Significant!" if p_value < 0.05 else "💤 Not Significant")
```

### 🏆 Step 2: Real-world Scenarios
| Scenario | Dataset | Test Type |
|----------|---------|-----------|
| 🍫 Chocolate weight quality control | `chocolate_weights.csv` | One-sample Z-test |
| 🎓 Student performance comparison | `test_scores.csv` | Two-sample Z-test |
| 🏥 Drug effectiveness study | `medical_trial.csv` | Proportion Z-test |

## 🎨 Interactive Examples

### 📈 Visual Hypothesis Testing
```python
import matplotlib.pyplot as plt
import seaborn as sns

# 🎨 Create beautiful visualization
def plot_z_distribution():
    fig, ax = plt.subplots(figsize=(10, 6))
    x = np.linspace(-4, 4, 1000)
    y = norm.pdf(x)
    
    ax.plot(x, y, 'b-', linewidth=2, label='Standard Normal')
    ax.fill_between(x[x>1.96], y[x>1.96], alpha=0.3, color='red', label='Rejection Region')
    ax.fill_between(x[x<-1.96], y[x<-1.96], alpha=0.3, color='red')
    
    plt.title('🎯 Z-test Critical Regions (α=0.05)')
    plt.legend()
    plt.show()
```

## 📂 Repository Structure
```
Z-test-Practice/
│
├── 📁 notebooks/           # Jupyter notebooks with examples
│   ├── 01_ztest_basics.ipynb
│   ├── 02_real_world_applications.ipynb
│   └── 03_advanced_topics.ipynb
│
├── 📁 datasets/           # Practice datasets
│   ├── chocolate_weights.csv
│   ├── student_scores.csv
│   └── medical_trial.csv
│
├── 📁 scripts/           # Python scripts
│   ├── ztest_calculator.py
│   └── visualization.py
│
├── requirements.txt      # 📦 Dependencies
└── README.md            # You are here! 🎉
```

## 🎯 Practice Challenges

### 🥇 Beginner Level
- [ ] Calculate Z-score for sample data
- [ ] Interpret p-values
- [ ] One-sample Z-test implementation

### 🥈 Intermediate Level  
- [ ] Two-sample Z-test comparison
- [ ] Confidence interval calculation
- [ ] Effect size measurement

### 🥇 Advanced Level
- [ ] Power analysis
- [ ] Multiple testing correction
- [ ] Real research data analysis

## 🤝 Join Our Learning Community!

<div align="center">

### 🌈 Contributors Welcome!
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)
[![Open Issues](https://img.shields.io/github/issues/Prachi005748/Z-test-Practice)](https://github.com/Prachi005748/Z-test-Practice/issues)

**Made with ❤️ by [Prachi](https://github.com/Prachi005748)**

⭐ **Star this repo if you find it helpful!** ⭐

</div>

## 📬 Get in Touch
- 🐛 **Found a bug?** [Open an Issue](https://github.com/Prachi005748/Z-test-Practice/issues)
- 💡 **Have an idea?** [Suggest a Feature](https://github.com/Prachi005748/Z-test-Practice/issues)
- 📚 **Want to contribute?** Check out our [Contributing Guidelines](CONTRIBUTING.md)

---

<p align="center">

### 🎊 Start Your Z-test Journey Today!
**From zero to statistical hero!** 🦸‍♀️

[**Explore Notebooks**](./notebooks/) | [**Try Examples**](./scripts/) | [**Practice Now**](./datasets/)

</p>

---

