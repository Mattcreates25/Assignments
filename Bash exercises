# bash-assignment
Assignment 2: bash scripting exercise

### Question 1
How many processes are currently running on your system? Use ps and wc, the first line of output of ps is not a process!
```bash
ps -e | wc -l
```
__output__
```
236
```

### Question 2
Write a script that upon invocation shows the time and date, lists all logged-in users, and gives the system uptime. 
The script then saves this information to a logfile.

```bash
datetime= 'date'
users= 'who'
system='uptime'
  echo date and time: $datetime
  echo logged in users: $users
  echo system uptime: $system
  
```bash
bash datetime.sh> date.log
```
__output__
```
Tue 26 Jul 2022 11:10:06 AM EAT
icipe    :0           2022-07-26 08:06 (:0)
date and time:
logged in users:
system uptime: uptime
```
   
### Question 3
Which command would you use in order to create an empty file in the current directory, let's say empty.txt?

```bash
touch empty.txt
```
output
```2014-01-31_JA-africa.tsv    201403160_01_text.json   bin          do         '[file]'    hello-world   jiy          mkdir       R                       snap
 2014-01-31_JA-america.tsv   33504-0.txt              date.sh      Documents   firstdir   jimmy         __MACOSX     Music       shell-lesson-data       Videos
 2014-01_JA.tsv              829-0.txt                Desktop      Downloads   for        Jimmy        'man ls'      pg514.txt   shell-lesson-data.zip
 2014-02-02_JA-britain.tsv   anaconda3                diary.html   empty.txt   gulliber   jimy          miniconda3   Pictures    shell-lesson.zip

2014-01-31_JA-africa.tsv    201403160_01_text.json   bin          do         '[file]'    hello-world   jiy          mkdir       R                       snap
 2014-01-31_JA-america.tsv   33504-0.txt              date.sh      Documents   firstdir   jimmy         __MACOSX     Music       shell-lesson-data       Videos
 2014-01_JA.tsv              829-0.txt                Desktop      Downloads   for        Jimmy        'man ls'      pg514.txt   shell-lesson-data.zip
 2014-02-02_JA-britain.tsv   anaconda3                diary.html   empty.txt   gulliber   jimy          miniconda3   Pictures    shell-lesson.zip
 ```

### Question 4
You are in /home/icipe/  suppose this directory is empty. How do you create in only one command the whole path /home/icipe/Work/mini-project/RNA-Seq/?

```bash
mkdir -p home/icipe/Work/mini-project/RNA-Seq/
```
__output__
```
 2014-01-31_JA-africa.tsv    date.sh     '[file]'       jiy          Pictures                trial-11.data   trial-1.data    trial-9.data
 2014-01-31_JA-america.tsv   Desktop      firstdir      less         R                       trial-12.data   trial-20.data  'universal greetings.txt'
 2014-01_JA.tsv              diary.html   for           __MACOSX     seq.txt                 trial-13.data   trial-2.data    universal_greetings.txt
 2014-02-02_JA-britain.tsv   do           gulliber     'man ls'      shell-lesson-data       trial-14.data   trial-3.data    Videos
 201403160_01_text.json      Documents    hello-world   miniconda3   shell-lesson-data.zip   trial-15.data   trial-4.data
 33504-0.txt                 Downloads    home          mkdir        shell-lesson.zip        trial-16.data   trial-5.data
 829-0.txt                   dt.sh        jimmy         Music        snap                    trial-17.data   trial-6.data
 anaconda3                   empty.txt    Jimmy         output.txt  'test.fa?raw=T'          trial-18.data   trial-7.data
 bin                         error.txt    jimy          pg514.txt    trial-10.data           trial-19.data   trial-8.data
