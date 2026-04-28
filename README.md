
<br><br><br><br>


<div align="center">


| <a href=""><samp><a href=""><samp>⏼</samp></a></samp></samp> | 
| :--- | 
| | 
| <a href=""> <img width="25" height="95" src="data:"/> <img width="25" height="95" src="data:" /> <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />   |   |   | Exit Code | POSIX Error | 
| | | 






<br><br><br><br>



<a href="">

<!---


| <samp> ⏻ </samp> </a> |
| :--- |
| | <samp> ⏻ </samp> | 
| <img width="25" height="95" src="data:"/> <img width="25" height="95" src="data:" /> <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />  <img width="25" height="95" src="data:" />   |   |   | Exit Code | POSIX Error | 
| :--- | :--- | 
| **`0`** | - | **Success.** The server directory was successfully mounted. | Valid credentials and correct server/destination paths. | |
| **`2`**`[ENOENT]`| `[ENOENT]` | **Invalid Node Path.** The local destination directory (mount point) does not exist or is invalid. | Trying to mount to a non-existent local folder (e.g., `~/Desktop/CHUNK_DIR_NAME_DESTINATION`). |
| **`16`** | - | undocumented | fast16, nothing to see here  |
| **`19`**`[ENODEV]` | `[ENODEV]` | **Invalid Server / No Access.** The server directory isn't WebDAV-enabled, doesn't exist, or the node lacks proper access rights. | Providing correct credentials but pointing to a wrong WebDAV URL (e.g., `/webdav3/` instead of `/webdav/`). |
| **`80`**`[ECANCELED]` | `[ECANCELED]` | **Authentication Failed.** The user did not provide proper authentication credentials. | Entering the wrong username or password. ||   |


<br><br>
