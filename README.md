# resume
import docx2txt
import os
print(f'{os.getcwd()}')

# replace following line with location of your .docx file
MY_TEXT = docx2txt.process("./Desktop/docx2txt/resume_marysumithra.docx")-


with open("Output.txt", "w") as text_file:
    print(MY_TEXT, file=text_file)