```

### Question 5
Suppose your current working directory contains a file named seqs.txt. How do you rename this file into sequences.fasta? 
Does this have any effect on the content of the file, and if yes, what does it do?

```bash 
mv seq.txt sequence.fasta
```
__0utput__
```
 2014-01-31_JA-africa.tsv    date.sh     '[file]'       jiy          Pictures                trial-11.data   trial-1.data    trial-9.data
 2014-01-31_JA-america.tsv   Desktop      firstdir      less         R                       trial-12.data   trial-20.data  'universal greetings.txt'
 2014-01_JA.tsv              diary.html   for           __MACOSX     sequence.fasta          trial-13.data   trial-2.data    universal_greetings.txt
 2014-02-02_JA-britain.tsv   do           gulliber     'man ls'      shell-lesson-data       trial-14.data   trial-3.data    Videos
 201403160_01_text.json      Documents    hello-world   miniconda3   shell-lesson-data.zip   trial-15.data   trial-4.data
 33504-0.txt                 Downloads    home          mkdir        shell-lesson.zip        trial-16.data   trial-5.data
 829-0.txt                   dt.sh        jimmy         Music        snap                    trial-17.data   trial-6.data
 anaconda3                   empty.txt    Jimmy         output.txt  'test.fa?raw=T'          trial-18.data   trial-7.data
 bin                         error.txt    jimy          pg514.txt    trial-10.data           trial-19.data   trial-8.data
```

### Question 6
How can you create in a single command a file containing the contents "Hello, world!" and named universal_greeting.txt?

```bash
echo "hello world"> universal_greetings.txt
```

```bash
echo "hello world"> universal_greetings.txt
```
__output__
```  2014-01-31_JA-america.tsv   829-0.txt     diary.html  '[file]'     home          __MACOSX     pg514.txt   shell-lesson-data.zip
 2014-01_JA.tsv              anaconda3     do           firstdir    jimmy        'man ls'      Pictures    shell-lesson.zip
 2014-02-02_JA-britain.tsv   bin           Documents    for         Jimmy         miniconda3   R           snap
 201403160_01_text.json      date.sh       Downloads    gulliber    jimy          mkdir        seq.txt     universal_greetings.txt
(base) icipe@icipe-HP-Z220-SFF-Workstation:~$ cd universal_greetings.txt
```

### Question 7
What about creating the same file but with filename "universal greeting.txt" (the filename contains a space)?

```bash
echo "hello world"> 'universal greetings'.txt
```
```  2014-01-31_JA-africa.tsv    33504-0.txt   Desktop      empty.txt   hello-world   jiy          Music       shell-lesson-data          universal_greetings.txt
 2014-01-31_JA-america.tsv   829-0.txt     diary.html  '[file]'     home          __MACOSX     pg514.txt   shell-lesson-data.zip      Videos
 2014-01_JA.tsv              anaconda3     do           firstdir    jimmy        'man ls'      Pictures    shell-lesson.zip
 2014-02-02_JA-britain.tsv   bin           Documents    for         Jimmy         miniconda3   R           snap
 201403160_01_text.json      date.sh       Downloads    gulliber    jimy          mkdir        seq.txt    'universal greetings.txt'
