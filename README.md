# FB-ideology
Python package done for computing FB ideology score at NTUECON research group

Since the intermediate data created when computing ideology scores could also be worth studying in our research, this package is written to connect different stage of computation while being able to save the intermediate data and read them for continuing the ideology score calculation.


The package can be separated into four parts
1. base.py: Drives the main computation for fan page political ideology score from page_page_matrix using Principle Component Analysis. After having page ideology score, we can compute user's ideology score based on their likes on fan pages.

2. read.py: Reads the data and conduct the data preprocessing needed to the next step in our score calculation.

3. use.py: "fb_score" function that wraps up the package. After specifying the format of input and output, the program will check the format and run the computation.

4. write.py: Writes the data into csv files to save the intermediate data.

To look at the findings and results of our research, feel free to check out the readme file in repo NTU-Facebook-Project: https://github.com/Chunhsiang/NTU-Facebook-Project  or the full research paper:  https://kengchichang.com/paper/thesis-fb-paper.pdf.

If you are interested in our data and how we process them, please take a look at the repo of our workshop for more explaination with demo: https://github.com/Chunhsiang/NTU-FB_workshop-2017-10
