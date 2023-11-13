# Customized Gepard

Yoshimura-san's repository → `https://bitbucket.org/junyoshi/gepard/src/master/`, which includes following modifications:

- Use `int` rather than `short` for LCP array.
- Draw red lines at boundaries of distinct sequences in a multi-fasta file.

Additional modifications are made in this repository:

- Draw blue lines at the positions of N bases.
- Add option for showing only dot plots, without text information. (TODO: make this an option?)

(We used v1.4.0 instead of v2.1.0 since v2.1.0 is difficult to compile due to its dependency on apache's external libraries.)

## How to compile Java source codes into a single jar file with VScode

1. Install `Extension Pack for Java` in VScode
2. Open the repository directory as a Java project folder
3. In the command palette, `Export Jar` (-> `Proceed` if compilation fails) -> specify `CommaneLine`
4. Then you can run Gepard comman line tool with `java -jar gepard.jar`
