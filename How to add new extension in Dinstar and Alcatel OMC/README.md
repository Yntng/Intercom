# 🔧 Configuring a Dinstar Port and Extension number Integrating with Alcatel OMC

Follow these steps to add and configure a new port and extension number in Dinstar and connect it with the Alcatel OmniPCX system via OMC.

---

## 🛠️ Step-by-Step Instructions

### 1. Access Dinstar Web Interface
- Open your browser and log in to the **Dinstar** device using the correct credentials.

![Alt text](images/Credential.png)

### 2. Add a New Port
- Click on **Add Port**.

![Alt text](images/add%20port%20in%20Dinstar.png)

- Assign the **Extension Number** to the available port.

- Enter the **New Extension Number** you’ve planned in the placeholder of **Primary SIP User ID and Primary Authenticate ID** (e.g., `303`).

![Alt text](images/Choose%20Port%20in%20Dinstar.png)

- Click **Save**.
---

## 🧩 Configure the Same Extension in OMC

### 3. Open OMC (OmniPCX Office Management Console)
- Log in to **OMC**.

### 4. Open Subscriber/Basestation
- to add new extension open subscriber/basestation 

![Alt text](images/Open%20subscriber%20in%20OMC.png)

### 5. Add a New Extension
- Click on **Add**.

![Alt text](images/Add%20extension.png)

- Enter the **New Extension Number** you’ve planned (e.g., `303`).

![Alt text](images/Put%20extension%20in%20OMC.png)

![Alt text](images/Add%20extension%202.png)

- Click **OK**.


### 6. Return to Subscriber List
- You’ll be taken back to the **Subscribers** list.
- The new extension will appear there.

### 7. Change Device Type to Open SIP Phone in Terminal
- By default, the extension will be set as **IP Enabler**.

![Alt text](images/IP%20Enabler.png)

- Change the type from **IP Enabler** to **Open SIP Phone**.

![Alt text](images/Terminal%20Open%20SIP%20Phone%20in%20OMC.png)

- click **Modify** to access its configuration settings.

![Alt text](images/Open%20SIP.png)

---

## ✅ Extension is added!
The extension is now added and ready for SIP configuration or registration with a compatible SIP device.

### 9. Edit Extension Number Details
- Select the extension number you just added and either:
  - Click **Details**, or
  - Double-click the extension number to open its settings.

![Alt text](images/Open%20SIP.png)

### 10. Go to IP/SIP Settings
- In the port settings, go to the **IP/SIP** tab.

![Alt text](images/Subscriber%20details%20and%20IP%20SIP.png)

### 11. Open SIP Parameters
- Click on the **SIP Parameter** section.

### 12. Copy SIP Password
- Locate and **copy the SIP Password** from this section.

![Alt text](images/SIP%20Parameters%20and%20copy%20password%20in%20OMC.png)

- Click **OK** to close the dialog.
- Click **OK** again to confirm.

---

## 🔁 Finalize Dinstar Configuration

### 13. Return to Dinstar
- Go back to the port settings in **Dinstar**.

### 14. Reopen the New Port added
- Select the port, **Modify the newly created port** for further configuration.

![Alt text](images/Select%20Port%20in%20Dinstar.png)

### 15. Paste SIP Password
- Paste the copied SIP Password into the **Primary Authentication Password** field.

![Alt text](images/Copy%20password%20from%20SIP%20Server%20in%20Dinstar.png)

### 16. Save Configuration
- Click **Save**.

---

## ✅ Done!
- The port is now configured and linked to the Alcatel system.
- You’re all set!

---

