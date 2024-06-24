Comandos proyecto
personal@ggarcia MINGW64 ~
$ cd Desktop/

personal@ggarcia MINGW64 ~/Desktop
$ cd iqtree-2.3.4-Windows/

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows
$ cd bin/

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows/bin
$ ls
 iqtree2.exe*   iqtree2-click.exe*   libiomp5md.dll*   muscle-I20240624-002233-0780-5455978-p1m.aln-fasta  'Secuencias proyecto final.1.txt'

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows/bin
$  ./iqtree2.exe -h
bash: ./iqtree2.exe -h: No such file or directory

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows/bin
$  ./iqtree2.exe -v
bash: ./iqtree2.exe -v: No such file or directory

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows/bin
$ chmod +x iqtree2.exe

personal@ggarcia MINGW64 ~/Desktop/iqtree-2.3.4-Windows/bin
$ ./iqtree2.exe -v
$ ./iqtree2.exe -s "muscle-I20240624-002233-0780-5455978-p1m.aln-fasta" -m MFP -bb 1000 -alrt 1000

$ ./iqtree2.exe -s "muscle-I20240624-002233-0780-5455978-p1m.aln-fasta" -m MFP -bb 1000 -alrt 1000
 cd ProyectoFinalBio24/
$ git remote -v
$ cd results/
$ git add .
$ git status
$ git commit -m "Foto para pryecto"



