

### 🎟️ Ticket #003 – **"Cleaning the Mess: File Movement, Copying, and Renaming"**

#### 🧠 Scenario:

You’ve just received feedback from your lead data scientist: the project directory is cluttered, and you need to clean it up before the team begins running analytics.

Your job is to **organize the data**, **prepare a cleaned version**, and **archive old scripts** — all via terminal.

---

### 📝 Tasks:

---

#### 📂 **1. Organize the Data Folder**

* Inside the existing `data/` folder, create two new subfolders:

  * `raw/` → for untouched data
  * `cleaned/` → for cleaned/preprocessed data

> ✅ *Think:* What’s the command to create nested folders inside a directory you’re already in?

---

#### 📁 **2. Move Existing CSV Files into `raw/`**

Move the following files from `data/` to `data/raw/`:

* `january.csv`
* `february.csv`
* `march.csv`

> ✅ *Check:* After moving, these files should no longer appear when you run `ls` in the `data/` folder.

---

#### 🧪 **3. Prep a Cleaned File for Testing**

* Copy `january.csv` from `raw/` into `cleaned/`
* Rename the copied file to: `january_cleaned.csv`

> ✅ *Check:* `january_cleaned.csv` should only exist in `cleaned/`, and the original `january.csv` should remain untouched in `raw/`.

---

#### 💾 **4. Archive an Old Script**

* Navigate to the `scripts/` folder.
* Create a subfolder named `archive/`
* Rename the file `analyze_trends.py` to `analyze_trends_OLD.py`
* Move the renamed file into the `archive/` folder

> ✅ *Check:* The `scripts/` folder should now contain only `clean_data.py`, and `analyze_trends_OLD.py` should be inside `scripts/archive/`

---

#### 📋 **5. Final Validation**

In each of the following folders, list out their contents and verify your work:

* `data/`
* `data/raw/`
* `data/cleaned/`
* `scripts/`
* `scripts/archive/`



---

### ✅ Completion Checklist:

* [ ] Created `raw/` and `cleaned/` inside `data/`
* [ ] Moved all `.csv` files into `raw/`
* [ ] Copied and renamed `january.csv` to `january_cleaned.csv` in `cleaned/`
* [ ] Created `archive/` in `scripts/`, renamed and moved `analyze_trends.py`


---

