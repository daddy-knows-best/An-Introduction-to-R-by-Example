# An-Introduction-to-R-by-Example
[LinkedIn](https://www.linkedin.com/posts/seung-yeop-yang_an-introduction-to-r-by-example-activity-7263360725224435712-ALJF?utm_source=share&utm_medium=member_desktop)

An Introduction to R by Example as Rnw

Another writing from me: "An Introduction to R by Example" that I have written in 2011 Summer. 

In 2011, I was interested in Statistics, and I wanted to have a programmable software tool that I can come up with statistical quality from small number of Voice Samples when I was working for VoIP Media Gateway Voice Quality.

I had surveyed the tools, and I found out a free software R, somehow I was connected with Korean R User Group just founded by Chel Hee Lee, and we tried to build the initial knowledge base for Korean R Users. At that time, I was interested in Literate Programming[1], and I found noweb[2], and its R equivalent package, Sweave[3], and then I was ready to write some of my own Literate Program for R.

When I took Summer vacation in 2011, I spent several days to try building the entire examples of "Introduction to R" tutorial as Sweave document/program, and posted in KRUG after the vacation.

Since I had to move out to Austin, TX to get a new job right after that, I couldn't have time to revise the document. Maybe someday...

I had a fun.

[1] Literate Programming, Don Knuth, CSLI, 1992

[2] https://github.com/nrnrnr, Norman Ramsey

[3] "Sweave: Dynamic Generation of Statistical Reports Using Literate Data Analysis", Leisch, Friedrich, 2002

p.s. This practice of literate programming influenced me, and I started using more templates, and graphing with R/gnuplot to visualize data into proper diagrams. 
<img width="1440" alt="Screenshot 2024-11-15 at 8 16 20 PM" src="https://github.com/user-attachments/assets/757726de-d028-4efe-a6c3-83db3c048058">

# How to 
I forgot how to build in command line :
```bash
$ R CMD Sweave R-intro.Rnw
$ (pdf/xe)latex R-into.tex
```
There should be a way to suppress warnings in command line.
or, if the warnings are bothering:

From RStudio as above click `Compile PDF', then
```bash
$ (pdf/xe)latex R-into.tex
```
