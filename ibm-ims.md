# IBM Information Management System

* The IBM Information Management System (IMS) is a **hierarchical** database that is **commercial**, not open-source. Their website can be found at [this link](https://www.ibm.com/products/ims).
* This database can be hosted through **client/server and embedded** options, as it is built for a widespread, organizational use.
* Similar to the IBM Cloudant discussed in the `cloudant.md` file, IBM IMS allows Java access through the **64-bit IBM Java (SDK)**.  [This community post](https://community.ibm.com/community/user/ibmz-and-linuxone/blogs/carlos-alvarado1/2022/02/16/31-bit-cobol-can-now-talk-to-64-bit-java) dives into the development of this expansion to include Java and how it connects to an older compiler.

**How this data model is different from the others**
* Not only is the IBM IMS different from the other databases that have been discussed because it is jointly a hierarchical database *as well as* an information management system, but it is different through its data model as well.
* The previous databases included relational, multi-model, and document-oriented data models while this IMS is hierarchical.
* Since this database is meant to be used with customer information, child nodes or "segments" (according to [this Wikipedia page](https://en.wikipedia.org/wiki/IBM_Information_Management_System)), are nested underneath parent segments that contain other useful information.
* This database structure also allows for detailed, quick access to necessary information, which is especially important on the client-side and for the transactions handled by this system.
