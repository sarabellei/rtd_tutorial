Conclusion:
-----------------------------------
**Cling** is not just a **REPL**, it is an embeddable and extensible execution system for efficient incremental execution of C++. **Cling** allows us to decide how much we want to compile statically and how much to defer for the target platform. **Cling** enables reflection and introspection information in high-performance systems such as **ROOT**, or **Xeus Jupyter**, where it provides efficient code for performance-critical tasks where hot-spot regions can be annotated with specific optimization levels. We will see more concrete examples in the slides to follow. 


You can find a detailed explanation of Cling’s design in the following paper: V Vasilev et al 2012 J. Phys.: Conf. Ser. 396 052071
More in detail, the paper describes in detail Cling’s characteristic features  such as syntactic and semantic error recovery, execution of statements, loading of dynamic objects (i.e. external objects loaded at runtime), entity redefinition, and displaying of execution results.
