# NumPy Fundamentals

A hands-on collection of NumPy concepts, practiced and implemented in Google Colab as part of my journey into Data Science and Machine Learning. NumPy is the foundation for almost every ML/DL library (Pandas, Scikit-learn, TensorFlow), so this repo focuses on building strong fundamentals — array manipulation, broadcasting, and vectorized operations — before moving into ML model building.

## 📌 Topics Covered

**Array Basics**
- Array creation: `np.array`, `np.zeros`, `np.ones`, `np.arange`, `np.linspace`, `np.eye`
- Array attributes: `shape`, `ndim`, `size`, `dtype`, `itemsize`
- 1D, 2D, and 3D array creation and understanding dimensions

**Indexing & Slicing**
- Basic indexing and slicing on 1D/2D/3D arrays
- Boolean indexing (filtering data using conditions)
- Fancy indexing (selecting specific elements using index arrays)

**Reshaping & Manipulation**
- `reshape`, `ravel`, `flatten` — converting array dimensions
- `concatenate`, `vstack`, `hstack`, `split` — combining and splitting arrays
- Transpose and axis manipulation

**Mathematical & Statistical Operations**
- Element-wise arithmetic operations
- Broadcasting — performing operations on arrays of different shapes
- Aggregate functions: `sum`, `mean`, `median`, `std`, `var`, `min`, `max`
- Sorting and searching: `np.sort`, `np.argmax`, `np.argmin`, `np.where`

**Random Module**
- Generating random numbers/arrays: `np.random.rand`, `randn`, `randint`
- Seeding for reproducibility (`np.random.seed`)

## 🎯 Why This Repo?

While learning NumPy, most tutorials skip the "why" behind broadcasting and vectorization — this repo documents my practice notebooks where I worked through each concept manually with examples, to build intuition before applying them in real ML preprocessing tasks (as part of CampusX's 100 Days of ML playlist).

## 🛠️ Tech Stack
- Python 3
- NumPy
- Google Colab

## 📂 Files
| File | Description |
|---|---|
| `numpy_basics.ipynb` | Core array creation, indexing, slicing |
| `numpy_broadcasting.ipynb` | Broadcasting rules with examples |
| `numpy_practice.ipynb` | Practice problems and mini exercises |

## 🔗 Related Repos
- [pandas-fundamentals](link) — Pandas practice notebooks
- [placement-predictor-ml](link) — End-to-end ML project using these fundamentals
