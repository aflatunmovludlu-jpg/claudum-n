# Video qaydası

İstifadəçi telefondan video göndərib edit/montaj istədikdə:

1. Hazır videonu `output/` qovluğuna aydın adla saxla (məs. `output/<mövzu>_edit.mp4`).
2. Videonu SendUserFile ilə istifadəçiyə göndər (`display: "attach"`), ki telefonda yükləyib Downloads/Qalereyaya saxlaya bilsin.
3. Videonu commit et və işlənən branch-a push et, ki bütün hazır videolar repoda toplansın.
4. GitHub fayl limiti 100 MB-dır: video bundan böyükdürsə keyfiyyəti az itirərək sıxışdır (məs. CRF-i artır), sonra commit et.
