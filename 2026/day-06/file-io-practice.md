# Day 06 – Linux Fundamentals: Read and Write Text Files

## Step 1: Create a File
- touch notes.txt -
  creates an empty file

  <img width="907" height="122" alt="image" src="https://github.com/user-attachments/assets/7a933947-a38e-4c15-91c0-54073103f9b1" />

## Step 2: Write First Line
- echo "this is line 1" > notes.txt -
  - echo - prints the text
  - > writes to the file (overwrite evrything)
  <img width="645" height="127" alt="image" src="https://github.com/user-attachments/assets/b7f75f0a-3289-4b85-a329-4e4d4e9d207a" />

## Step 3: Append Second Line
- echo "this is line 2" >> notes.txt -
  - >> append the content to the file

## Step 4: Append Third Line using tee
- echo "This is Line 3" | tee -a notes.txt -
  writes to the file and displays output on terminal on the same time
  <img width="757" height="122" alt="image" src="https://github.com/user-attachments/assets/53765be4-5070-409a-9928-757eedabc7a3" />

## Step 5: Read Full File
 - cat - displays full file content
   <img width="491" height="130" alt="image" src="https://github.com/user-attachments/assets/d1f2671e-2c37-4b6c-8d4a-153700916f49" />

## Step 6: Read First Few Lines
- head -n 2 notes.txt -
   shows first 2 lines
  <img width="483" height="106" alt="image" src="https://github.com/user-attachments/assets/b99e4642-4ef7-4017-8f38-fbd14a8d8e44" />

## Step 7: Read Last Few Lines
 - tail -n 2 notes.txt -
   shows last 2 lines
   <img width="440" height="113" alt="image" src="https://github.com/user-attachments/assets/8000704c-4878-49f7-ad1a-48fc53954748" />