```

### Question 8
How can you use the commandline (on whichever machine you are now, that is connected to the internet) to download directly the 
file you can see on https://github.com/Fnyasimi/my-first-repo/blob/main/directory1/test.fa ? Be careful, you need to get the raw text file itself, 
not the full HTML page presenting it.

```bash
wget https://github.com/Fnyasimi/my-first-repo/blob/main/directory1/test.fa?raw=T
```
calling cat on the file that we've downloaded birnigs

```
>XM_021165122.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X6, mRNA
CTCGGCGGCGGCGGCGGCGGCAGAGGCGGCAGCGCTCGCCATTGCCGCTGGTGGCAGGAGGCTGCGAGGAGCCGGCGCGG
TCGCAGTCTCCACGGCGCAGGCCCACGGTAGCGCAGCCGCTCTGAGGTCGAATGATATGTGGTTCATGTAGACCACATTT
TGTTTCCCACTCACCCATTGATGGACACTTGGGTAGCTTCCATCTTTTGGCTGTTGTGAATAATGCTGCTATGAACATGG
GTGTGCACATAGCTCTCTGAGACGCTGCTTTCAGTCCTTCTGGTAGATCTTCATGGAGGAGCACGGAGTGACCCAAACTG
AACACATGGCTACCATAGAAGCCCATGCAGTGGCCCAGCAAGTCCAGCAGGTCCATGTAGCCACATACACTGAGCACAGT
ATGCTAAGTGCTGATGAAGACTCCCCTTCCTCCCCCGAGGACACTTCTTATGATGACTCTGACATCCTCAACTCCACGGC
AGCTGATGAGGTAACTGCCCATCTGGCTGCTGCAGGTCCTGTGGGAATGGCCGCTGCTGCTGCTGTGGCAACAGGGAAGA
AACGGAAACGGCCTCATGTGTTTGAGTCTAATCCATCTATCCGAAAGAGACAGCAGACACGTTTGCTTCGGAAACTCAGA
GCCACGTTGGATGAGTACACGACGCGAGTGGGACAGCAAGCGATTGTACTCTGCATCTCACCCTCCAAACCCAACCCCGT
CTTCAAGGTGTTTGGCGCAGCACCTTTGGAGAATGTGGTGCGAAAGTACAAGAGCATGATCCTGGAAGACCTGGAGTCAG
...
```

### Question 9
How can you count the number of lines in this text file (test.fa)? How do you count the number of sequences?

```bash
wc -l test.fa\?raw\=T 
```
__output__

```
10281 test.fa?raw=T
```

### Question 10
Extract only the identifier lines from this file, and write them into a file called "identifiers.txt".

```bash
grep -w ">*" test.fa\?raw\=true > identifiers.txt
```
__output__
```
>NM_001361694.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 9, mRNA
>NM_001361695.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 10, mRNA
>NM_001164226.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 1, mRNA
>NM_010938.4 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 6, mRNA
>AK082580.1 Mus musculus 0 day neonate cerebellum cDNA, RIKEN full-length enriched library, clone:C230066G05 product:nuclear respiratory factor 1, full insert sequence
>XM_021165121.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X5, mRNA
>XM_021165122.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X6, mRNA

```

### Question 11
How can you process the file you got from question 8 to replace all its uppercase "A" letters into lowercase "a" letters, leaving the rest untouched?

```bash
grep "A" test.fa\?raw\=T | tr [A] [a]
```
__output__
```
>XM_021165122.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X6, mRNa
CTCGGCGGCGGCGGCGGCGGCaGaGGCGGCaGCGCTCGCCaTTGCCGCTGGTGGCaGGaGGCTGCGaGGaGCCGGCGCGG
TCGCaGTCTCCaCGGCGCaGGCCCaCGGTaGCGCaGCCGCTCTGaGGTCGaaTGaTaTGTGGTTCaTGTaGaCCaCaTTT
TGTTTCCCaCTCaCCCaTTGaTGGaCaCTTGGGTaGCTTCCaTCTTTTGGCTGTTGTGaaTaaTGCTGCTaTGaaCaTGG
GTGTGCaCaTaGCTCTCTGaGaCGCTGCTTTCaGTCCTTCTGGTaGaTCTTCaTGGaGGaGCaCGGaGTGaCCCaaaCTG
```

### Question 12
In one command, ask for the display of all identifier lines from the same file test.fa without wrapping the lines, i.e. by having all lines displayed 
on your screen effectively start with the character '>'.

```bash
less -S identifiers.txt
```
__output__
```
>NM_001361694.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 9, mRNA
>NM_001361695.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 10, mRNA
>NM_001164226.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 1, mRNA
>NM_010938.4 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 6, mRNA
>AK082580.1 Mus musculus 0 day neonate cerebellum cDNA, RIKEN full-length enriched library, clone:C230066G05 product:nuclear respiratory factor 1, full insert sequence
>XM_021165121.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X5, mRNA
>XM_021165122.1 PREDICTED: Mus caroli nuclear respiratory factor 1 (Nrf1), transcript variant X6, mRNA
>AK029034.1 Mus musculus 10 days neonate skin cDNA, RIKEN full-length enriched library, clone:4732483G17 product:nuclear respiratory factor 1, full insert sequence
>AK014494.1 Mus musculus 14 days embryo liver cDNA, RIKEN full-length enriched library, clone:4432414E03 product:nuclear respiratory factor 1, full insert sequence
>NM_001361693.1 Mus musculus nuclear respiratory factor 1 (Nrf1), transcript variant 8, mRNA

