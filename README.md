# DiabetesMed AI — Portfolio Website

## 🗂️ File Structure

Your website folder should look like this:

```
your-repo/
├── index.html          ← The main website file
├── README.md           ← This file
└── images/             ← Create this folder manually
    ├── class_distribution.png
    ├── missing_values.png
    ├── univariate_analysis.png
    ├── correlation_heatmap.png
    ├── top_ten_diagnosis.png
    ├── outlier_detection.png
    ├── roc_curves.png
    ├── confusion_matrices.png
    ├── confusion_matrices_knn_xgboost.png
    ├── f1_vs_desc1.png
    ├── f1_vs_desc2.png
    ├── f1_all_models.png
    ├── auc-roc_allmodels.png
    ├── precision_vs_recall.png
    ├── perfomance_metrics.png
    └── phase5__test_comparision.png
```

---

## 📁 Images to Upload

Create a folder called `images` inside your repo and add these files (rename them exactly as shown):

| Your filename                    | Rename to                          |
|----------------------------------|------------------------------------|
| class_distribution.png           | class_distribution.png             |
| missing_values.png               | missing_values.png                 |
| univariate_analysis.png          | univariate_analysis.png            |
| correlation_heatmap.png          | correlation_heatmap.png            |
| top_ten_diagnosis.png            | top_ten_diagnosis.png              |
| outlier_detection.png            | outlier_detection.png              |
| roc_curves.png                   | roc_curves.png                     |
| confusion_matrices.png           | confusion_matrices.png             |
| confusion_matrices_knn_xgboost.png | confusion_matrices_knn_xgboost.png |
| f1_vs_desc1.png                  | f1_vs_desc1.png                    |
| f1_vs_desc2.png                  | f1_vs_desc2.png                    |
| f1_all_models.png                | f1_all_models.png                  |
| auc-roc_allmodels.png            | auc-roc_allmodels.png              |
| precision_vs_recall.png          | precision_vs_recall.png            |
| perfomance_metrics.png           | perfomance_metrics.png             |
| phase5__test_comparision.png     | phase5__test_comparision.png       |

---

## 🚀 How to Host on GitHub Pages

### Step 1 — Create the Repository
1. Go to https://github.com and sign in
2. Click the **+** button (top right) → **New repository**
3. Name it: `ml-portfolio` (or any name you like)
4. Set it to **Public**
5. Click **Create repository**

### Step 2 — Upload Files
1. Inside your new repo, click **Add file** → **Upload files**
2. Upload `index.html`
3. Click **Commit changes**

### Step 3 — Create the Images Folder
1. Click **Add file** → **Create new file**
2. In the filename box, type: `images/placeholder.txt`
3. Add any text in the body (e.g., "images folder")
4. Click **Commit new file**
5. Now go into the `images/` folder and click **Add file** → **Upload files**
6. Upload ALL your PNG image files
7. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. In your repo, click **Settings** (top menu)
2. Scroll down to **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Under **Branch**, choose **main** and **/ (root)**
5. Click **Save**
6. Wait ~1-2 minutes, then refresh the page

### Step 5 — Get Your Website URL
- Your site will be live at:
  `https://YOUR-USERNAME.github.io/REPO-NAME/`
- Example: `https://najeyahwaseem05.github.io/ml-portfolio/`

---

## ✏️ Things to Customize Later

Open `index.html` in any text editor (Notepad, VS Code, etc.) and search for:

| What to find | What to change |
|---|---|
| `alert('Add your technical report PDF link here!')` | Replace with: `window.open('YOUR_PDF_LINK', '_blank')` |
| `alert('Add your presentation slides link here!')` | Replace with: `window.open('YOUR_SLIDES_LINK', '_blank')` |
| `alert('Add your demo video link here!')` | Replace with: `window.open('YOUR_VIDEO_LINK', '_blank')` |
| `→ Profile Coming Soon` buttons | Add `href="YOUR_PROFILE_URL"` to those anchor tags |

---

## 🌐 No images showing?

Make sure:
- Image filenames match **exactly** (case-sensitive, including underscores)
- Images are inside a folder named exactly `images` (lowercase)
- The `images` folder is at the **root** of your repo, same level as `index.html`
