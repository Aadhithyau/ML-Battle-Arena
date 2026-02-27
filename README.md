# ML-Battle-Arena
Helper codes for setting up the colab environment

# ML Battle Arena – Setup Helper

This repository contains helper code to prepare your Google Colab environment for the ML Battle Arena competition.

The goal of this setup is to:
- Mount Google Drive
- Verify dataset files
- Extract images
- Generate and save image embeddings

Once completed, you can start building your own models without worrying about setup errors.

---

## 📂 Required Files

Before running the helper code, upload the following files to your Google Drive (MyDrive):

- `mini_train.csv`
- `mini_test.csv`
- `mini_images.zip`

Do not rename the files.

---

## 🚀 How To Use

1. Open Google Colab
2. Create a new notebook
3. Open `setup_helper.txt` from this repository
4. Copy and paste each section into Colab
5. Run the cells one by one (top to bottom)

---

## 🧠 What Each Section Does

### 1️⃣ Mount Google Drive
Connects your Google Drive to Colab.

### 2️⃣ Check Files + Copy
Verifies that required files exist and copies them to the Colab runtime.

### 3️⃣ Unzip Images
Extracts the images from `mini_images.zip`.

### 4️⃣ Extract and Save Embeddings
Uses ResNet18 to generate image embeddings.
These embeddings are saved to your Google Drive and do not need to be generated again.

