# 🧭 **XportOne – Official Documentation (F1 Help)**

Welcome to the official help center for **XportOne**, the plugin designed to optimize and automate sheet exports from Revit to **PDF** and **DWG** quickly, consistently, and without errors.

This documentation fulfills Autodesk App Store’s **Contextual Help (F1)** requirement.

---

# 📌 **1. About XportOne**

**XportOne** is an Autodesk Revit add-in that simplifies the sheet export workflow by enabling:

- Batch exporting of multiple sheets  
- Automatic generation of standardized **PDF** and **DWG** files  
- Configurable naming, prefixes, and output paths  
- Reduced manual work  
- Elimination of common export mistakes  

It is designed for engineering and architecture teams who need speed, consistency, and reliability in deliverables.

---

# 🚀 **2. How to Use XportOne**

### **Step 1 – Open the XportOne panel**
In Revit, go to:

> **Add-Ins → Export → Export PDF + DWG**

Click the **Export PDF + DWG** button.

---

### **Step 2 – Select the sheets**

The XportOne interface will show:

- A list of sheets in the project  
- Multi-selection checkboxes  
- Filters (discipline, naming patterns, prefixes)  

Select the sheets you want to export.

---

### **Step 3 – Configure export options**

You can configure:

- Output folder  
- File naming (automatic or custom)  
- Export **PDF**, **DWG**, or both  
- Automatic folder creation  
- Prefixes and suffixes  

---

### **Step 4 – Export**

Click **Export**.

XportOne will generate the files according to your settings, providing clear notifications about:

- Generated files  
- Possible errors  
- Output locations  

---

# ⚙️ **3. System Requirements**

- **Autodesk Revit 2025** (or compatible version listed in the App Store)  
- .NET 8 runtime included in Revit  
- Write permissions to the output folder  

---

# 📂 **4. Installation**

The plugin is installed through:

### ✔ Autodesk App Store (official package)  
OR  
### ✔ Manual installation

Place **XportOne.addin** and the `.bundle` folder into:

C:\ProgramData\Autodesk\Revit\Addins\2025\


Restart Revit afterward.

---

# 🧩 **5. Uninstallation**

To remove XportOne:

1. Close Revit.  
2. Delete:
   - `C:\ProgramData\Autodesk\Revit\Addins\2025\XportOne.addin`  
   - `C:\ProgramData\Autodesk\Revit\Addins\2025\XportOne.bundle\`  
3. Reopen Revit.

---

# ❗ **6. Troubleshooting**

### **The XportOne button does not appear**
- Make sure the add-in files are in the Addins folder.  
- Confirm the correct version (2025) is installed.  
- Try running Revit as administrator.  

---

### **The exporter window does not open**
- Windows may have blocked the DLL:  
  → Right-click → *Properties* → enable **Unblock**.  
- Antivirus software may be blocking the DLL.  

---

### **Some sheets do not appear in the list**
- Verify they are valid ViewSheets.  
- Dependent or template sheets are not listed.  

---

### **DWG export configuration looks incorrect**
- Adjust your DWG export template in Revit.  
- XportOne uses Revit’s active DWG export settings.  

---

### **PDF files are not generated**
- Check write permissions for the output folder.  
- Close any PDF files that are already opened.  

---

# 🔒 **7. Privacy and Data Handling**

XportOne **does not collect, store, or transmit** any user data.

You can read the full privacy policy here:

👉 **https://xportone.github.io/**

---

# 📘 **8. Licensing**

XportOne is distributed via the Autodesk App Store under the platform’s licensing terms.

---

# 🆘 **9. Technical Support**

If you encounter issues, need help, or have feature suggestions:

### 📧 **Support Email**  
**xportone.plugin@gmail.com**

### 🛠 Expected response time  
**24–48 business hours**

---

# 🎉 **Thank you for using XportOne!**

This plugin was built to make Revit exports faster, easier, and more reliable.  
We appreciate your support and feedback!