```

### Question 13
Can you write a very short script (possibly one single commandline) to extract from the same file the species names?

```bash
cut -d ' ' -f2-4 identifiers.txt |cut -d : -f 2 | sed 's/^ *//g' | cut -d ' ' -f 1,2
```
__output__
```
Mus musculus
Mus musculus
Mus musculus
Mus musculus
Mus musculus
Mus caroli
Mus caroli
Mus musculus
Mus musculus
Mus musculus
Mus musculus
Mus musculus
Mus musculus
Mus pahari
Rattus norvegicus
Peromyscus maniculatus
Mus musculus
Mus musculus
```
### Question 14
Once this is done, how do you count the species names with their order of multiplicity 
(i.e. how many sequences belong to Mus musculus, how many to Homo sapiens, etc)?

```bash
 cut -d ' ' -f2-4 identifiers.txt |cut -d : -f 2 | sed 's/^ *//g' | cut -d ' ' -f 1,2 | uniq -c |sort -n
```
```
__output__
``` 1 Aotus nancymaae
      1 Aotus nancymaae
      1 Castor canadensis
      1 Cebus capucinus
      1 Ceratotherium simum
      1 Cercocebus atys
      1 Cercocebus atys
      1 Colobus angolensis
      1 Cricetulus griseus
      1 Cricetulus griseus
      1 Equus asinus
      1 Equus caballus
```
### Question 15
Write a loop in Bash producing all the integers from 1 to 30, one per line?

```bash
$ for numbers in 1 30 ; do seq $numbers ; done

```
__output__
```
1
1
2
3
4
5
6
7
8
9
10
11
12
13
14
15
16
17
18
19
20
21
22
23
24
25
26
27
28
29
30
```
### Question 16
Create at once 20 files called "trial1" to "trial20" and *then* rename them all by appending the suffix ".data". 
Of course, don't issue 20 commands, but just one.

```bash
touch trial-{1..20}.data
```
__output__
```
trial-10.data
 trial-11.data
 trial-12.data
 trial-13.data
 trial-14.data
 trial-15.data
 trial-16.data
 trial-17.data
 trial-18.data
 trial-19.data
 trial-1.data
 trial-20.data
 trial-2.data
 trial-3.data
 trial-4.data
 trial-5.data
 trial-6.data
 trial-7.data
 trial-8.data
 trial-9.data
```
or
```
touch $(seq -f "trial%g" 1 20) ; for f in trial* ; do mv "$f" $f.data ; done

```

### Question 17
Try this with the command "expr 1 / 0", whose purpose is to calculate the integer result of 1 divided by 0. What happens? Why?
```output
expr: division by zero
```
this is a command for division any number divided by 0 gives a syntax error.

### Question 18
How can you separately redirect the standard output and the standard error streams into two separate files?

```bash
cat seqdump.txt > output.txt 2>error.txt 
```


Try: sudo apt install <deb name>
```
the error file generates this out put if the initial command __cat__ is changed to an unidentified command eg. __catt__

### Question 19
Write a Bash script asking "What's your name?", then waiting for you (the user) to enter you name and press Enter, 
following what the program displays some text according to the following pattern:
"Good morning/day/evening, your_name!
It's now current_time on this lovely day of current_day." and it exits.

For instance, the message written by your program would be:
```
Good day Emmanuel! It's not 12:57EAT on this lovely day of July 20. 1:00
or 'Good morning" in the morning hours, or "Good evening" in the evening hours, depending on the current time.
Of course there will be at least an if or a case construct in your script.
```
```
echo "What is your name?"

read name


h=`date +%H`

if [ $h -lt 12 ]; then

    echo "Good morning $name"

elif [ $h -lt 18 ]; then

    echo "Good afternoon $name"

else

   echo "Good evening $name"

fi


current_time=`date +%T`
current_date=`date +%Y-%m-%d`


echo "It is now $current_time in the lovely day of $current_date"

```
calling the  nano script in bash will generate the output below 

__output__
```What is your name? <type in name>
Mark
Good afternoon Mark
It is now 12:58:08 in the lovely day of 2022-07-26
```
### Question 20
Suppose your current working directory is /home/icipe/Linux/Exercises/. What is the command that will enable to move to /home/icipe/Fun_stuff/?

```bash
cd ../../Fun_stuff/
```
this command takes you two directories back the path and moves you into the directory stuff/
