# The sync Command repo:
Here is the list of folders and their matched paths that are synced.

1. format: rsync -avP /src/folder/ /dest/folder/
2. add `--delete` to delete if file in destination is not at source
3. add `--dry-run` to test the files transfers

ssh root@ynas.fish-silverside.ts.net

## 2025
1. Alaska2025 - 9thMarch2025


- **[Local > NAS]**
```bash
rsync -avP '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/Alaska2025 - 9thMarch2025/' 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/Alaska2025 - 9thMarch2025/'
```

- **[NAS > Local]**
```bash
rsync -avP 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/Alaska2025 - 9thMarch2025/' '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/Alaska2025 - 9thMarch2025/'
```


2. NikiEngaged - 9thMarch2025

- **[Local > NAS]**
```bash
rsync -avP '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/NikiEngaged - 9thMarch2025/' 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/NikiEngaged - 9thMarch2025/'
```

- **[NAS > Local]**
```bash
rsync -avP 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/NikiEngaged - 9thMarch2025/' '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/NikiEngaged - 9thMarch2025/'
```

3. RedwoodNP - 20thFeb2025

- **[Local > NAS]**
```bash
rsync -avP '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/RedwoodNP - 20thFeb2025/' 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/RedwoodNP - 20thFeb2025/'
```

- **[NAS > Local]**
```bash
rsync -avP 'root@YNAS:/mnt/user/blackhawk-photography-cache/2025/RedwoodNP - 20thFeb2025/' '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2025/RedwoodNP - 20thFeb2025/'
```

## 2024

1. BJPMeet2024 - 1stSep2024

- **[Local > NAS]**
```bash
rsync -avP \
'/Users/yashashgaurav/Documents/PhotosToEdit - Local/2024/BJPMeet2024 - 1stSep2024/' \
'root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2024/PhotosToEdit/BJPMeet2024 - 1stSep2024/'
```

- **[NAS > Local]**
```bash
rsync -avP 'root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2024/PhotosToEdit/BJPMeet2024 - 1stSep2024/' '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2024/BJPMeet2024 - 1stSep2024/'
```

2. ChandramitaUBC - 10thMay2024

- **[Local > NAS]**
```bash
rsync -avP \
'/Users/yashashgaurav/Documents/PhotosToEdit - Local/2024/ChandramitaUBC - 10thMay2024/' \
'root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2024/PhotosToEdit/ChandramitaUBC - 10thMay2024/'
```

- **[NAS > Local]**
```bash
rsync -avP \
'root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2024/PhotosToEdit/ChandramitaUBC - 10thMay2024/' \
'/Users/yashashgaurav/Documents/PhotosToEdit - Local/2024/ChandramitaUBC - 10thMay2024/'
```

3. 


## 2023

1. Yosemite'23 - 7thAug2023

- **[Local > NAS]**
```bash
rsync -avP "/Users/yashashgaurav/Documents/PhotosToEdit - Local/2023/Yosemite'23 - 7thAug2023/" "root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2023/PhotosToEdit/Yosemite'23 - 7thAug2023/"
```


- **[NAS > Local]**
```bash
rsync -avP 'root@YNAS:/mnt/user/blackhawk-photography-archives/Personal Photography/With 80D/2023/PhotosToEdit/Yosemite'23 - 7thAug2023/' '/Users/yashashgaurav/Documents/PhotosToEdit - Local/2023/Yosemite'23 - 7thAug2023/'
```