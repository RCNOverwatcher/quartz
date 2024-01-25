---
banner: "![[computerscience.jpg]]"
---
# Transaction and Master files and serial and sequential files

> [!Info]
> Data storage on various devices, such as floppy disks, hard drives, and magnetic tape, involves decisions about file organization. Different methods of file organization impact the speed of data access. Files can be organized for direct access, where specific data can be retrieved quickly, or sequentially, where data is accessed in order. When deciding on file organization and storage devices, key considerations include the need for quick data retrieval and the intended purpose of the data.

> [!Info]
> **Serial Files:**
>    - Data in a serial file is stored in chronological order.
>    - Retrieving individual data items is a slow process, requiring sequential scanning.
>    - Serial files are suitable for applications where fast data access is not crucial.
 >  
 >  **Applications of Serial Files:**
>
 >  **a. Back-ups:**
 >    - Networks often back up data onto magnetic tape, as occasional data retrieval is sufficient.
 > 
 >**b. Shop Transactions:**
  >    - Shopkeepers maintain a transaction file (serial) to record daily sales.
   >   - The transaction file updates the master file, facilitating stock control and reordering.
>
 >  **c. Automatic Teller Machine (ATM):**
  >    - ATMs maintain a transaction file (serial) for daily transactions, batch processing it to update the master file.
>
  > **d. Payroll System:**
  >    - Employee clock-in/clock-out events are stored in a serial file, later sorted into a sequential file for efficient processing.
>
> **Sequential Files:**
  > - Organized based on a specific order other than time, such as product ID.
  > - Transactions for each product are grouped together before updating the master file.
>
> **Media for Serial and Sequential Files:**
  > - Both file types can be stored on magnetic tape, floppy disks, CD R/W, and hard disks.
  
  