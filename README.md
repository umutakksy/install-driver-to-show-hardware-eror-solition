# **Guide to Install Intel VMD Driver During Windows Installation**

This guide explains how to resolve the Intel VMD driver error during Windows installation.

---

## **Requirements**
- A bootable USB drive with the Windows ISO file.
- **Intel VMD driver files** (in a ZIP format).

---

## **Step 1: Copy Intel VMD Files to the USB Drive**
1. **Extract the Intel VMD ZIP file**:
   - Extract the ZIP file to a folder on your computer.
2. Copy the extracted files to your **Windows installation USB drive**:
   - Ensure the files are placed in an easily accessible location on the USB drive.

---

## **Step 2: Boot from the USB Drive**
1. Set your computer to boot from the USB drive:
   - You may need to adjust the **boot order** in your BIOS/UEFI settings.

---

## **Step 3: Resolving the Driver Error**
1. During the Windows installation, if you encounter an error, click on **Browse**.
2. To select the Intel VMD driver, follow these steps:
   - Locate the **Intel VMD folder** on the USB drive.
   - Inside, you may see options like:
     - **Intel**
     - **Non-Intel**
   - Select the **Intel** option.

3. Uncheck **Show compatible drivers only**:
   - This will display all driver options.

4. Choose the **Managed Controller** driver.

---

## **Step 4: Proceed with Windows Installation**
1. After loading the correct driver, proceed with the Windows installation as usual.

---

By following this guide, you can easily resolve the Intel VMD error and complete your Windows installation successfully!
