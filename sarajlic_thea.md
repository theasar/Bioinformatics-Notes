hello
attempting to sync!

# 2/13/26 - Lab 4    
### Notes    
#### Exercise 4    
To find a hidden directory the command to use is   "ls -a" which means "all files"  

The hidden directory name is .hidden  

The hidden file is youfoundit.txt  

#### Exercise 3   
To list the contents of untrimmed_fastq directory from the home directory:   

ls gen711-811/shell_data/untrimmed_fastq/  

To find specific things within the directory, you can use "ls *"   

#### Exercise 2   
When nothing matches it will come back w/:    

ls: cannot access '*fq' : No such file or directory    

#### Relative path resolution     
../backup will bring you or show you what is in "backup"    

#### Exercise 1     
cd gen711-811/shell_data/untrimmedfast_q/    

#### Exercise 5   
The line number in my history for the command that listed all the .sh files in /usr/bin was 203 for me     

203 ls /usr/bin/*.sh   

To rerun I would do: !203    
   
#### Exercise 8   
less -S SRR097977.fastq  

CAC   
    
#### Exercise 9
   
mkdir backuo   

cp SRR098026.fastq SRR098026-backup.fastq   

mv *backup.fastq backuo    

I accidentally named my backup directory "backuo" and went with it - sorry    



#### Other    

ls /usr/bin/c* | wc -l    

Counts the number of files in bin that have c in it     

To use a command from your history do !"number in history"    

"grep" looks through things | grep 'grep'    