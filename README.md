Dapin M-Pesa POS Integration for Odoo 18
========================================

This module allows your Odoo Point of Sale (POS) system to accept and reconcile M-Pesa payments with ease. Developed by **Dapin Technologies**, it brings real-time mobile money integration directly into your Odoo POS workflow.



Features
--------
- ✅ **STK Push Integration**: Trigger M-Pesa push requests to customer phones directly from the POS.
- ✅ **Direct-to-Till or Paybill Support**: Accept payments sent directly to your Till or Paybill number — even without an STK push.
- ✅ **Unified Transaction Dashboard**: View and track all M-Pesa transactions — whether via STK push or direct Till/Paybill — in one place.
- ✅ **Auto-Reconciliation**: Payments are matched to POS orders automatically in real time.
- ✅ **Multi-Session Support**: Works with multiple POS terminals and cashier sessions.
- ✅ **Sandbox & Production Mode**: Seamlessly switch between Safaricom test and live environments.

**1. Direct-to-Till or Paybill Support**

<img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/b4bb96d0-16a0-426c-9c14-40c315265826" />


**2. STK Push Integration**

<img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/9387ced6-846d-43b0-b8dd-fbe07d20e3c5" />

**3. Unified MPESA Dashboard**

<img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/1f81b764-bbd6-47df-b35c-ecfbf204c0e5" />

**4. Easy POS configuration**

   <img width="1919" height="932" alt="image" src="https://github.com/user-attachments/assets/be2565a8-fe14-4208-b56c-4bdf141cd406" />

Installation
------------
1. Clone or download the `dapin_pos_mpesa` module into your Odoo `addons` directory.
2. Restart Odoo and update the Apps List.
3. Search for and install **Dapin M-Pesa POS Integration** from the Apps menu.

Configuration
-------------
1. Navigate to **POS Configuration** → Enable **M-Pesa Payments**
2. Enter your:
   - Shortcode (Till or Paybill)
   - Consumer Key & Secret
   - Passkey
   - API environment (Sandbox/Live)
3. Set your callback URLs in the Safaricom Developer Portal to point to your public Odoo instance.

Support & Contact
-----------------
**Dapin Technologies**  
📧 Email: info@dapintechnologies.com  
🌐 Web: https://dapintechnologies.com  
📞 Phone: +254 708 518 641

License
-------
AGPL-3
