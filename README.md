# AI in Space Applications II: Build the Thinking Spacecraft · Labs

The four hands-on labs of Astronify's course **AI in Space Applications II: Build the Thinking Spacecraft** ([astronify.org](https://astronify.org)). Each lab is a Google Colab notebook that runs on the free tier. You build, test and defend the onboard brain of VEGA-1, a 6U Earth-observation CubeSat.

| Lab | After | What you do | Open |
|---|---|---|---|
| 1. Honest clouds | Lesson 8 | Train a small cloud model on real Sentinel-2 chips, score it with a random split and a split by region, and set its send-or-discard line from stated costs | [Open in Colab](https://colab.research.google.com/github/Astronify-SpaceTech/ai-in-space-ii-labs/blob/main/lab1_honest_clouds.ipynb) |
| 2. Shrink and time | Lesson 14 | Export to ONNX, quantize to INT8, benchmark honestly, fill the budget sheet, and flip one bit | [Open in Colab](https://colab.research.google.com/github/Astronify-SpaceTech/ai-in-space-ii-labs/blob/main/lab2_shrink_and_time.ipynb) |
| 3. Know when you don't know | Lesson 20 | Give the model an out-of-distribution score, test it on snow and damaged tiles, and write the safe-fail rule | [Open in Colab](https://colab.research.google.com/github/Astronify-SpaceTech/ai-in-space-ii-labs/blob/main/lab3_know_when_you_dont_know.ipynb) |
| 4. Prove it | Lesson 24 | Write one test per requirement, apply the rule of three, rerun cleanly and fill a model card | [Open in Colab](https://colab.research.google.com/github/Astronify-SpaceTech/ai-in-space-ii-labs/blob/main/lab4_prove_it.ipynb) |

## How to start a lab

1. Click **Open in Colab** for the lab.
2. In Colab, choose **File → Save a copy in Drive**. The link opens a temporary copy; your own copy keeps your edits.
3. Run the cells in order. When the setup cell asks to connect Google Drive, allow it: your models and results are kept in the Drive folder `AI_in_Space_II_labs`, where the next labs find them.

The data files download by themselves. Do the labs in order: Labs 2 to 4 start from what Lab 1 saves.

## Data

`vega1_train.npz` and `vega1_test.npz` are attached to the [data-v1 release](https://github.com/Astronify-SpaceTech/ai-in-space-ii-labs/releases/tag/data-v1). They are cut from CloudSEN12+ through Copernicus-Bench's Cloud-S2 subset (CC0). Contains modified Copernicus Sentinel data. Tiles marked "simulated" in the notebooks are made by the notebooks themselves.

## Use

The notebooks are © Astronify, shared for learners of the course. The full course, with its lessons, quizzes, graded assignments and capstone, is on [astronify.org](https://astronify.org).
