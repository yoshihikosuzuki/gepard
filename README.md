# Customized Gepard

Most of those changes were originally made by Yoshimura-san for v1.40.0:

- Use `int` rather than `short` for LCP array.
- Draw red lines at boundaries of distinct sequences in a multi-fasta file.
- Draw blue lines at the start positions of N in a contiguous sequence.
- Add option for showing only dot plots, without text information.

Gepard v2.1.0 is difficult to compile (because it uses apache's libraries).

## How to compile into a jar file with VScode

1. Install `Extension Pack for Java` in VScode
2. Open the repository directory as a Java project folder
3. From command palette, `Export Jar` (-> `Proceed` if compilation fails) -> specify `CommaneLine`
4. You can run Gepard comman line tool with `java -jar gepard.jar`
