How to Use LySpoon 2.0 in Linux?
Platform: Fedora 3.9.6-200.fc18.x86_64

1.Download:
http://nlp.zzu.edu.cn/LySpoon.asp
Click "LySpoon2.0源代码" to download it.
2.unzip it, you will get a file folder "LySpoon2.0"
3.rename "LySpoon2.0" to "LySpoon"
4.Now you can get my patch file from my GitHub:
https://github.com/sfyoung/patch_to_run_LySpoon_2.0_on_Linux
5.Make sure the file of patch is in the parent directory of LySpoon, 
cd LySpoon and run follow command in terminal:
$ patch -p1 <../patch_to_run_LySpoon_2.0_on_Linux
7.Open idle in terminal, the pwd is the parent directory of LySpoon
$ idle
and the choose file->open, and open the file:
LySpoon/GUI/Experiment/Experiment.py
then press F5, run it. 
:)Good Luck to you.
