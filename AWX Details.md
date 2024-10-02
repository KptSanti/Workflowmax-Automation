
**Logs Generation**

1. Creation of payment link upon approval (activate)  
2. When paying through AWX/WFM/XERO (reactivate and activate)  
3. When deleting a payment in WFM/XERO (deactivate)  
4. When deleting/cancelling an Invoice through WFM/XERO (deactivate)
5. Paying exceed amount to their outstanding balance (failed)
6. Paying to the inactive/deleted/expired payment link (failed)
7. When you disconnect AWX and create invoice then integrate back the AWX (failed)

Resync Conditions

- Active payment links with the same configuration should not create new or update payment links.
- Active payment links when resynced with different configurations should create new / update payment links depending on your configuration setup and deactivate the previous link.
- Active invoices in sync logs with deleted/expired payment links should create a new payment link based on your configuration.
- Paid invoices or inactive payments link should not create new or update payment links.
- Failed syncs only when resynced should create new/update payment links based on your configuration.
- If failed status has recent payment link and its latest sync logs is inactive/active when resync it should not create a new or update payment link

Failed Logs Message:

1.  When you integrate AWX, then suddenly disconnect the integration, and then re-integrate, the invoices you created while you were disconnected will also try to create a new payment link but will fail. This is because the integration is not able to recognize the invoices that were created while it was disconnected.   
    **Message**: Failed to create payment link, token expired / no airwallex setup found  
    
2. When you try to pay in WFM/XERO but the link was inactive/expired.  
    **Message:** The payment link status is inactive and invalid for operations  
    
3. When the user try to pay over than their amount in Invoice:  
    **Message**: The payment cannot be imported as it exceeds the remaining outstanding balance
Greetings! I am a fifth year Architecture student at Sorsogon State University and currently working on my undergraduate thesis entitled " Proposed Campus for College of Science and Medicine at Sorsogon State University" in compliance for our course, I would like to formally ask if there are available data regarding the: 1. Population of STEM (Science, Technology, Engineering, and Mathematics) Students in the Province of Sorsogon from 2018 - 2024 Hoping for your kind consideration, Thank you.