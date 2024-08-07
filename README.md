Converts text file to HTML with table of contents linked to each section. 
<pre>
shell> ./txt2html.sh TEXT_FILE   OUT_DIR
shell> ./txt2html.sh sample.txt  ~/t
</pre>
sample.txt  : Must follow below format. All chapter headings must begin with forward slash(/) and seperated by pipe(|)
<pre>
/ Title
some text
/ 1 | Apache-Hadoop-Installation
some text
/ 2 | Topology
some text
/ 2.1 | Master-Nodes
some text
/ 2.2 | Slave-Nodes
some text
/ 3 | Prerequisites
some text
/ 3.1 | Passwordless-SSH-Root
some text
/ 3.1 | Java
some text
/ 3.2 | Create-Users
some text
/ 3.3 | Passwordless-SSH
some text
/ A | References
some text
/ B | Document Version
some text
</pre>
