# Customized Gepard

This is based on Yoshimura-san's repository (https://bitbucket.org/junyoshi/gepard/src/master/), which includes following modifications to the original Gepard v1.40.0:

- Use `int` rather than `short` for LCP array.
- Draw red lines at boundaries of distinct sequences in a multi-fasta file.

Additional modifications are made in this repository:

- Draw blue lines at the positions of N bases.
- Option (`-onlyplot`) for showing only dot plots, without any text information and white margins outside the plot.

## How to compile Java source codes into a single jar file with VScode

1. Install `Extension Pack for Java` in VScode
2. Open the repository directory as a Java project folder
3. In the command palette, `Export Jar` (-> `Proceed` if compilation fails) -> specify `CommaneLine`
4. Then you can run Gepard comman line tool with `java -jar gepard.jar`
