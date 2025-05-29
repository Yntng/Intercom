# ✅ Assigning a DID Number to an Extension in OMC (Alcatel-Lucent OmniPCX Office)

This is a step-by-step guide using direct and practical instructions that match how the OMC interface works.

---

## 🔧 Step-by-Step Procedure

### 1. Go to **Numbering**

![Alt text](images/Numbering%20.png)

- Open **Numbering Plan** from the left-hand menu.

![Alt text](images/Open%20numbering.png)

- Then go to  **Public Numbering Plan** under **Numbering Plan** → **DID Ranges**.

- Assign the **Start** and **End** range for the DID numbers that match your internal base extension range.
  > Example: Start `0123456700`, End `0123456799` → for extensions `200-299`.

![Alt text](images/Assign%20DID%20%20to%20extension.png)

- Click **Add** (or **Modify** if you're updating an existing range).

- Set how many digits to match from the incoming DID (e.g., last 3 digits).
- Click **OK** to save.

---

### 2. Go to **Subscribers**

- Click on **Subscribers** from the main menu.

![Alt text](images/Open%20Subscriber%20list.png)

- Then open **Directory Numbers**.


### 3. Select the Subscriber (Extension)

- Find and **select** the extension you want to assign the DID to (e.g., `364`).
- Click **Modify**. (**Notes**- If you wish to modify extension number.)

![Alt text](images/Choose%20subscriber%20list%20in%20OMC.png)

### 4. Configure DID in **Details**

- Go to the **Details** tab and then to **Misc**
- Click **Ok** 

![Alt text](images/Misc%20and%20ok.png)

### 5. In **Misc** Tab

- Now go to the **Misc** tab.
-In the **Alternative CLIP/CLOP number** field, enter the **DID number** you've planned to assign (e.g., `0123456701`).

  ![Alt text](images/add%20DID%20number%20to%20the%20subscriber%20or%20extension.png)

Click **OK** to save.

---

### 6. Test the DID

- Call the DID number from an outside line by adding Single Zero (eg; **01892310818**) 
- If within the **Alcatel network** use double zero **00** (eg; **001892310818**)
- It should ring directly on the assigned extension.

---

## 📝 Summary

- **Numbering** → Set DID range linked to extension range.
- **Subscribers** → Open extension → **Details** → Add DID.
- **Misc** → Confirm additional settings.
- Test from external line.

---

