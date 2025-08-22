# REPORT AUDIT REPOSITORY TECHSTORE

1. Terdapat file gambar (.png .jpg)file logs, file css, file md, file scripts (.bat .sh) yang terdampar di root folder repositorynya.

2. bug visual tersebut disebabkan oleh index.html yang salah linking stylenya (seharusnya style.css bukan style.sss)

3. dengan menggunakan perintah git log --all -- debug.log sehingga menciptakan output berikut :
commit 06bb74f030131ba202ef20d383481e3afd63e242 (origin/about-us)
Author: iqbaljlldn iqbaljalaludin1309@gmail.com
Date:   Thu Aug 21 18:34:12 2025 +0700

**my second commits**

commit be72ca73cc36df6a616a8f43d82effbce5da9a55
Author: iqbaljlldn iqbaljalaludin1309@gmail.com
Date:   Thu Aug 21 18:22:42 2025 +0700

 **apa ya lupa**

commit 0d965c4cf6ec50d591d60fe937600492726e4c9f
Author: iqbaljlldn iqbaljalaludin1309@gmail.com
Date:   Thu Aug 21 18:17:26 2025 +0700

**MY SECOND COMMITS TERDAPAT PADA BRANCH ABOUT US, JADI:KITA LIAT Commitan "apa ya lupa"**
**--> kita track filenya...**
3.  *API key terdapat pada commit : "apa ya lupa" dan ada di baris ke 4 : *

[2025-08-21 10:00:00] INFO: Server started successfully.

[2025-08-21 10:05:12] DEBUG: Processing request for image banner.jpg.

[2025-08-21 10:05:15] CRITICAL: API connection failed. Using fallback key for auth.

**[2025-08-21 10:05:16] DEBUG: Auth details - User: admin, Key: xA-tOpSecReT-12345**

[2025-08-21 10:06:00] INFO: Request completed.